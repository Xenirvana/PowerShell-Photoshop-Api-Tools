# PowerShell Photoshop API Tools
**PowerShell-Photoshop-API-Tools** is a PowerShell Script Module designed to enable PowerShell users to work with, automate, and manipulate the Adobe Photoshop Creative Cloud (CC2013-CC2021) API via leveraging Microsoft PowerShell Scripts in the same manner as users of Photoshop have been 'officially' able to do using JavaScript, VBScript, and AppleScript, in the past.
This Module is written to maintain full compatibility with both 'Desktop' and 'Core' Editions of Microsoft PowerShell.

## Table of Contents
> * [PowerShell Photoshop API Tools](#powershell-photoshop-api-tools)
> * [Table of Contents](#table-of-contents)
> > * [Overview & Functionality](#overview-&-functionality)
> > > * [Application Management](#application-management)
> > > * [File Manipulation](#file-manipulation)
> > > * [Automation Scripts](#automation-scripts)
> > * [Installation](#installation)
> > > * [Requirements](#requirements)
> > > * [Manual Install](#manual-install)
> > > * [PowerShell Gallery](#powershell-gallery)
> > * [How to Use](#how-to-use)
> > * [Currently Available Functions](#currently-available-functions)
> > > * [Unregister-ComObject](#unregister---comobject)
> > > * [Set-CloseWindow](#set---closewindow)
> > > * [Start-Photoshop](#start---photoshop)
> > > * [Close-Photoshop](#close---photoshop)
> > > * [ExportAs-PNG](#exportas---png)
> > * [Photoshop Profile Script](#photoshop-profile-script)
> * [Project Updates](#project-updates)
> * [Contributing](#contributing)
> * [License](#license)
> * [Contact the Developer](#contact-the-developer)

## Overview & Functionality

### Application Management
**Application Management** - Ability to start and terminate Photoshop processes/instances with Extended Command-Line Arguments.

### File Manipulation
**File Manipulation** - Ability to Export, Import, Convert, and even perform any editing tasks you could normally do using Photoshop Automation Scripts directly from the PowerShell Console.

### Automation Scripts
**Automation Scripts** - Extending Photoshop's already rich Automation Scripting features by adding PowerShell to the list of compatible Scripting Languages, alongside JavaScript, Visual Basic Script, and AppleScript!

## Installation

### Requirements
**Requirements are as follows:** 
* *Microsoft Windows PowerShell v5+* **OR** *Microsoft PowerShell Core v6+*
* *Adobe Photoshop CC2013-CC2021*
* *PowerShell-Photoshop-API-Tools Module*

### Manual Install
**To Manually install:** 
* Download the zip archive from this Repository (*PowerShell-Photoshop-API-Tools - master*)
* Unpack it's contents (a folder named *PowerShell-Photoshop-API-Tools*) to your preferred $PSModulePath Directory
* In PowerShell Console run the following Cmdlet:
* **Import-Module -Name PowerShell-Photoshop-API-Tools** 

### PowerShell Gallery
**To Install via PowerShell Gallery:**
* In PowerShell Console run the following Cmdlets:
* **Install-Module -Name PowerShell-Photoshop-API-Tools** 
* **Import-Module -Name PowerShell-Photoshop-API-Tools** 

## How to Use

### Currently Available Functions

#### Unregister-ComObject

#### Set-CloseWindow

#### Start-Photoshop

#### Close-Photoshop

#### ExportAs-PNG

## Photoshop Profile Script
**PhotoshopAPI_profile.ps1** - A PowerShell Profile Script pre-configured with additional Functions, Aliases, and Variables to improve your Command-Line image editing capabilities!

## Project Updates

## Contributing

## License
[GNU General Public License v3]()

## Contact the Developer
To contact me please use my primary email for all Development work:

[Contact via Email](sierracreative@outlook.com)
