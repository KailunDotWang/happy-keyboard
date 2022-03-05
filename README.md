# Happy Keyboard

Happy Keyboard is so happy.

Create on 2022/03/03 20:09:57 by [Kailun.Wang](https://kailun.wang).

Power by AutoHotkey v1.1.33.10.


## Caps Lock

|     Key      |      Map       |     Command     |        Script         | When  |   Source    | Shortcuts |
| :----------: | :------------: | :-------------: | :-------------------: | :---: | :---------: | :-------: |
|   CapsLock   |     LCtrl      |                 |    CapsLock::LCtrl    | Held  |    HHKB     |           |
| CapsLock + y | Shift + Insert |      Paste      | CapsLock & y::+Insert |       |    Emacs    |           |
| CapsLock + u |                |                 |                       |       |             |           |
| CapsLock + i |   LCtrl + i    | Trigger Suggest |   CapsLock & i::^i    |       |   VS Code   |           |
| CapsLock + o |                |                 |                       |       |             |           |
| CapsLock + p |       Up       |  Previous line  |   CapsLock & p::^p    |       |    Emacs    | LCtrl + p |
| CapsLock + h |   Backspace    |    Backspace    |    CapsLock & h::^    |       |    Emacs    | LCtrl + h |
| CapsLock + j |                |                 |                       |       |             |           |
| CapsLock + k |                |                 |                       |       |             |           |
| CapsLock + l |                |                 |                       |       |             |           |
| CapsLock + k |                |                 |                       |       |             |           |
| CapsLock + n |      Down      |    Next line    |   CapsLock & n::^n    |       |    Emacs    | LCtrl + n |
| CapsLock + m |                |                 |                       |       |             |           |
| CapsLock + \ |       \        |  \ or      \|   |    CapsLock & \::\    |       | Kailun.Wang |           |


## Enter

|    Key    |    Map    |   Command   |            Script             |     When     |   Source    | Shortcuts |
| :-------: | :-------: | :---------: | :---------------------------: | :----------: | :---------: | :-------: |
|   Enter   |   Enter   |             |  Enter::KeyWait,Enter,T0.156  | Single Click |             |           |
|   Enter   |   RCtrl   |             | Enter::SendInput {RCtrl down} |     Held     | Kailun.Wang |           |
| Enter + s | RCtrl + s |    Save     |                               |              |             |           |
| Enter + b | RCtrl + b | Left arrow  |        Enter & b::Left        |              |    Emacs    |           |
| Enter + f | RCtrl + f | Right arrow |        Enter & f::Left        |              |    Emacs    |           |


## Backspace

|    Key    |         Map          | Command | Script | When  | Source | Shortcuts |
| :-------: | :------------------: | :-----: | :----: | :---: | :----: | :-------: |
| Backspace | \` | | Backspace::\` |         |  HHKB  |       |


## Slash

|  Key  |   Map    | Command |    Script    | When  | Source | Shortcuts |
| :---: | :------: | :-----: | :----------: | :---: | :----: | :-------: |
|   \   | Backspce |         | \::Backspace |       |  HHKB  |           |


## Back Quote

|        Key         |  Map  | Command | Script | When  | Source | Shortcuts |
| :----------------: | :---: | :-----: | :----: | :---: | :----: | :-------: |
| ` | Esc | |\`::Esc |       |  HHKB   |        |


## Alt

|   Key    |     Map      | Command |   Script    | When  | Source | Shortcuts |
| :------: | :----------: | :-----: | :---------: | :---: | :----: | :-------: |
| LAlt + b | Ctrl + Left  |         | >!b::^Left  |       | Emacs  |           |
| LAlt + f | Ctrl + Right |         | >!f::^Right |       | Emacs  |           |
