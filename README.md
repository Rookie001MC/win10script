# win10script
## This repo was originally by ChrisTitusTech: https://www.youtube.com/c/ChrisTitusTech
This is the Ultimate Windows 10 Script from a creation from multiple debloat scripts and gists from github. I also added Chocolatey and other tools to the script that I install on every machine.

## Installation
Before installing the script, it is recommended to read the scripts thoroughly and tweak the scripts to your own liking.
Steps:
* Clone the repo
* Open notepad, navigate to your cloned repo, then open win10debloat.ps1, and tweak it to your liking.
* Close notepad, open Windows PowerShell, and then navigate to your cloned repo.
* Type: > ./win10debloat.ps1 (hit tab to autofill)
* Sit back and wait.

## My Additions

- Dark Mode
- One Command to launch and run
- Chocolatey Install
- O&O Shutup10 CFG and Run
- Added Install Programs
- Added Debloat Microsoft Store Apps

## Modifications
I encourage people to fork this project and comment out things they don't like! Here is a list of normal things people change:
- Uninstalling OneDrive (This is on in my script)
- Installing Adobe, Chocolatey, Notepad++, MPC-HC, and 7-Zip

Comment any thing you don't want out... Example:

```
########## NOTE THE # SIGNS! These disable lines This example shows UACLow being set and Disabling SMB1
### Security Tweaks ###
	"SetUACLow",                  # "SetUACHigh",
	"DisableSMB1",                # "EnableSMB1",

########## NOW LETS SWAP THESE VALUES AND ENABLE SMB1 and Set UAC to HIGH
### Security Tweaks ###
	"SetUACHigh",
	"EnableSMB1",
```
