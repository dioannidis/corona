# corona
Downloads daily accumulated case counts of the corona virus disease from the 2019 Novel Coronavirus COVID-19 (2019-nCoV) data repository by Johns Hopkins University CSSE

Plots the data as a function of time.

## Installation
This repository contains Lazarus source files only. Please use Lazarus v2.0.6 or
later to compile the binary.

No additional packages are required to compile the application. But the OpenSSL library must be available. In Windows, copy the files libeay32.dll and ssleay32.dll of the correct bitness to the application directory.

For Windows the OpenSSL dlls can be downloaded from
- 32 bit: https://packages.lazarus-ide.org/openssl-1.0.2j-i386-win32.zip
- 64 bit: https://packages.lazarus-ide.org/openssl-1.0.2j-x64_86-win64.zip

## Data source
https://github.com/CSSEGISandData/COVID-19
