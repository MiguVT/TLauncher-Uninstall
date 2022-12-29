# Uninstall TLauncher
This method to uninstall TLauncher has not been proven for sure, but today it is the one with the best chance of removing the virus. To make this tutorial we have based ourselves on all the information we obtained through various analyzes in Triage, AnyRun, FileScan and VirusTotal, and we have analyzed both the installer (original binary) and the binary that is downloaded to you.

## Steps for uninstall TLauncher
To uninstall tlauncher, we will use the [Revo Uninstaller software](https://download.revouninstaller.com/download/revosetup.exe) ([click here for download portable version](https://download.revouninstaller.com/download/RevoUninstaller_Portable.zip)), which is a free uninstaller that allows you to uninstall programs and remove all the files that are left behind. To do this, we will follow the following steps:
1. Type in the search bar TLauncher
2. Right click and click "Uninstall"
3. Uncheck the "Create system restore point" (Optional) and continue
4. Continue with the normal steps to uninstall TLauncher in the normal way
5. After finishing the uninstall, select advanced analysis and hit "Analyze", this may take a few minutes
6. Once the analysis is finished, Click the "Select all" button to delete all the firewall modifications and click "Delete", this will delete all firewall rules made by tlaucnher
7. Do the same but for files and directories and click "Delete", this will delete all the files and directories that are left behind, it can delete the files of .minecraft, so be careful
8. Press Win + r and type "appdata" and press enter, this will open the appdata directory
9. Go to LocalLow and delete the file Oracle (This will delete java, reinstall if you want to use it again)
10. It uses MalwareBytes to scan for viruses and removes all viruses it finds (Optional but recommended)
11. Restart your computer and you will have successfully uninstalled TLauncher.

## Recommended launchers

There are many minecraft launchers, but here we will give you a list of the most recommended and we are 100% sure that they do not have viruses and its open source!

* [MultiMC](https://multimc.org/#Download)
* [GDLauncher](https://gdevs.io/)
* [Minecraft Launcher](https://www.minecraft.net/en-us/download/alternative) (Recommended, you need a minecraft account but its the official launcher)
* [TLauncher Legacy](https://tlaun.ch/) (Recommended and its open source)

## 💖 Contributors
* [**Migu**](https://github.com/migu-star) - *repository creator*
* [**s4vitar**](https://github.com/s4vitar) - *Analysis of the original binary and the one that is downloaded, the analyzes were made for the community but we use it as a reference for this repository.*

## 💤 For the future...
* We will continue to analyze the TLauncher and we will update this repository with the new information we find.
* We will make an uninstaller, probably in python or javascript, to make uninstalling easier.
