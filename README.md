
 <img style="display: block; margin-left: auto; margin-right: auto; width:30%;" src="https://raw.githubusercontent.com/kozabrada123/PyLunaroRPC/main/assets/images/Lunaro-logo.png" alt="project logo" width="30%"/>

# PyLunaroRPC
A simple tool for Lunaro in Warframe which shows current match data on your profile with Discord RPC.

![GitHub](https://img.shields.io/github/license/kozabrada123/PyLunaroRPC?style=for-the-badge)
![GitHub top language](https://img.shields.io/github/languages/top/kozabrada123/PyLunaroRPC?style=for-the-badge)
![Github Commit Activity m](https://img.shields.io/github/commit-activity/m/kozabrada123/PyLunaroRPC?style=for-the-badge)
![GitHub last commit](https://img.shields.io/github/last-commit/kozabrada123/PyLunaroRPC?style=for-the-badge)
![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/kozabrada123/PyLunaroRPC?style=for-the-badge)
![LOC](https://img.shields.io/tokei/lines/github/kozabrada123/PyLunaroRPC?style=for-the-badge)
![GitHub issues](https://img.shields.io/github/issues/kozabrada123/PyLunaroRPC?style=for-the-badge)
![Libraries.io dependency status for GitHub repo](https://img.shields.io/librariesio/github/kozabrada123/PyLunaroRPC?style=for-the-badge)

<br/>


![No Windows Binaries](https://raw.githubusercontent.com/kozabrada123/PyLunaroRPC/44d0c6136a4a18850e5776e89010a690f6891714/assets/images/no-windows-binaries.svg)
![Lunaro](https://raw.githubusercontent.com/kozabrada123/PyLunaroRPC/98189fcc19354dd62ea8f43dc8d8ad4ef6d6f41b/assets/images/lunaro.svg)

<br/>

- [PyLunaroTracker](#PyLunaroTracker)
  - [Prerequisites](#prerequisites)
  - [Getting Started](#getting-started)
  - [Usage](#usage)
  - [Troubleshooting](#troubleshooting-and-common-issues)
 - [Todo](#to-do-and-future-updates-to-excpect)



## Prerequisites

* Python 3.7+
* Discord
* Warframe to play lunaro

<br/>

* **Currently running on Linux is a bit of a pain, because Keyboard needs Sudo**

## Getting Started

- First, download or git clone this repo.
- Install the python requirements with `pip3 -r requirements.txt`.
- Everything should now be set up!

## Usage:

- Start the program with `python3 main.py` (or `python main.py`)
- (**Make sure to launch LunaroRPC before Warframe**)
- Launch Warframe
- Go into a game of lunaro
- Press 'o' (default hotkey, configurable in settings.py) while holding TAB
- If everything is set up correctly, the players from both team should be visible on your profile.

## Troubleshooting and common issues:

- `No package .. was found` - This usually means you haven't installed the requirements correctly, try manually installing the library with pip


- Can't see presence on profile - This usually means you haven't enabled Game Activity in Discord Settings (`Settings/Activity Status/Display current activity as status message`). If you have, try to exit any other running games or try to turn Game Activity On and Off. 


- Discord SDK Error 4 - this is an **internal server error, an error on Discord's side**. This means that I have no idea how to fix it.

- Problems with requirements - there might be mismatch between your python and pip, try running `python3 -m pip install -r requirements.txt` or `python -m pip install -r requirements.txt`.


## TO-DO And Future Updates To Excpect

- ~~**At least basic Ui**~~ - I've Tried, pls no

If you submit a pull request for a working ui I'll take a look at it but I do not want to get my anus penetrated with trying to handle all the ui threads

- Windows binary (Soon TM)
