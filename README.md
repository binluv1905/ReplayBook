<p align="center">
<a href="https://www.fraxiinus.dev/ReplayBook/">
<img src=".github/logo/banner_rev2_fullsize.png" alt="ReplayBook Logo Banner Image" width="400"/>
</a>
</p>

![DarkMode](docs/images/0_banner_image.png "Window Overview Image")

[![Build](https://img.shields.io/github/workflow/status/fraxiinus/ReplayBook/Build?style=flat-square)](https://github.com/fraxiinus/ReplayBook/actions?query=workflow%3ABuild)
[![License](https://img.shields.io/github/license/fraxiinus/ReplayBook?style=flat-square)](https://github.com/fraxiinus/ReplayBook/blob/master/LICENSE)
[![Downloads](https://img.shields.io/github/downloads/fraxiinus/replaybook/total?style=flat-square)](https://github.com/fraxiinus/ReplayBook/releases/latest)
[![Donate](https://shields.io/badge/ko--fi-support%20me-green?logo=ko-fi&style=flat-square)](https://ko-fi.com/fraxiinus)

### ReplayBook is a free open-source tool that helps you organize and manage your downloaded replay files

## [Download ReplayBook](https://www.fraxiinus.dev/ReplayBook/pages/downloads.html)

### [Project Website](https://www.fraxiinus.dev/ReplayBook)

### [Get Started Tutorial](https://www.fraxiinus.dev/ReplayBook/tutorial/0_landing.html)

## Need help?

[Check out the Common Problems and Solutions page](https://www.fraxiinus.dev/ReplayBook/pages/common_problems.html),  
[Ask about it in the GitHub Discussions page](https://github.com/fraxiinus/ReplayBook/discussions),  
[Or ask in the developer Discord](https://discord.gg/c33Rc5J).

## Translating

ReplayBook is currently looking for translators! [View the wiki for more information](https://github.com/fraxiinus/ReplayBook/wiki/Translating).

## Building from Source

### Requirements

* Visual Studio 2022
* .NET 6 SDK
* Python 3+

### Steps

1. Open the provided solution file. Set **Rofl.UI.Main** as the startup project. Build the solution, but running it now will crash.
2. Run the provided `scripts\generate-runes.py` python script. This script will create the required rune data files in a new `runes` folder.
3. Repeat step 2 with `generate-items.py` and `generate-champions.py`. Folders `items` and `champions` will be created.
4. Copy the created folders and all the contents to `Rofl.UI.Main\bin\Debug\net6.0-windows10.0.18362.0\data\`. So you should have folders `data\runes`, `data\items`, and `data\champions`.
5. The solution will run successfully now.
