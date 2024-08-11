---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: page
permalink: /install
title: Install
nav_order: 3
---

## Install Prerequisites

- Unity 2021.3.23f1
- git
- ChilloutVR CCK

### Unity

Please download and install from the unity official [release site](https://unity.com/releases/editor/archive)\
The currently supported version is `2021.3.23f1`

### Git

Git is needed to install the project package via the unity package manager, please download from the official
 [Git site](https://git-scm.com/)

### ChilloutVR CCK

This package is for use with the ChilloutVR CCK, please download from the official ABI Interactive
[downloads page](https://docs.abinteractive.net/cck/setup/)\
The currently supported version is `3.10`

---

## Unity Package Prerequisites

Note the following should be auto installed to the project by adding this package

- com.unity.nuget.newtonsoft-json: 3.1.0
- com.unity.vectorgraphics: 2.0.0-preview.21
- com.unity.editorcoroutines: 1.0.0

## Installation

1. In unity open the `Package Manager` window
2. Click the plus button in the top left of that window and choose the `Add packages from git URL` option
3. Paste in the git url of this repo `https://github.com/NovaVoidHowl/CVRFury.git#alpha`
4. Click the add button

The script should then be ready to configure via `NVH -> CVRFury -> Tool Setup`.
> ⓘ \
Recommendation is to install all app components from the Tool Setup menu to enable all possible features

## Core Update Manager

Should you want to switch to a different release channel or specific release of the software, you can do this via the menu
option at `NVH -> CVRFury -> Update Manager`\
> ⓘ \
Note it is recommended to restart unity after switching to a new channel or specific release