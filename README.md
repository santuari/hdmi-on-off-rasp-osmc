#Force HDMI sleep in KODI/XMBC (Raspberry)

1. Install [XBMC callbacks](http://kodi.wiki/view/Add-on:Kodi_Callbacks) add-on.
2. Navigate to the XBMC callbacks add-on (Settings -> Addons -> Services) and open the configuration:
	- create task 1: type script, browse to the "screen-off.sh", flag execute in shell and wait for script to complete
	- create a task 2: type script, browse to the "screen-on.sh", flag execute in shell and wait for script to complete
    - then create two events: one using the task 1 when screensaver is activated and the other using task 2 when the screen saver is deactivated
3. To reactivate the HDMI click a key on a keyboard or on a mouse or on KODI remote the application.
