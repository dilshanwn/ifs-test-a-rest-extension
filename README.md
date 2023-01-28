# ifs-test-a-rest-extension README

This can be used to run IFS TAR scripts from vs code using a context menu item in file explorer

## Features

run IFS TAR scripts from vs code using a context menu item in file explorer

![ContextMenu](https://dilshanwn.github.io/imagehost/TarExtRun.jpg "ContextMenu")

## Requirements

Test-A-Rest
VS Code

## Install locally

use install-package.cmd 

or

```
code --install-extension ifs-test-a-rest-extension-<version>.vsix

I.e. 

code --install-extension ifs-test-a-rest-extension-0.0.1.vsix
```

## Extension Settings

Following settings need to be set before use


* `IfsTar.tarExeLocation`: Set to absolute path to the **TestARest.exe** ending with TestARest.exe.
* `IfsTar.ifsUrl`: Set to URL for IFS Environment.
* `IfsTar.ifsUserName`: Set to Username for IFS Environment.
* `IfsTar.ifsPassword`: Set to Password for IFS Environment.

Navigate to File->Preferences->Settings->Extentions->IFS TAR to set up the settings

![Settings](https://dilshanwn.github.io/imagehost/TarSettings.jpg "Sample settings")

## Build package

```
npm install -g @vscode/vsce

vsce package
```

## TODO
* Add walkthrough to setup settings if not set
* try to add multiple environment information