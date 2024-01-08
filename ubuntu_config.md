Ubuntu Config

# Ubuntu
## Appearance
- Dark
- Auto hide the dock 
- Panel mode off
- Icon size max
- trash off
- Remove some favs on the dock
- Select bg

## Displays
- Nightlight `18 to 7`
- desktop icons off `sudo apt install gnome-shell-extension-prefs`

## Keyboard
- close_window Ctrl Q
- screenshot Prsc
- home_folder Super E
- fullscreen F11

## Multitasking
- Number of workspaces 1

## Date&Time
- lang en

## Users
- no passwd
```
sudo visudo `fira ALL=(ALL) NOPASSWD:ALL`

// admin:///etc/polkit-1/localauthority/50-local.d/nopw.pkla
[No password prompt]
Identity=unix-group:sudo
Action=*
ResultActive=yes
```

## Sound
- system sound off

## Power
- automatic screen brightness off

## Printer
- search for driver(`linux64 ij debian`) `https://in.canon/en/support/search`

## Privacy:Tmpfile&Trash
- auto delete files after 30days

# Files
- add templates

# Gedit
- autosave
- tab use spaces: 2spaces
- line nums off
- status bar off

# Image Viewer
- smooth off

# Chromium
- sys title bar off
- Add bookmarks: OI,Github,recreation..
- Add folders in all bookmarks: Blogs,Tools,Todo..
- Exs: adguard newtab justblack lulutranslate
- Exs allow in incognito

# Code
- welcome page off
- auto save
- hide activity & tab & status & menu bar
- workspace trust `/home`
- sudo apt install g++
- Exs: atom-style code-runner idea-shortcuts cmake
- Code-runner: run_in_ter auto_focus_ter
```
    "code-runner.executorMap": {
        // "cpp": "cd $dir && g++ $fileName -o $fileNameWithoutExt && $dir$fileNameWithoutExt",
        "cpp": "cd $dir && g++ \"$fileName\" -o \"$fileNameWithoutExt\" && \"$dir$fileNameWithoutExt\"",
    }
```
- font: "Fira Code"
- shortcuts
```
run_code ctrl r
stop_running ctrl e
close_file ctrl w
open_containing_folder ctrl shift o
```

# Git
- config `git config user.email _email`
- save pws `git config --global credential.helper store`

# Sogou input
- Fcitx
- Fcitx autostart `sudo cp /usr/share/applications/fcitx.desktop /etc/xdg/autostart/`
- Fcitx globalcfg:appearance `dont show input method hint`
- Fcitx clipboard `ctrl ;`
- Delete ibus `sudo apt purge ibus`
- Install dependence 
```
sudo apt install libqt5qml5 libqt5quick5 libqt5quickwidgets5 qml-module-qtquick2
sudo apt install libgsettings-qt1
```
- hide status bar
- skin setting
- pinyin `mohuyin`

# ThunderBird
- Config mail devvhy@zohomail.cn
- junk 

# v2raya
- dependence `sudo apt install v2ray`
- login: name f pw firafira
- proxy only gfwlist

# Wine
- `winecfg`
- open with `wine windows program loader`
- delete a program `/home/fira/.local/share/applications/`

# Fonts
- From gh/firavoyage/fonts
- install

# Softwares
- VLC
- OBS
- Eudic
- Tg Desktop
- Dingtalk





