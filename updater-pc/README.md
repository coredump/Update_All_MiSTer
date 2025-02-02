# MiSTer Updater script for PC (Windows and Linux)
Download [*updater-pc.zip*](https://github.com/theypsilon/Update_All_MiSTer/releases/latest/download/updater-pc.zip) and extract the contents on an **EMPTY** folder. Access the new *updater-pc* folder. On Windows execute *update_all_win.bat* or *update_all_win_db9_snac8.bat", on Linux execute *update_all_linux.sh*.

Any configuration file should be placed at *updater-pc/update_all.ini* before you execute anything. (optional)

After the updater is done, copy all the contents of that folder to your MiSTer SD card.

Next time you can execute the same script from the MiSTer SD card directly*.

Windows binaries licenses are under *licenses* directory in the zip file.
- curl https://curl.haxx.se/ ([LICENSE](https://github.com/curl/curl/blob/master/COPYING))
- Cygwin https://www.cygwin.com/ ([LICENSE](https://cygwin.com/COPYING.LIB))
- GNU tools https://www.gnu.org/ ([LICENSE](https://cygwin.com/COPYING))


*Some cards might have issues with downloading many files to it at once, so it is better to run from the SD card for incremental updates only.


# Known problems

Norton antivirus has detected threats in DLLs in a case. It is a false positive. Those DLLs and all the other files come from the standard installation of [Cygin 64](https://cygwin.com/), and are tested in many other antivirus without any notice of malware of any kind. If you use Norton, and you face this problem, you would have to disable Norton before executing the .bat files included in the zip.
