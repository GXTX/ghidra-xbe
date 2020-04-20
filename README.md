ghidra-xbe ![CI Status](https://github.com/mborgerson/ghidra-xbe/workflows/Build/badge.svg?branch=master) [![Download](https://img.shields.io/badge/-Download-blue)](https://github.com/mborgerson/ghidra-xbe/releases/latest)
==========
This is an extension for the [Ghidra SRE framework](https://ghidra-sre.org/) to support loading Xbox Executable Format (XBE) files, the format used for the [original Xbox game console](https://en.wikipedia.org/wiki/Xbox_(console)). Library symbol recovery is supported through integrated pattern matching against the [XbSymbolDatabase](https://github.com/Cxbx-Reloaded/XbSymbolDatabase).

Download
--------
The latest release of this extension can be [found on the releases page](https://github.com/mborgerson/ghidra-xbe/releases/latest). Download the latest `ghidra_9.1.2_PUBLIC_XXXXXXXX_ghidra-xbe.zip` package. See below for how to install.

How to Build
------------
To build this extension from source on Ubuntu, clone the repository and run the `build.sh` script. The script will download the JDK, Gradle 5.0, and Ghidra release package, then build the extension and output a release package to the `dist` directory.

How to Install
--------------
Copy the extension package `ghidra_9.1.2_PUBLIC_XXXXXXXX_ghidra-xbe.zip` to your Ghidra installation directory `<path to Ghidra root>/Extensions/Ghidra`. When starting Ghidra, in the main window navigate to <kbd>File</kbd>&rarr;<kbd>Install Extensions...</kbd>, and select **XboxExecutableLoader**. You can now import and analyze XBE files!
