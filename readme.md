Description
------------------

Provides handy clipboard commands without keybindings.

**NOTE:** [Sublime Text 3+](http://www.sublimetext.com/) Package. Install via an updated version of  [Package Control 2+](https://sublime.wbond.net/installation).

Installation
------------------

1. Shift-CMD-P / Shift-CTRL-P and then select "Package Control: Add Repository"

2. Paste the GitHub address for the package:  `https://github.com/mkormendy/ClipboardCommands`

3. Now install the package by pressing Shift-CMD-P / Shift-CTRL-P again and select "Package Control: Install Package"

4. You should see ClipboardCommands listed, select it and it will be installed.

5. To assign a new keybinding open ".../Packages/User/Default.sublime-keymap" 
6.  Append there, for example for the paste as plain text command:

```
, { "keys": ["ctrl+alt+v"], "command": "clipboard_commands_paste_plain_text" }
```

To find all of the different commands you can use, see the list in this repository's `Commands.sublime-commands` file.


Source-code
------------------

https://github.com/mkormendy/ClipboardCommands