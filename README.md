# cgalinstallation
# My instructions for installing CGAL on window


# Setup for 64 bit 
## Boost
Precompiled library dowmloaded from  
https://sourceforge.net/projects/boost/files/boost-binaries/1.64.0/
and install boost_1_64_0-msvc-14.1-64.exe

As per dependancy text following tools configration was used for building them
```Python 2: 2.7.13
Python 2: 2.7.13 amd64
Python 3: 3.6.0
Python 3: 3.6.0 amd64
zlib: 1.2.8
bzip2: 1.0.6


Microsoft Visual Studio 2005 - msvc-8.0 - Service Pack 1
Microsoft Visual Studio 2008 - msvc-9.0 - Service Pack 1
Microsoft Visual Studio 2010 - msvc-10.0 - Service Pack 1
Microsoft Visual Studio 2012 - msvc-11.0 - Update 4
Microsoft Visual Studio 2013 - msvc-12.0 - Update 5
Microsoft Visual Studio 2015 - msvc-14.0 - Update 3
Microsoft Visual Studio 2017 - msvc-14.1 - RTW
```
Also Set 
```
BOOST_LIBRARYDIR=C:\local\boost_1_64_0\lib32-msvc-14.1
BOOST_INCLUDEDIR=C:\local\boost_1_64_0
also add C:\local\boost_1_64_0\lib32-msvc-14.1 to PATH
```
## QT
Set 
```
QTDIR = C:\Qt\5.10.0
also added C:\Qt\5.10.0\msvc2017_64\bin to PATH
```

## Running Triangular 3 demo
copy C:\dev\CGAL-4.11\auxiliary\gmp\lib\libgmp-10.dll to t3_demo.exe folder

