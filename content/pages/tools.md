---
content_type: page
description: This section includes the software requirements and instructions for
  the applications used in the course.
learning_resource_types:
- Tools
ocw_type: CourseSection
title: Tools
uid: 05eaccc2-57be-3899-31db-fc4e04e23b67
---

Overview
--------

21M.385 uses Kivy - an application / graphics framework for Python. We also use a few other packages: numpy, pyAudio (which uses PortAudio), FluidSynth, and rtmidi.

*   Installation files for Mac and Win: {{% resource_link 6c4fa3ab-e73f-ef02-67d6-fc8fd51acf81 "Installation files (ZIP - 5.8MB)" %}} (this ZIP file contains 11 .py files, 1 .sh file, 2 .sf2 files, 7 .dll files, 4 .pyd files, 1 .so file, 2 .dylib files, and 2 .whl files)
*   LEAP Motion files: [download directly from the LEAP site](https://developer.leapmotion.com/sdk/v2)

Follow the steps below to install everything you need for Mac or Windows.

Mac Installation Instructions
-----------------------------

*   Install [Homebrew](http://brew.sh/) if you don't already have it.
*   You will also need Xcode and the Xcode command line tools. Get Xcode from the App store. Make sure to actually run Xcode once to accept the license agreement.
*   Get the OSX install package and unzip it.
*   Open a terminal window and cd to the OSX installation directory (for example, if the OSX package is in Downloads type cd downloads/osx).
*   The rest of the installation is handled by running:  
    $ ./install\_osx.sh

Note this can take a while.

*   Test the installation by running:  
    $ python check\_install.py

Windows Installation Instructions
---------------------------------

*   Install the latest Python 2.7. I recommend using [Miniconda](http://conda.pydata.org/miniconda.html). Select the 32-bit Python 2.7 for Windows. If you already have Python installed, please make sure that:  
    *   You have the latest Python - 2.7.12
    *   It is Python2 (not Python3)
    *   It is the 32bit version of Python (not 64bit)
*   Make sure that the correct version of Python is in your PATH and runnable from the command line. If you installed Python with Miniconda, you will automatically have the PATH set up for you by the installer.
*   Get the [ASIO drivers](http://www.asio4all.com/). The default windows audio drivers are often bad - exhibiting a lot of latency.
*   GET MSVCR110. You'll need the Microsoft [MSVC redistrib library](http://www.microsoft.com/en-us/download/details.aspx?id=30679). Choose vcredist\_x86.exe (the 32bit library) and run to install.
*   Get the win install package and unzip it.
*   From the cmd line, cd to the win directory you just unzipped and run:  
    $ .\\install\_win.bat

This might take a while.

*   Test the installation by running:  
    $ python check\_install.py