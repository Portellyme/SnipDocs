# Windows Updates - Uninstall

## Simple Uninstall
To uninstall an update, open an Elevated Command Prompt (admin) and then type the following command after replacing the KB ID with the one that you wish to uninstall: **wusa /uninstall /kb:[id]**

**Example:** wusa /uninstall /KB:4023057
![Simple UnInstall](images/Uninstall_update_01.jpg)
<hr>

## Quiet Uninstall
If you want to uninstall the update without your interaction and automatically restart the computer, you would use the following command: **wusa /uninstall /kb:[id] /quiet**

**Example:** wusa /uninstall /KB:4023057 /quiet
![Quiet UnInstall](images/Uninstall_update_02.jpg)
<hr>

## Prompt Restart
If you want to uninstall the update and prompt to restart the computer, use the following command: **wusa /uninstall /kb:[id] /quiet /promptrestart**

**Example:** wusa /uninstall /KB:4023057 /quiet /promptrestart
![Promp Restart UnInstall](images/Uninstall_update_03.jpg)
<hr>

## No Restart
If you want to uninstall the update without a forced system reboot, use the following command: **wusa /uninstall /kb:[id] /quiet /norestart**

**Example:** wusa /uninstall /KB:4023057 /quiet /norestart
![Promp Restart UnInstall](images/Uninstall_update_04.jpg)
<hr>

## Force Restart
If you want to uninstall the update and force system reboot, use the following command: wusa /uninstall /kb:[id] /quiet /forcerestart

**Example:** wusa /uninstall /KB:4023057 /quiet /forcerestart
![Promp Restart UnInstall](images/Uninstall_update_05.jpg)
<hr>

### Source :
[Bleeping Computer - Uninstall Windows Updates - 2019/08/05](https://www.bleepingcomputer.com/news/microsoft/how-to-uninstall-windows-10-updates-manually/)
