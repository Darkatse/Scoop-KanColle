# Scoop-KanColle [![Build status](https://img.shields.io/appveyor/ci/Darkatse/Scoop-KanColle/master.svg?style=popout&logo=appveyor&label=AppVeyor)](https://ci.appveyor.com/project/Darkatse/Scoop-KanColle/branch/master)

"Scoop-KanColle "是一款为砍口垒玩家打造的scoop源！  
[*Scoop简介 —— Windows 上体验最好的「包管理器」*](https://sspai.com/post/52496)

[English](https://github.com/Darkatse/Scoop-KanColle/blob/master/README.md)|[简体中文](https://github.com/Darkatse/Scoop-KanColle/blob/master/README_CN.md)  

包含哪些软件？
------------

| 名称 | 描述 |
|----------|-------------|
| poi | 可扩展的「舰队 Collection」浏览器_ |
| poi-np | poi 本地安装版本|
| poi-nightly | poi 的每夜构建版本 |
| WhoCallsTheFleet | 多功能kancolle数据库与舰队配置模拟 |
| ShimakazeGO | ACG相关网站综合辅助工具 |
| ING | 功能强大资源节省的kancolle浏览器 |
| ElectronicObserver | 七四式電子観測儀 |
| logbookex | 航海日誌 拡張版 |
| KanColleViewer | 提督很忙！ |



如何使用scoop
=====

前置要求:

* 确保至少安装了 [PowerShell 5](https://aka.ms/wmf5download) (或者 [PowerShell Core](https://docs.microsoft.com/en-us/powershell/scripting/install/installing-powershell-core-on-windows?view=powershell-6)) 以及 [.NET Framework 4.5](https://www.microsoft.com/net/download) 。


在 Windows 8 和 10 当中 Power Shell 已经被安装了  
想要安装Scoop，只需要在 Power Shell 中输入  

    Invoke-Expression (New-Object System.Net.WebClient).DownloadString('https://get.scoop.sh')  

*或者用短命令*  

    iwr -useb get.scoop.sh | iex

安装后请输入 `scoop help` 来查看指南。


如何添加该源
=====

简单的在 Power Shell 输入  
    `scoop bucket add kancolle https://github.com/Darkatse/Scoop-KanColle.git`  
即可
    
查看是否成功：

    scoop bucket list

更新scoop列表：

    scoop update
    
测试下能否搜到poi浏览器:
    
    scoop search poi

恭喜你，你已经完成了所有必要的操作！
