# Uninstall Mac Apps

This script is designed to provide standard users the ability to delete apps on their own, e.g. via Jamf Self Service Policy.


## Blacklist Apps
To find out the bundle identifier of an app try this:
```
/usr/libexec/PlistBuddy -c "Print CFBundleIdentifier" "/Applications/YOUR-APP.app/Contents/Info.plist"
```

Blacklisted apps will show the following to the user:

<img src="https://github.com/aduffner/uninstallMacApps/blob/main/appstore.png" width="80%">

## Screenshots of the script in action

<img src="https://github.com/aduffner/uninstallMacApps/blob/main/bbedit_choose.png" width="80%">

<img src="https://github.com/aduffner/uninstallMacApps/blob/main/bbedit_stop.png" width="80%">

<img src="https://github.com/aduffner/uninstallMacApps/blob/main/bbedit_uninstall.png" width="80%">

## Usage

...
