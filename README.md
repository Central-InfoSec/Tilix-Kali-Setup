# Tilix Kali Setup

Tilix Kali Setup is a penetration testing and red teaming script that installs and customizes Tilix on Kali Linux 2020+.

## Main Features

 - Dark theme is set
 - Background color is set to black
 - Foreground (text) color is set to green
 - Tabs are used for sessions
 - Session tabs are positioned on the bottom
 - Title style is set to small to save space
 - Terminal title will show when single
 - Other windows are not allowed on top of Tilix quake
 - Text is copied on select
 - A custom script toggles between quake window heights
 - A custom script toggles between background transparency
 - A custom script displays the keyboard shortcuts

## Installation

Clone the GitHub repository and run the script
```
sudo git clone https://github.com/Central-InfoSec/Tilix-Kali-Setup /opt/Central-InfoSec/Tilix-Kali-Setup
```

## Usage

Run the following commands to install:
```
sudo chmod +x /opt/Central-InfoSec/Tilix-Kali-Setup/tilix-kali-setup.sh
sudo -E bash /opt/Central-InfoSec/Tilix-Kali-Setup/tilix-kali-setup.sh kali
```

## Custom Commands

### Change Quake Window Height (Tilix Size)

Toggle between 30% and 70% quake window height when no parameters are passed in or to size given between 0-100
```
ts
ts 50
```

### Change Background Transparency (Tilix Transparency)

Toggle between 0% and 25% transparency when no parameters are passed in or to transparency given between 0-100
```
tt
tt 50
```

### Display Keyboard Shortcuts (Tilix Help)

Print the Tilix keyboard shortcuts
```
th
```

## Keyboard Shortcuts

### Application

Show/Hide Tilix quake mode
```
Alt + q
```

New Tilix window
```
Alt + t
```

Show keyboard shortcuts
```
Alt + z
```

Add new window
```
Alt + w
```

### Session

Add new session
```
Alt + s
```

Rename session
```
Alt + r
```

Switch to left session
```
Alt + j
```

Switch to right session
```
Alt + k
```

Move session to left
```
Shift + Alt + j
```

Move session to right
```
Shift + Alt + k
```

Fullscreen session
```
Alt + f
```

Save current session
```
Ctrl + Alt + s
```

Open saved session
```
Ctrl + Alt + o
```

Exit current session
```
Ctrl + Alt + e
```

### Terminal

Add new terminal right
```
Alt + n
```

Add new terminal down
```
Alt + d
```

Rename terminal
```
Shift + Alt + r
```

Switch to left terminal
```
Alt + h
```

Switch to right terminal
```
Alt + u
```

Switch to terminal by direction
```
Alt + Up
Alt + Down
Alt + Left
Alt + Right
```

Switch to terminal by number 1-9
```
Alt + 1
Alt + 2
...
Alt + 9
```

Resize terminal
```
Shift + Alt + Up
Shift + Alt + Down
Shift + Alt + Left
Shift + Alt + Right
```

Zoom in
```
Ctrl + =
```

Zoom out
```
Ctrl + -
```

Zoom normal
```
Ctrl + 0
```

Maximize terminal
```
Alt + m
```

Scroll up
```
Shift + Up
```

Scroll down
```
Shift + Down
```

Page up
```
Shift + Page_Up
```

Page down
```
Shift + Page_Down
```

Find text
```
Ctrl + f
```

Find next
```
Ctrl + g
```

Find previous
```
Ctrl + h
```

Copy text (text is already copied on select)
```
Alt + c
```

Paste text
```
Alt + v
```

Save terminal contents
```
Ctrl + s
```

Exit terminal
```
Alt + e
```

### Nautilus

Open file browser
```
Shift + Alt + o
```

Open in Tilix
```
Shift + Alt + t
```