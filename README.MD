# CS:GO Configuration File

A customized (and customizable) Counter Strike: Global Offensive configuration file.
Feel free to fork this file and adjust it accordingly to your needs.

## How to use?

Save this file inside your CS:GO cfg folder. The path should look similar to 

```
Windows(C:) > Program Files (x86) > Steam > userdata > (your own numbers) > (your own 3 digit file) > local > cfg
```

A shell script (for windows CMD) to find the default configuration file for CS:GO among other installed apps (in a 64bits machine with default installation folder):

```
cd %PROGRAMFILES(X86)% && dir * /s/b | findstr Steam\\userdata\\[0-9]*\\[0-9]*\\local\\cfg\\config.cfg
```

Keeping filename _autoexec.cfg_, the game will execute it everytime the game is launched.

In cases you want to rename the file for whatever reason, you have two options to run:

### 1 - Setting the Steam launcher options (auto-loaded)

* Open Steam and access the game library on the left-hand side.
* Right-click on CSGO and click "Properties"
* Click "Set Launch Options"
* Add `+exec <filename>` and then click "OK" (eg: for filename `custom.cfg`, the command will be `+exec custom.cfg`)

### 2 - Running manually in the console

* Open the console by pressing '
* Type `exec <filename>` and hit Enter (eg: for filename `custom.cfg`, the command will be `exec custom.cfg`)

## License

Licensed under [MIT License](https://opensource.org/licenses/MIT)
