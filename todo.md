# TODO 
- Fix SHIFT+CMD+A conflict on PHPStorm and macOs
- ~jump to next/previous word ALT+R ALT+L in kitty~
- Review `mackup` - https://github.com/lra/mackup
- Review `restic` - https://restic.readthedocs.io/en/stable/040_backup.html


# TimeMachine App Data / Config recovery / Backups
Don't forget to deal with these Apps as well as private dotfiles (see mackup/restic above)

TIME_MACHINE_PATH=/Volumes/TimeMachine/Backups.backupdb/MacBookPro/latest/Macintosh HD - Data/Users/username

- Typora
$TIME_MACHINE_PATH/Library/Application Support/abnerworks.Typora/themes/pixyll
$TIME_MACHINE_PATH/Library/Application Support/abnerworks.Typora/themes/pixyll.css

- HostBuddy
$TIME_MACHINE_PATH/Library/Application Support/Hostbuddy

- HELO
$TIME_MACHINE_PATH/Library/Application Support/HELO

- LiveHome 3D Pro
$TIME_MACHINE_PATH/Library/Application Support/Live Home 3D Pro

- Postbox
$TIME_MACHINE_PATH/Library/Application Support/PostboxApp

- PineGrow
$TIME_MACHINE_PATH/Library/Application Support/Pinegrow

- HomeDesigner Pro 2021
$TIME_MACHINE_PATH/Library/Application Support/Home Designer Pro 2021

- Postman
$TIME_MACHINE_PATH/Library/Application Support/Postman

- Transmit - Which one ?
$TIME_MACHINE_PATH/Library/Application Support/Transmit
$TIME_MACHINE_PATH/Library/Application Support/com.panic.Transmit

- BusyCal
https://support.busymac.com/help/98887-how-do-i-migrate-from-an-old-computer-to-a-new-computer

cp -r "$TIME_MACHINE_PATH/Library/Containers/com.busymac.busycal3/Data/Library/Application Support/BusyCal" "$HOME/Library/Containers/com.busymac.busycal3/Data/Library/Application Support"

$TIME_MACHINE_PATH/Library/Containers/com.busymac.busycal3/Data/Library/Application Support/BusyCal
$TIME_MACHINE_PATH/Library/Containers/com.busymac.busycal3/Data/Library/Preferences/com.busymac.busycal3.plist