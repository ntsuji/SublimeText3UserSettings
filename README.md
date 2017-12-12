# How to use

## Install

### Install Sublime Text 3
* [Stable](https://www.sublimetext.com/3)
* [Dev](https://www.sublimetext.com/3dev)

### Install [Package Control](https://packagecontrol.io/installation#st3)

### Git Clone `SublimeText3UserSettings`

### Make symbolic link
* Windows

  Run `cmd.exe` as Administrator

  ```
  > cd PATH\TO\PACKAGES
  > rd /s /q User
  > mklink /d User PATH\TO\SublimeText3UserSettings
  ```

* Mac/Linux

  ```
  $ cd PATH/TO/PACKAGES
  $ rm -rf User
  $ ln -s PATH/TO/SublimeText3UserSettings User
  ```

### Edit `Preferences.sublime-settings`
Uncomment machine specific settings.

## Uninstall

### Remove symbolic link

### Remove `SublimeText3UserSettings`
