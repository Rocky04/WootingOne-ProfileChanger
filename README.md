# WootingOne-ProfileChanger
Changes the active profile to the given id.

## Getting Started

This project will allow you to build an modify your own Profile Changer for the Wooting One. It uses the source code from the project [wooting-rgb-sdk](https://github.com/WootingKb/wooting-rgb-sdk). If you are interested in more downloads and guides for the Wooting One check out their [developer portal](https://dev.wooting.nl).


### Prerequisites

#### Windows
[Visual studio](https://visualstudio.microsoft.com/)

### Installing
```
git clone --recurse-submodules https://github.com/Rocky04/WootingOne-ProfileChanger.git
```
Open the visual studio project file "windows\WootingOne-ProfileChanger.vcxproj" and select your target settings.

## Program Manual
```
usage: WootingOne-ProfileChanger.exe ProfileID

  ProfileID     The number for the new active profile from 0 to 3.
                   0 = digital profile
                   1 = first analog profile
                   2 = second analog profile
                   3 = third analog profile

example: WootingOne-ProfileChanger.exe 2
```

## Known Bugs
If you still press a key while the program is started this key will permanent spawn due to a bug in the firmware of the keayboard, because windows don't register the keyup event from the keyboard.

## License
This project is licensed under the Mozilla Public License Version 2.0 - see the [LICENSE](LICENSE) file for details
<hr>
<i>Created with visual studio 2017 (Community).</i>
