[[Refactoring Test Code.pdf#page=2&selection=4,0,4,13|Source (Refactoring Test Code)]]
[Source (TSDetect)](https://testsmells.org/pages/testsmells.html#MysteryGuest)
The test uses external resources, such as a file. Introduces hidden dependencies. The external resources can also change, affecting the tests in hidden ways.

```java
public void testPersistence() throws Exception {
    File tempFile = File.createTempFile("systemstate-", ".txt");
    try {
        SystemState a = new SystemState(then, 27, false, bootTimestamp);
        a.addInstalledApp("a.b.c", "ABC", "1.2.3");

        a.writeToFile(tempFile);
        SystemState b = SystemState.readFromFile(tempFile);

        assertEquals(a, b);
    } finally {
        //noinspection ConstantConditions
        if (tempFile != null) {
            //noinspection ResultOfMethodCallIgnored
            tempFile.delete();
        }
    }
}
```


Refactors:
- [[Refactoring Test Code.pdf#page=3&selection=270,0,272,16|Inline Resource]] Set up the needed information in a fixture instead of a file.
- [[Refactoring Test Code.pdf#page=3&selection=299,0,301,24|Setup External Resource]] Create the files manually within the test. (and then delete them once the test is finished)
