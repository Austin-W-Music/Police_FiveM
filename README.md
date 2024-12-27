# Police_FiveM
[![GitHub release](https://img.shields.io/github/release/FiveM-Scripts/Cops_FiveM.svg)](https://github.com/FiveM-Scripts/Cops_FiveM/releases/latest) [![GitHub license](https://img.shields.io/github/license/FiveM-Scripts/Cops_FiveM.svg)](https://github.com/FiveM-Scripts/Cops_FiveM/blob/master/LICENSE)

Police_FiveM is a resource mainly for RP servers. It gives servers a cops system with loadouts, vehicles, fines, ...    
You can find a complete overview with all the features [here](docs/features.md).

## Changelog
You can find the latest changes [here](CHANGELOG.md).

## Community Support
A Discord server is available: [![](https://discordapp.com/api/guilds/361144123681538060/widget.png)](https://discord.gg/qnAqCEd)

## Requirements
If you are using a database then you need to setup **ghmattimysql** before you can start using Cops_FiveM.  
In case you are using **ZAP-Hosting** and don't know what your database name/username/password is then [watch this video](https://www.youtube.com/watch?v=4UcC9zNZkFc).

- Download [ghmattimysql](https://github.com/GHMatti/ghmattimysql/releases/download/1.3.2/ghmattimysql.zip)
- Extract the zipfile and make sure that the folder is named **ghmattimysql**.
- Open ghmattimysql/config.json and edit the config lines with your db name/user/password/host.
- Copy the **ghmattimysql** folder to resources.
- Open `server.cfg` and add **start ghmattimysql**.

## Installation
1. Verify that you have installed the requirements from above.
2. Download the latest version from the [GitHub repository](https://github.com/FiveM-Scripts/Cops_FiveM/releases/latest).    
3. Only copy the subdirectory *police* to the *resources* folder on your server.    
4. Edit [config file](https://github.com/FiveM-Scripts/Cops_FiveM/blob/master/police/config/config.lua) to your preferences    
5. Add *start police* in server.cfg (make sure you start this resource after all dependencies).
6. The first time when you enter the game you will need to add yourself to the police database.    
you can do this in your server console enter `CopAddAdmin 1` or `CopAdd 1` press **enter** and you should receive a confirmation message.

## Commands
You can use these commands with RCON (`PoliceAdd` / `PoliceAddAdmin` / `PoliceDept`/ `PoliceRem` / `PoliceRank`).    
To see how to use them, just type the command you want without any parameter.

## Departments
| ID | Name |
| -- | ---- |
| 0  | Park Rangers |
| 1  | Los Santos Police Department|
| 2  | Blaine County Sheriff's Office |
| 3  | San Andreas State Police |
| 4  | Prison Department |
| 5  | Correctional Department |
| 6  | Probation Department |

## Ranks
| ID | Name |
| -- | ---- |
| 0  | Trainee|
| 1  | Trooper|
| 2  | Master Police Officer|
| 3  | Sergeant|
| 4  | Lieutenant|
| 5  | Captain|
| 6  | Chief of Police|
| 7  | Admin Police Rank|

## Contribute
If you are a developer and would like to contribute any help is welcome!.   
The contribution guide can be found [here](https://github.com/Kyominii/Cops_FiveM/blob/master/CONTRIBUTING.md).
