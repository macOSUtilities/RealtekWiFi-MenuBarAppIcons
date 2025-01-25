# Status Bar Icons for Realtek Wi-Fi Adapters.

By default, the icons that ship with the StatusBarApp for the Realtek Wi-Fi Adapters (the Wi-Fi menu living in your Status Bar) look very ancient and out-of-place with macOS. These icons have been taken from Apple's official SF Icons and modified to slot in cleanly with the rest of the icons.

## Installation ##

#### Script ####
To use the installation script, open a Terminal window in the project's folder by right-clicking the folder and run:\
`sh installationScript.sh`
The script will copy the icons, quit the app, and reopen it to apply the new icons.

#### Manual Installation ####

Copy the icons from the theme of your choosing and move them to:\
`/Library/Application Support/WLAN/StatusBarApp.app/Contents/Resources`

To open `StatusBarApp.app` through Finder, you can right click on it and then click `Show Package Contents`

You will need to logout so the changes can be applied!\
Or you can open a Terminal Window and run:\
`killall StatusBarApp` to kill the process. Then just regular double-click on the `.app` to reopen.

## Screenshot ##

The icons in action:

**Dark Mode**\
![](https://i.imgur.com/fzXDwxI.png)

**Light Mode**\
![](https://i.imgur.com/F4MQ2N8.png)

### Minor Inconveniences ###

The icons don't change based on the system theme.\
For now you can rerun the installation script to change the theme.\
But I will be looking for a solution to that problem that doesn't require white/black icons in the same file.

Credits for the original icons go to [Arch-0](https://github.com/Arch-0)
