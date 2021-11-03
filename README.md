# gnome4k

gnome4k is a repository containing workarounds necessary to run gnome on 4k monitors without scaling.

## Gnome UI Fonts
Install gnome-tweaks, open it, go to "Fonts" and increase accordingly (probably something around 18)

## Pointer Size
Open Gnome settings/Accessibility/Cursor Size and change to desired size

## Pointer Acceleration
Open Gnome settings/Mouse & Touchpad/Mouse speed and change to desired acceleration

## Gnome Shell

The file gnome-shell.css makes the following elements bigger:

- top bar font size
- mini calendar days font size
- wifi networks font size

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

Double left-click on that line to open the 'Enter string Value' box so you can edit the Value.

The default value will be -1.0

Enter a new number eg: 1.25 or 1.5 or 2.0 or 2.2


## Thunderbird

Menu app icon > Options > General

Scroll down to the very bottom

click 'Config Editor' button to open 'about:config' 

In search type: pixels

Look for this line: layout.css.devPixelsPerPx

Double left-click on that line to open the 'Enter string Value' box, so you can edit the Value. 

The default value will be -1.0

Enter a new number eg: 1.25 or 1.5 or 2.0 or 2.2

click OK 

## Goland
- Select Help/Edit Custom VM options
- insert this line:
  ```-Dsun.java2d.uiScale=2```
- restart the IDE
- Select File/Setting/Appearance and Behavior/Appearance/Use Custom Font and enter a value around 15


## Tradingview desktop app
- Type \<ctrl>+ to increase the view size. 

## Slack desktop app
Click your workspace name in the top left. Choose Preferences. Click Accessibility. Select your zoom level.

