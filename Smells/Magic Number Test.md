[Source (TSDetect)](https://testsmells.org/pages/testsmells.html#MagicNumberTest)

Detection: Check if, for any assertion, any of the given arguments are numeric literals. 
Fix: Extract said numeric literal as a local constant.


[Similar tutorial](https://learn.microsoft.com/en-us/archive/msdn-magazine/2014/special-issue/csharp-and-visual-basic-use-roslyn-to-write-a-live-code-analyzer-for-your-api)


## Testing
- [ ] AreEqual(Object, Object): ok
- [ ] AreEqual(String, String): ok, literal 1st, literal 2nd, both literal
- [ ] AreEqual(Double, Double, Double): ok, literal 1st, literal 2nd, both literal
- [ ] AreEqual(Single, Single, Single): ok, literal 1st, literal 2nd, both literal
- [ ] AreEqual(sbyte, sbyte): ok, literal 1st, literal 2nd, both literal
- [ ] AreEqual(byte, byte): ok, literal 1st, literal 2nd, both literal
- [ ] AreEqual(short, short):ok, literal 1st, literal 2nd, both literal
- [ ] AreEqual(ushort, ushort): ok, literal 1st, literal 2nd, both literal
- [ ] AreEqual(int, int): ok, literal 1st, literal 2nd, both literal
- [ ] AreEqual(uint, uint): ok, literal 1st, literal 2nd, both literal
- [ ] AreEqual(long, long): ok, literal 1st, literal 2nd, both literal
- [ ] AreEqual(ulong, ulong): ok, literal 1st, literal 2nd, both literal
- [ ] AreEqual(nint, nint): ok, literal 1st, literal 2nd, both literal
- [ ] AreEqual(nuint, nuint): ok, literal 1st, literal 2nd, both literal

- [ ] AreNotEqual(Object, Object): ok
- [ ] AreNotEqual(String, String): ok, literal 1st, literal 2nd, both literal
- [ ] AreNotEqual(Double, Double, Double): ok, literal 1st, literal 2nd, both literal
- [ ] AreNotEqual(Single, Single, Single): ok, literal 1st, literal 2nd, both literal
- [ ] AreNotEqual(sbyte, sbyte): ok, literal 1st, literal 2nd, both literal
- [ ] AreNotEqual(byte, byte): ok, literal 1st, literal 2nd, both literal
- [ ] AreNotEqual(short, short):ok, literal 1st, literal 2nd, both literal
- [ ] AreNotEqual(ushort, ushort): ok, literal 1st, literal 2nd, both literal
- [ ] AreNotEqual(int, int): ok, literal 1st, literal 2nd, both literal
- [ ] AreNotEqual(uint, uint): ok, literal 1st, literal 2nd, both literal
- [ ] AreNotEqual(long, long): ok, literal 1st, literal 2nd, both literal
- [ ] AreNotEqual(ulong, ulong): ok, literal 1st, literal 2nd, both literal
- [ ] AreNotEqual(nint, nint): ok, literal 1st, literal 2nd, both literal
- [ ] AreNotEqual(nuint, nuint): ok, literal 1st, literal 2nd, both literal



- [ ] AreSame(Object, Object): ok
- [ ] AreSame(String, String): ok, literal 1st, literal 2nd, both literal[]()
- [ ] AreSame(Double, Double, Double): ok, literal 1st, literal 2nd, both literal
- [ ] AreSame(Single, Single, Single): ok, literal 1st, literal 2nd, both literal
- [ ] AreSame(sbyte, sbyte): ok, literal 1st, literal 2nd, both literal
- [ ] AreSame(byte, byte): ok, literal 1st, literal 2nd, both literal
- [ ] AreSame(short, short):ok, literal 1st, literal 2nd, both literal
- [ ] AreSame(ushort, ushort): ok, literal 1st, literal 2nd, both literal
- [ ] AreSame(int, int): ok, literal 1st, literal 2nd, both literal
- [ ] AreSame(uint, uint): ok, literal 1st, literal 2nd, both literal
- [ ] AreSame(long, long): ok, literal 1st, literal 2nd, both literal
- [ ] AreSame(ulong, ulong): ok, literal 1st, literal 2nd, both literal
- [ ] AreSame(nint, nint): ok, literal 1st, literal 2nd, both literal
- [ ] AreSame(nuint, nuint): ok, literal 1st, literal 2nd, both literal

- [ ] AreNotSame(Object, Object): ok
- [ ] AreNotSame(String, String): ok, literal 1st, literal 2nd, both literal
- [ ] AreNotSame(Double, Double, Double): ok, literal 1st, literal 2nd, both literal
- [ ] AreNotSame(Single, Single, Single): ok, literal 1st, literal 2nd, both literal
- [ ] AreNotSame(sbyte, sbyte): ok, literal 1st, literal 2nd, both literal
- [ ] AreNotSame(byte, byte): ok, literal 1st, literal 2nd, both literal
- [ ] AreNotSame(short, short):ok, literal 1st, literal 2nd, both literal
- [ ] AreNotSame(ushort, ushort): ok, literal 1st, literal 2nd, both literal
- [ ] AreNotSame(int, int): ok, literal 1st, literal 2nd, both literal
- [ ] AreNotSame(uint, uint): ok, literal 1st, literal 2nd, both literal
- [ ] AreNotSame(long, long): ok, literal 1st, literal 2nd, both literal
- [ ] AreNotSame(ulong, ulong): ok, literal 1st, literal 2nd, both literal
- [ ] AreNotSame(nint, nint): ok, literal 1st, literal 2nd, both literal
- [ ] AreNotSame(nuint, nuint): ok, literal 1st, literal 2nd, both literal