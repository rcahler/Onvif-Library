# Onvif-Library
## Building
With the latest version of Visual Studio installed do the following
- run Build01.bat
- add #import "wsse.h" in the onvif.h and change #import "wsdd10.h" to #import "wsdd.h" in onvif.h
- run Build02.bat
- run Build03.bat

Any changes that are made to which wsdl and schema files are used needs to be reflected in the build files and in the Visual Studio project file

## Recreating from scratch
### Downloading and Installing
##### Visual Studio
  - Download the newest version of Microsoft [Visual Studio](https://www.visualstudio.com/), the project was originally built using 2017 Community Edition
  - Install, making sure to include the build tools
##### OpenSSL
  - Download [OpenSSL](https://www.openssl.org/) source code, any version newer than 1.1.0 will work.
  - Using the Visual Studio build tools (Native and Cross) to compile all combinations of 32bit/64bit and Debug/Release OpenSSL. Much of the OpenSSL docs are out of date, this [tutorial](http://p-nand-q.com/programming/windows/building_openssl_with_visual_studio_2013.html) can help.
##### gSoap
  - Download the latest gSoap, 2.8.66 was used to build this project.
  - Licensing for gSoap differs depending on the planned usage, so read the [licensing](https://www.cs.fsu.edu/~engelen/soap.html) before decinding whether to use the [open source](https://sourceforge.net/projects/gsoap2/) or [commercial](https://www.genivia.com/products.html#gsoap) version of gSoap.
##### Onvif WSDL and Schema files
