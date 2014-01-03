Transparentwindows
=======================

### Extension for adding windows transparency to gnome-shell.
* support for global transparency setting
* support for per window transparency setting
* support for indicator visibility setting
* support for terminal windows auto detection and custom opacity
* support for inactive windows transparency (BETA)

### Changes
* Converted to 3.10 only due to gShell API changes.
* Added inactive windows transparency settings
* Added custom settings page
* Added simple mode, just for terminals
* You can now hide the panel indicator

#### Tested on:
* 3.10
* Will not work on anything below 3.10
* If you find any bugs please report them.

### How to use:
* select globar transparency from the menu to set transparency for all new / currently existing windows
* to set a custom transparency value to a window, select it then use the active window slider to set the required transparency.
* NOTE: windows with custom transparency will ignore global transparency settings
* to remove custom transparency value from a window, select it and click "clear active window transparency", it will reset it to the global transparency value.
* if all you need is terminal transparency, enable auto trancparency from the extenssion setting's menu.
* Terminals are detected by the window title. Gnome terminal and xterm title ussualy starts with something like user@host, kde konsole is bit different. Just change this to whatever suits your needs. (you must type in something to get this working)



### WARNING:
* This extension may break anything else that changes opacity.
* Having many transparent windows may and probably will kill your performance. You may expiriance lag while dragging windows around. It all depends on your hardware tho.
* You use this extenion at your own risk. If you have any doubts, do NOT install it.

HOW TO INSTALL:
---------------
Either:

A. https://extensions.gnome.org/extension/684/transparent-windows/

B. Grab it from here

Please note that only this git repo contains the most recent version of the addon. Due to the review process it may take a while before the updates show up on the extensions.gnome.org page.

