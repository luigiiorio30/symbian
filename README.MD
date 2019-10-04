# Symbian

This repository contains a git-repo compatible manifest for cloning the complete Symbian (Symbian^3) source code.

## Getting started
Conexport's Symbian^3 is using Git-Repo, the same tool used in Android to keep all the components of the system synced.

For more information, visit Google's [Using repo](http://source.android.com/source/using-repo.html) page.

Create a new directory where the Symbian code will be cloned and type the following command to initialize it:
```
repo init -u git://github.com/conexport/symbian.git
```

Next, sync the repository (it will download and extract all the data):
```
repo sync
```

Depending on your connection and your hard drive speed,
this step could take a while, the complete Symbian^3 source code is approximatly 13GB.

NOTE: We are using SymbianSource's GitHub repositories for the portions of code that we haven't modified or forked.

## Special thanks to
[SymbianSource](https://github.com/SymbianSource)
