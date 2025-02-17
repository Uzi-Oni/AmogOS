# x64 Getting started
Every release contains a iso and a zip. First, find the newest release at the top of https://github.com/jostroOS/AmogOS/releases.

For installation, you can choose the fast method via iso, or use the zip for manual installation if the fast method won't work or you are using a Linux system and can't run Universal USB Installer's exe file.

## ISO live USB installation:
Download Universal USB Installer from pendrivelinux: https://www.pendrivelinux.com/universal-usb-installer-easy-as-1-2-3/. 
DO NOT use rufus or anything else because they aren't tested or guaranteed to work. 
Find "AmogOS" at the top of the "Other Distros" section in Universal USB Installer, choose your spare USB stick (recommended size is > 2GB), download & choose the .iso file in the buttom of the release and click Create.

### Manual live USB installation:
Download & extract the .zip and follow the instructions in the "Manual-Install-README.txt" file inside it to install the OS onto a spare USB stick.

### Manual hard drive installation
For those of you wanting to go the extra mile and install the OS onto their SSD/HDD instead of live booting the OS from USB, I applaud your efforts. Boot Ubuntu as a live USB on your PC of choice, then follow the [Manual Live USB](https://github.com/Amog-OS/AmogOS/blob/main/Additional_Notes/AmogOS-x64-installation-README.md#manual-installation) installation steps, but copy the files to your computer's drive instead of a USB and run the bootinst.sh script. Now, you can shutdown the Ubuntu live USB and reboot your PC. It should automatically select your system drive where you installed AmogOS as the default drive and boot it. This system will still live boot from the drive though and load the OS into RAM, but know that we are working on a more solid solution with Calamares. You can try this too: https://www.youtube.com/watch?v=oSW3xCN1_Yo.

## Post-install
- Boot it up by plugging it into a PC, and go into the BIOS to then choose your flashed boot media as the boot device.
In the boot menu, choose the "Live USB" option to boot the OS and have all your modififed files revert on reboot or the "persistance" option to have your changed files get written to the boot media and stay on reboot.  

- :warning: If the screen resolution is off, click the "Display Settings" shortcut on the desktop and change resolutions until you find one that works for you. Also note that if the dock looks like it's positioning is broken, run `plank --preferences` in the terminal and change the position to "Bottom". You can also set the alignment to "Center" and manually change the spacing with the slider.

- Connect to internet via ethernet or wifi

- Update packages with "sudo apt update && sudo apt upgrade"

- Set timezone following https://linuxize.com/post/how-to-set-or-change-timezone-in-linux/

Go wild, do what you want and make it your own!

And remember, everyone is sus... (this ascii art is so sus that it doesnt render properly)

⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⣠⣤⣤⣤⣤⣤⣶⣦⣤⣄⡀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⢀⣴⣿⡿⠛⠉⠙⠛⠛⠛⠛⠻⢿⣿⣷⣤⡀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⣼⣿⠋⠀⠀⠀⠀⠀⠀⠀⢀⣀⣀⠈⢻⣿⣿⡄⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⣸⣿⡏⠀⠀⠀⣠⣶⣾⣿⣿⣿⠿⠿⠿⢿⣿⣿⣿⣄⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⣿⣿⠁⠀⠀⢰⣿⣿⣯⠁⠀⠀⠀⠀⠀⠀⠀⠈⠙⢿⣷⡄⠀
⠀⠀⣀⣤⣴⣶⣶⣿⡟⠀⠀⠀⢸⣿⣿⣿⣆⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⣿⣷⠀
⠀⢰⣿⡟⠋⠉⣹⣿⡇⠀⠀⠀⠘⣿⣿⣿⣿⣷⣦⣤⣤⣤⣶⣶⣶⣶⣿⣿⣿⠀
⠀⢸⣿⡇⠀⠀⣿⣿⡇⠀⠀⠀⠀⠹⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡿⠃⠀
⠀⣸⣿⡇⠀⠀⣿⣿⡇⠀⠀⠀⠀⠀⠉⠻⠿⣿⣿⣿⣿⡿⠿⠿⠛⢻⣿⡇⠀⠀
⠀⣿⣿⠁⠀⠀⣿⣿⡇⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢸⣿⣧⠀⠀
⠀⣿⣿⠀⠀⠀⣿⣿⡇⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢸⣿⣿⠀⠀
⠀⣿⣿⠀⠀⠀⣿⣿⡇⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢸⣿⣿⠀⠀
⠀⢿⣿⡆⠀⠀⣿⣿⡇⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢸⣿⡇⠀⠀
⠀⠸⣿⣧⡀⠀⣿⣿⡇⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⣿⣿⠃⠀⠀
⠀⠀⠛⢿⣿⣿⣿⣿⣇⠀⠀⠀⠀⠀⣰⣿⣿⣷⣶⣶⣶⣶⠶⠀⢠⣿⣿⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⣿⣿⠀⠀⠀⠀⠀⣿⣿⡇⠀⣽⣿⡏⠁⠀⠀⢸⣿⡇⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⣿⣿⠀⠀⠀⠀⠀⣿⣿⡇⠀⢹⣿⡆⠀⠀⠀⣸⣿⠇⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⢿⣿⣦⣄⣀⣠⣴⣿⣿⠁⠀⠈⠻⣿⣿⣿⣿⡿⠏⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠈⠛⠻⠿⠿⠿⠿⠋⠁⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
