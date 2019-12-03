![CLEVER DATA GIT REPO](https://raw.githubusercontent.com/LiCongMingDeShujuku/git-resources/master/0-clever-data-github.png "李聪明的数据库")

# 如何在Workstations上安装RSAT
#### How To Install RSAT On Workstations
**发布-日期: 2015年6月4日 (评论)**

## Contents

- [中文](#中文)
- [English](#English)
- [Build Info](#Build-Info)
- [Author](#Author)
- [License](#License) 


## 中文
这样;你是一个试图在数据库系统中配置一些东西的DBA，所以你需要浏览Active Directory来查找共享，帐户，组，OU，会员等等。你需要转动Remote Server Administration Tools以便访问dsa.msc。然而，当你转到功能时，你会看到它们丢失了。 现在你必须安装它，然后添加该功能。这里有一些快速步骤可以帮助你完成该过程。

获取.msu文件并使用这些超级简单的步骤进行安装。

1. 下载RSAT：https://www.microsoft.com/en-us/download/details.aspx?id=7887
2. 将其复制到C的根：
3. 从命令提示符运行它（以管理员或管理员帐户打开命令提示符）
4. 粘贴并运行：wusa C：Windows6.1-KB958830-x64-RefreshPkg.msu

只需在安装开始时单击提示即可。大约需要5分钟。


选择以下功能，然后单击提示中的下一个以安装它们。

•	Remote Server Administration Tools
•	Role Administration Tools
•	AD DS and AD LDS Tools
•	Active Directory Administrative Center
•	AD DS Snap-ins and Command-line Tools
•	Server NIS Tools
•	Remote Server Desktop Tools


## English
So; you’re a DBA trying to configure something in the database system, and so it’s pretty ordinary stuff that you’ll need to browse Active Directory to find Shares, Accounts, Groups, OU’s, Members etc. You’ll need to turn the Remote Server Administration Tools on so you can get to dsa.msc. However; when you go to the features you see they are missing. Now you have to install it, and then add the feature. Here’s some quick steps to help you with that process.

Get the .msu file and install it using these super easy steps.

1.	Download RSAT:https://www.microsoft.com/en-us/download/details.aspx?id=7887
2.	Copy it to root of  C:
3.	Run it from command prompt (open the command prompts as administrator or with admin account)
4.	Paste this, and run it:  wusa C:Windows6.1-KB958830-x64-RefreshPkg.msu

Just click through the prompts when the installation starts. Takes about 5 minutes.


![#](images/01-How-To-Install-RSAT-On-Workstations.png?raw=true "#")
 
Next you’ll want to add the feature just as before.
Go to Start Run: appwiz.cpl
接下来，你要像之前那样添加该功能。
转到开始运行：appwiz.cpl

![#](images/02-How-To-Install-RSAT-On-Workstations.png?raw=true "#")
 
Select ‘Turn Windows Features on or off’.
选择“Turn Windows Features on or off”

![#](images/03-How-To-Install-RSAT-On-Workstations.png?raw=true "#")
 
Select the following features, and click next through the prompts to have them installed.

•	Remote Server Administration Tools
•	Role Administration Tools
•	AD DS and AD LDS Tools
•	Active Directory Administrative Center
•	AD DS Snap-ins and Command-line Tools
•	Server NIS Tools
•	Remote Server Desktop Tools

![#](images/04-How-To-Install-RSAT-On-Workstations.png?raw=true "#")
 


[![WorksEveryTime](https://forthebadge.com/images/badges/60-percent-of-the-time-works-every-time.svg)](https://shitday.de/)

## Build-Info

| Build Quality | Build History |
|--|--|
|<table><tr><td>[![Build-Status](https://ci.appveyor.com/api/projects/status/pjxh5g91jpbh7t84?svg?style=flat-square)](#)</td></tr><tr><td>[![Coverage](https://coveralls.io/repos/github/tygerbytes/ResourceFitness/badge.svg?style=flat-square)](#)</td></tr><tr><td>[![Nuget](https://img.shields.io/nuget/v/TW.Resfit.Core.svg?style=flat-square)](#)</td></tr></table>|<table><tr><td>[![Build history](https://buildstats.info/appveyor/chart/tygerbytes/resourcefitness)](#)</td></tr></table>|

## Author

- **李聪明的数据库 Lee's Clever Data**
- **Mike的数据库宝典 Mikes Database Collection**
- **李聪明的数据库** "Lee Songming"

[![Gist](https://img.shields.io/badge/Gist-李聪明的数据库-<COLOR>.svg)](https://gist.github.com/congmingshuju)
[![Twitter](https://img.shields.io/badge/Twitter-mike的数据库宝典-<COLOR>.svg)](https://twitter.com/mikesdatawork?lang=en)
[![Wordpress](https://img.shields.io/badge/Wordpress-mike的数据库宝典-<COLOR>.svg)](https://mikesdatawork.wordpress.com/)

---
## License
[![LicenseCCSA](https://img.shields.io/badge/License-CreativeCommonsSA-<COLOR>.svg)](https://creativecommons.org/share-your-work/licensing-types-examples/)

![Lee Songming](https://raw.githubusercontent.com/LiCongMingDeShujuku/git-resources/master/1-clever-data-github.png "李聪明的数据库")

