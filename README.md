# DSPack-continued

DSPack-continued is a set of components and classes to write multimedia
applications using Microsoft DirectShow.

The (original and discontinued DSPack by Henry Gourvest)[https://code.google.com/archive/p/dspack/source/default/commits]
was designed to work with DirectX 9 on Win9X, ME, 2000, and Windows XP
operating systems.  DSPack-continued does not claim support for these old
windows versions anymore.  It may work or not.  It is currently used
successfully in Windows 7.

The main packages, but not the examples, compile with Delphi 2010 and XE3.  For other Delphi versions YMMV.

This version supports Win64, which the original DSPack and the many other imports/forks from Google code likely don't.

## License

DSPack is distributed under the MPL 1.1.

## Features

* Delphinus-Support

## How to install?

* Add "(DSPackDir)\src\DSPack" to your Delphi Library paths (for Win32 or/and Win64)
* Compile DSPack Runtime Package "packages\DSPack_Dx.dproj" (for Win32 or/and Win64, optional?)
* Install DSPack Design Time Package "packages\DSPackDesign_Dx.dproj" (Win32 only, as IDE is a Win32 program)

