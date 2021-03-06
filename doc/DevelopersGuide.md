#DevelopersGuide
*Aparapi developers guide. Updated Sep 13, 2011 by frost.g...@gmail.com*
##Developer Guide
Although the vast majority of the Aparapi code is Java® we do include some to C++ code (accessed from Java™ via JNI) to interface with existing OpenCL™ C/C++ headers and libraries. Therefore to build Aparapi for a given platform (Microsoft® Windows® 32- or 64- bit and or Linux® 32- or 64- bit) we do require developers to setup a build environment containing both Java® and C++ development tools. In this documentation we will describe the tools required to build Aparapi for the various supported platforms.

##Supported Platforms
In general Aparapi can be used on any platform currently supported by AMD APP SDK v2.5 or later. Please check the AMD APP SDK site for details on supported platforms and installation help.

[http://developer.amd.com/sdks/amdappsdk/downloads/pages/default.aspx](http://developer.amd.com/sdks/amdappsdk/downloads/pages/default.aspx)

[http://developer.amd.com/sdks/AMDAPPSDK/assets/AMD_APP_SDK_Installation_Notes.pdf](http://developer.amd.com/sdks/amdappsdk/downloads/pages/default.aspx)

* 32-bit Microsoft® Windows® 7
* 32-bit Microsoft® Windows Vista®
* 64-bit Microsoft® Windows® 7
* 64-bit Microsoft® Windows Vista®
* 32-bit Linux®
* 64-bit Linux®

Clearly we will also depend on platform specific Oracle® Java® JDK 6 components and C++ compilers along with some platform neutral tools (such as SVN, ant and Junit) .

## Platform Specific Developer Guides
We have broken the Developer Guide into two separate docs. One for Linux® (32- and 64- bit) and another for Microsoft® Windows® (32- and 64- bit). Please follow the appropriate link below.

[DevelopersGuideLinux](DevelopersGuideLinux.md)

[DevelopersGuideWindows](DevelopersGuideWindows.md)

Attribution