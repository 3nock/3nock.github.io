---
layout: page
title: Installation
menubar: docs_menu
show_sidebar: false
toc: true
hero_image: /img/hero4.png
hero_height: is-medium
hero_darken: true
image: /img/hero4.png
---

Installing SpiderSuite involves a series of simple steps which must be completed in the correct
sequence for the installation to be successful.

## **To Download**
The installers and portable executable files are available on the SpiderSuite’s Github repository [release page](https://github.com/3nock/SpiderSuite/releases)

SpiderSuite currently supports Windows and Linux operating systems with x64 architecture. On the release page there are two types of download packages for each of the two systems i.e. installers and portable executable.

Installers will install SpiderSuite and its dependencies in default chosen location on your machine. The installers are `SpiderSuite_vX.X.X_win64_installer.exe` for windows and `SpiderSuite_vX.X.X_linux_installer.run` for linux.

Portable executables do not need any installation; you simply download SpiderSuite and use it. The portable executables are `SpiderSuite_vX.X.X_win64.zip` for Windows and `SpiderSuite_vX.X.X_linux.AppImage` and `SpiderSuite_vX.X.X_linux.tar.gz` for Linux

## **To Install**
Please Note: SpiderSuite is a Graphical User Interface application so all of the steps in this guide refer to the SpiderSuite GUI.

* **For Windows Portable Executables:**

Download and extract `SpiderSuite_vX.X.X_win64.zip` archive and place it at your choosen location, extract the archive then run SpiderSuite.exe simply by double clicking on the program.

* **For Linux Portable Executable:**

Download and extract `SpiderSuite_vX.X.X_linux.AppImage` archive and place it at your chosen location, then run it simply by double clicking or using command line with the command:

```bash
./SpiderSuite_vX.X.X_linux.AppImage
```

OR

Download and extract SpiderSuite_vX.X.X_linux.tar.gz archive and place it at your chosen location, extract the archive on desired location (you can use GUI option or command line: 

```bash
tar –xzf SpiderSuite_vX.X.X_linux.tar.gz
```
Then run it simply by double clicking on the SpiderSuite/AppRun.Wrapper or using command line with the command 

```bash
./SpiderSuite/AppRun.Wrapper
```

* **For Windows Installer:**

Download SpiderSuite_vX.X.X_win64_installer.exe then run the installer, then fill in the required information such as installation location and shortcut names precedually until you finish the installation procedure.

* **For Linux Installer:**

Download `SpiderSuite_vX.X.X_linux_installer.run` then run the installer using the command line :

```bash
./SpiderSuite_vX.X.X_linux_installer.run
```
Then fill in the required information such as installation location and shortcut names precedually until you finish the installation procedure.

_**NOTE:**_

In most windows environment SpiderSuite will run on the first try but case of SipderSuite fails to run on the first try on windows, this could be an indication that your machine does not contain the required MSVC-redistributable package. 

Don’t worry, SpiderSuite comes packaged with the required MSVC-redistributable package in case of this. 

Simply Install the MSVC-redistributable package which comes with SpiderSuite (SpiderSuite/vcredist_x64.exe)

Also In case SpiderSuite fails to connect to the internet and shows SSL errors, install the OpenSSL package which comes packaged with SpiderSuite (SpiderSuite/Win64 OpenSSL v1.1.1n Light.msi).

## **To Uninstall**
To uninstall SpiderSuite for portable SpiderSuite, just delete the SpiderSuite folder and you are done.  For installed SpiderSuite run the uninstaller located in the SpiderSuite installation directory (SpiderSuite/maintanance_tool.exe).
