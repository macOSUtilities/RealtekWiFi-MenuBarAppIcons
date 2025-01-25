# Menu Bar Icons for Realtek Wi-Fi Adapters.

By default, the icons that ship with the StatusBarApp for the Realtek Wi-Fi Adapters (the Wi-Fi menu living in your Menu Bar) look very ancient and out-of-place with macOS. These icons have been taken from Apple's official SF Icons and modified to slot in cleanly with the rest of the icons.

## Installation ##

#### Easy-Install ####
To use the quick-install script, follow these steps:
1. Download and open the [latest DMG from Releases.](https://github.com/macOSUtilities/RealtekWiFi-MenuBarAppIcons/releases/download/v2.0/Package_v1.0_macOS.dmg)
2. Double-click `install.command`
3. Follow the script instructions.
4. On some versions of macOS, you will have to hold down Option (Alt), then Contol-click (right-click), then click open.
On some Macs running Sequoia or higher, you will have to visit Privacy & Security in System Settings to allow the script.
The script will let you pick which mode, then copy the icons, quit the app, and reopen it to apply the new icons.

#### Manual Installation ####

Download and open the latest DMG from Releases. 
Copy the icons from the theme of your choosing and move them to:\
`/Library/Application Support/WLAN/StatusBarApp.app/Contents/Resources`

To open `StatusBarApp.app` through Finder, you can right click on it and then click `Show Package Contents`

You will need to logout so the changes can be applied!\
Or you can open a Terminal Window and run:\
`killall StatusBarApp` to kill the process. Then just regular double-click on the `.app` to reopen.

## Screenshot ##

The icons in action:

**Dark Mode**\
![Screenshot of the dark mode Wi-Fi icon in the Menu Bar](https://github.com/user-attachments/assets/3707f0b0-96de-4a37-a43b-3cec562e3f24)


**Light Mode**\
![Screenshot of the light mode Wi-Fi icon in the Menu Bar](https://i.imgur.com/F4MQ2N8.png)

### Minor Inconveniences ###

The icons don't change based on the system theme.\
For now you can rerun the installation script to change the theme.\
But I will be looking for a solution to that problem that doesn't require white/black icons in the same file.

Credits for the original icons go to [Arch-0](https://github.com/Arch-0)
