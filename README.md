# Onvif-Library
##Building
With the latest version of Visual Studio installed do the following
- run Build01.bat
- add #import "wsse.h" in the onvif.h and change #import "wsdd10.h" to #import "wsdd.h" in onvif.h
- run Build02.bat
- run Build03.bat
Any changes that are made to which wsdl and schema files are used needs to be reflected in the build files and in the Visual Studio project file

##Recreating from scratch
