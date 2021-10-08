# gnome4k

gnome4k is a repository containing workarounds necessary to run gnome on 4k monitors without scaling.


## Gnome Shell

The file gnome-shell.css makes the following elements bigger:

- top bar font size
- mini calendar days font size
- wiifi networks font size

To install it:
- create the gnome-shell directory:

    ``` mkdir -p ~/.themes/<desired theme name>/gnome-shell ```
- copy gnome-shell.css in the gnome-shell directory
- go to the extension management app
- enable "User Themes"
- click the setting cog of "User Themes"
- choose the newly created theme

## Firefox

In the address bar, type "about:config"

In search type: pixels

Look for this line: layout.css.devPixelsPerPx

Double left click on that line to open the 'Enter string Value' box so you can edit the Value.

The default value will be -1.0

Enter a new number eg: 1.25 or 1.5 or 2.0 or 2.2


## Thunderbird

Menu app icon > Options > General

Scroll down to the very bottom

click 'Config Editor' button to open 'about:config' 

In search type: pixels

Look for this line: layout.css.devPixelsPerPx

Double left click on that line to open the 'Enter string Value' box so you can edit the Value. 

The default value will be -1.0

Enter a new number eg: 1.25 or 1.5 or 2.0 or 2.2

click OK 

## Goland


