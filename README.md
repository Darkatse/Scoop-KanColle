# Scoop-KanColle

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
| ShimakazeGO | A network acceleration tool for KanColle |



How to start use scoop
=====

Requirements:

* [PowerShell 3](http://www.microsoft.com/en-us/download/details.aspx?id=34595)
* PowerShell must be enabled for your user account e.g. `set-executionpolicy unrestricted -s cu`


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