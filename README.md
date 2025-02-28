# Counter Strike Auto-Accept

#### Preview/Story

- When playing on the offical servers you have to press the `ACCEPT` button to accept the game
- This AutohotKey-Script let's you fetch a fresh beer and snacks from the kitchen while this script keeps on clicking the spot where the button will appear
- It also keeps your avatar busy during warm-up

![alt text](https://github.com/klaus-moser/counter-strike-auto-accept/blob/master/images/readme/test-image-orig.png?raw=true)

#### Compatibility

| Game | Current status    | Result    |
| :---   | :---: | :---: |
| Counter-Strike | not tested   | ❌   |
| Counter-Strike: Condition Zero | not tested   | ❌   |
| Counter-Strike: Source | not tested   | ❌   |
| Counter Strike: Global Offensive | fully tested   | ✅   |
| Counter Strike 2   | fully tested   | ✅   |

#### Requirements
- Requires AutoHotkey v2.0
- https://www.autohotkey.com/download/ahk-v2.exe

#### Contents
- `counter-strike-auto-accept.ahk` is the standard script that only moves and clicks repeatedly
- `counter-strike-auto-accept-color-check.ahk` is a script that tries to identify the "ACCEPT" colors, click and auto stop

#### Installation
- Clone or download the repo
- Click and install AutoHotKey via the `ahk-v2.exe`
- Double-Click the `counter-strike-auto-accept.ahk` to load script
- You can check your taskbar in the down right corner if it was installed & loaded successfully

![alt text](https://github.com/klaus-moser/counter-strike-auto-accept/blob/master/images/readme/check-taskbar.jpg?raw=true)

#### Usage
- Start or Stop the clicker via [Strg] + [F11]
- ✨Magic ✨

#### Auto startup
- After every reboot/start-up, AutoHotkey (and the`counter-strike-auto-accept.ahk` is inaktive)
- You have to execute the script again to start Autohotkey and load the script
- If you want to autostart the script press [win] + R to open the command line
- Enter following command `shell:startup`

![alt text](https://github.com/klaus-moser/counter-strike-auto-accept/blob/master/images/readme/open-auto-start-with-command.jpg?raw=true)

- Put the `counter-strike-auto-accept.ahk` into this folder
  
![alt text](https://github.com/klaus-moser/counter-strike-auto-accept/blob/master/images/readme/auto-startup-folder.jpg?raw=true)

- The script will be executed with each start-up/reboot to be ready to use with [Strg] + [F11]

#### Future (possible) features
- "Premier"-script
- Auto-Click-Play
- "Look-Up"

#### License

MIT

**Free Software, Hell Yeah!**
