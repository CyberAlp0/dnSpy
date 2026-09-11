# dnSpy 6.1.8 — Archive Copy

This repository is a **backup** of the dnSpy v6.1.8 release files, kept in case the upstream downloads are ever removed. Nothing here has been modified.

- **Source:** [dnSpyEx/dnSpy](https://github.com/dnSpyEx/dnSpy) ([README](https://github.com/dnSpyEx/dnSpy/blob/master/README.md))
- **Release:** [`v6.1.8`](https://github.com/dnSpyEx/dnSpy/releases/tag/v6.1.8), tagged December 7, 2020
- **License:** GPLv3 (same as upstream)

## About dnSpy

dnSpy is a debugger and .NET assembly editor. It lets you edit and debug assemblies even without the source code. dnSpyEx is an unofficial continuation of the original dnSpy project.

- **Debugger:** debug .NET Framework, .NET, and Unity game assemblies with no source code required. Supports breakpoints (including conditional ones), stepping into any assembly, locals/watch/autos windows, and debugging several processes at once.
- **Assembly editor:** edit all metadata, edit methods and classes in C# or Visual Basic with IntelliSense, edit IL, and add new methods and classes.
- **Hex editor:** highlights .NET metadata and PE structures, and links hex offsets to decompiled code.
- **Other:** BAML decompiler/disassembler, assembly-wide search, analyzer and reference tracking, and several themes.

It is built on [ILSpy](https://github.com/icsharpcode/ILSpy), [Roslyn](https://github.com/dotnet/roslyn), and [dnlib](https://github.com/0xd4d/dnlib).

## Files

| File | Contents |
|------|----------|
| `dnSpy-net-win64.zip` | 64-bit build for modern .NET (self-contained) |
| `dnSpy-net-win32.zip` | 32-bit build for modern .NET (self-contained) |
| `dnSpy-netframework.zip` | .NET Framework build |
| `dnSpy-6.1.8.zip` | Source code (zip) |
| `dnSpy-6.1.8.tar.gz` | Source code (tar.gz) |

To use a build, extract the zip and run `dnSpy.exe`. The command-line tool is `dnSpy.Console.exe`.

## SHA-256 checksums

```
78d855aef02d87195ddde4f4a89f16f03708e66ec8282cf8eb9ecc89dd469f6c  dnSpy-net-win64.zip
3cb7340b5b0b250a5b8d6cbf45bee4355be09c9a4d4fe2b2fac9abd5c7b95efd  dnSpy-net-win32.zip
99c4bbc73d82c3d0d79f4d50ac08e86c569495a330f770ad2272fbe3843066d3  dnSpy-netframework.zip
e8a2d32f9961b189a38b17c4f664e9b778d0ab2d6397ca5f01021192d2ea72a1  dnSpy-6.1.8.zip
45bd4bd9a2cfa4a661b5d158f219b397d83b6f0a9a29ccd318e48232a16d0753  dnSpy-6.1.8.tar.gz
```

To check a file on Windows: `certutil -hashfile dnSpy-net-win64.zip SHA256`
