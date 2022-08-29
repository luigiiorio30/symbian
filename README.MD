# Symbian

Attemps at using Symbian^3 EPL source code.

[What is Symbian?](https://en.wikipedia.org/wiki/Symbian_OS)

## Acquiring a toolchain
There are three toolchains that could be used for building Symbian^3:
- ARM RealView Development Suite 2 (RVCT 2)
- ARM RealView Development Suite 4 (RVCT 4)
- CodeSourcery G++ Lite (GCCE)

RVCT2 is the compiler which was used by Symbian, this is a legacy C++ closed source compiler developer by ARM.

RVCT4 is an evolution of RVCT2, RVCT4 was not fully compatible with Symbian, see [this page](https://akawolf.org/wiki/index.php/Compiler_Compatibility/RVCT) for more information.

You can grab both RVCT 2 and RVCT 4 by login in with your ARM developer account at the [ARM Sliver](https://silver.arm.com) website.

GCCE (GCC Embedded) is a fork of GCC made by CodeSourcery. The GCC base version is 4.3.2. The installers might not correctly work under modern systems.

## Building the code
This repository contains the source code of Symbian^3 EPL release.
You can clone the compilete source code by using the git-repo (the same tool used in Android)

For more information, visit Google's [repo](https://gerrit.googlesource.com/git-repo/+/refs/heads/master/README.md) page.


Create a new directory where the Symbian code will be cloned and type the following command to initialize it:
```
repo init -u https://github.com/conexport/symbian
```

Next, sync the repository (it will download and extract all the data):
```
repo sync
```

Depending on your connection and your hard drive speed, 
this step could take a while, the complete Symbian^3 source code is approximatly 13GB.

NOTE: SymbianSource's repositories are being used for the portions of code not forked.

## References
[Symbian developer wiki (archived)](https://akawolf.org/wiki/index.php/Main_Page)
[SymbianSource](https://github.com/SymbianSource)
