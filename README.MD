# CS:GO Configuration File

A customized (and customizable) Counter Strike: Global Offensive configuration file.
Feel free to fork this file and adjust it accordingly to your needs.

## How to use?

Save this file inside your CS:GO cfg folder. You cand find game install location using Steam:
- In your library tab, right-click _Counter-Strike: Global Offensive_ and select __Properties__
- Go to __Local Files__ tab
- Select __BROWSE LOCAL FILES__. Windows Explorer will be opened in the folder where game is installed.
- Navigate to _csgo > cfg_. This is the place where the file should be placed.

For the default path installation, it should look similar to 

```
C:\Program Files (x86)\Steam\steamapps\common\Counter-Strike Global Offensive\csgo\cfg
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
