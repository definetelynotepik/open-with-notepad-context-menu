# open-with-notepad-context-menu
Registry change to add "Open with notepad..." to your Windows Explorer context menu.

# What it adds
Adds "notepadopen" key to HKCR\*\shell
<br>
Adds "command" to HKCR\*\shell\notepadopen

# Values
notepadopen:
<br>
Default: Open with notepad...
<br>
Icon: C:\Windows\system32\notepad.exe
<br>
notepadopen\command:
<br>
Default: "C:\Windows\system32\notepad.exe" "%1"
