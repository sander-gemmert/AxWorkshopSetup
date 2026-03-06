# Workshop Setup

This document describes the steps to setup the AX Code environment.
The official online documentation will be referenced in this document.
[SIMATIC AX • Industrial Operations X Documentation](https://docs.industrial-operations-x.siemens.cloud/p/simatic-ax)

Please follow and complete all steps before the workshop.
If any problems arise, please get into contact before the workshop date.

### Table of contents

1. [Installing AX Code](#Installation_of_AX_Code)
2. [Installing mandatory software](#Installing_Mandatory_Software)
3. [Installing additional software](#Installing_Additional_Software)
4. [Testing with the Quickstart](#Testing_installation_with_the_Quickstart)

## Installation of AX Code

First we start with the installation of AX Code. You can download it on the [SIMATIC AX](https://console.simatic-ax.siemens.io/) console page.
Please follow the online documentation for the installation.

💿 [Guide - Installing AX Code](https://docs.industrial-operations-x.siemens.cloud/r/en-us/ax/get-started/2510/setting-up-simatic-ax-logic-control-engineering/installing-ax-code)

## Installing mandatory Software

Some additional software is required for using AX Code:

* Node.js version 22
* A recent version of the Microsoft Visual C++ Redistributable
* Git - for version control
* Visual Studio Build Tools - for unit testing within AX Code

💿 [Guide - Installing mandatory software](https://docs.industrial-operations-x.siemens.cloud/r/en-us/ax/get-started/2510/setting-up-simatic-ax-logic-control-engineering/installing-additional-software/installing-mandatory-software)

## Installing additional software

For this workshop PLCSIM Advanced is used to simulate the PLC. It is possible to complete the workshop with physical hardware, please make sure the hardare is compatible for this workshop.

* [S7-1500](https://docs.industrial-operations-x.siemens.cloud/r/en-us/ax/hw-s7-1500/4.3.0/s7-1500-hardware-support-package/supported-hardware)
* [ET 200SP](https://docs.industrial-operations-x.siemens.cloud/r/en-us/ax/hw-et200sp/4.3.0/et200sp-hardware-support-package/supported-hardware)

> Note: During the workshop we will focus on the modules which are supported by the Hardware Engineering Tools of SIMATIX AX at this moment, see the links above.

### 1.Installation of SIMATIC PLCSIM Advanced

The latest version of PLCSIM Advanced can be used to simulate a PLC with the AX Code development workflow.

💿 Download and install SIMATIC S7-PLCSIM Advanced V8.0.
The download can be found here: [SIMATIC S7-PLCSIM Advanced V8.0 download](https://support.industry.siemens.com/cs/document/109990051/simatic-s7-plcsim-advanced-v8-0-download-incl-trial-license-?dti=0&lc=en-NL)

📃 When using PLCSIM Advanced for the first time; and if you don't have a valid license, you are able to start the 21-day trail.

### 2.Installation of SIMATIC PC Identifier

⛔️ The installation of SIMATIC PC Identifier is not nessesary when SIMATIC PLCSIM Advanced is installed, the PLCSIM Advanced installation also includes the software.

[Installing SIMATIC PC Identifier](https://docs.industrial-operations-x.siemens.cloud/r/en-us/ax/get-started/2510/setting-up-simatic-ax-logic-control-engineering/installing-additional-software/installing-optional-software/installing-simatic-pc-identifier-pc-identifier)

### 3.Configuring Git

If you would like to save your project and have version control. You can [configure Git](https://docs.industrial-operations-x.siemens.cloud/r/en-us/ax/get-started/2510/setting-up-simatic-ax-logic-control-engineering/configuring-installed-software/configuring-git) and [create a new repository](https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-new-repository).

## Testing with the Quickstart

Now the installation is complete, we will need to test if it is successfully installed and everything is working as it should be. For this we will use the quickstart project template.

🙌 Go the the official Quickstart documentation and follow the steps:
[Quickstart guide](https://docs.industrial-operations-x.siemens.cloud/r/en-us/ax/get-started/2510/quickstart)

At the end of the quickstart you have accomplished the following:

* You will have setup your first AX Logic Control Engineering project.
* You have tested it.
* You have deployed it to PLC
* And you have monitored the program and changed its variables.

✅ By successfully going through the quickstart we have tested that the AX Code environment is installed correctly and you are ready for the [AX Introduction Workshop](https://github.com/sander-gemmert/AxWorkshop)!

