# Scoop-KanColle [![Build status](https://img.shields.io/appveyor/ci/Darkatse/Scoop-KanColle/master.svg?style=popout&logo=appveyor&label=AppVeyor)](https://ci.appveyor.com/project/Darkatse/Scoop-KanColle/branch/master)[![Excavator](https://github.com/Darkatse/Scoop-KanColle/workflows/Excavator/badge.svg)](https://github.com/Darkatse/Scoop-KanColle/actions)


The "Scoop-KanColle" is a scoop bucket built for kancolle players!  
Scoop is a command-line installer for Windows, like homebrew.  
With scoop, you can install, update and (if you want) uninstall these software from the command line with ease.

[English](https://github.com/Darkatse/Scoop-KanColle/blob/master/README.md)|[简体中文](https://github.com/Darkatse/Scoop-KanColle/blob/master/README_CN.md)  

Feature Apps
------------

| Manifest | Description |
|----------|-------------|
| poi | Scalable KanColle browser and tool. |
| poi-np | Installed version of poi|
| poi-nightly | Nightly build of poi |
| WhoCallsTheFleet | powerful kancolle database and fleet simulator |
| ShimakazeGO | A network acceleration tool for KanColle |
| ING | A powerful and resource-saving kancolle browser |
| ElectronicObserver | Another kancolle browser |
| logbook-ex | a log tool for kancolle |
| KCCacheProxy | a local proxy meant to cache KC assets |
| KanColleViewer | 提督業も忙しい！ |



How to start use scoop
=====

Requirements:

* Make sure [PowerShell 5](https://aka.ms/wmf5download) (or later, include [PowerShell Core](https://docs.microsoft.com/en-us/powershell/scripting/install/installing-powershell-core-on-windows?view=powershell-6)) and [.NET Framework 4.5](https://www.microsoft.com/net/download) (or later) are installed. 


On Windows 8 and 10 Power Shell already installed.
For run just type in cmd:

    powershell

To install scoop (run in powershell console):

    Invoke-Expression (New-Object System.Net.WebClient).DownloadString('https://get.scoop.sh')  

*or shorter*  

    iwr -useb get.scoop.sh | iex

Once installed, run `scoop help` for instructions.


How to add this bucket
=====

To make it easy to install apps from this bucket, run  
    `scoop bucket add kancolle https://github.com/Darkatse/Scoop-KanColle.git`
    
Check that it works:

    scoop bucket list

For update run:

    scoop update
    
For example, search all avialable poi packages:
    
    scoop search poi

You've completed all the necessary steps, just enjoy it!
