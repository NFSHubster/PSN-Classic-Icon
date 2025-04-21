<p align="center">
  <img src="https://media.discordapp.net/attachments/1180478475669348444/1363872158253580438/477-4776929_psn-logo-w-title-playstation-network-logo-png.png?ex=68079c6e&is=68064aee&hm=66d4bb488464695609216b4cccc183ce97800ca05c1d73c18e50a9193c2aaf59&" alt="Classic PSN Logo" width="300"/>
  <img src="https://media.discordapp.net/attachments/1180478475669348444/1363873243315966193/IMG_20250421_164356_399.jpg?ex=68079d70&is=68064bf0&hm=032d7c3d8736cfd316388ebbdc7b82ac00014e872d0da406073910187638132f&" alt="Restored on PS3" width="300"/>
</p>

# Restore the Classic PlayStation Network Logo on PS3

Bring back nostalgia by restoring the **classic PlayStation Network category icon** on your PS3's XMB. This guide helps you bring back the iconic orb-style PSN logo instead of the newer PlayStation?Network text.

> Made with love by me (NFSHubster),released before on [PSX-Place](https://www.psx-place.com/resources/how-to-restore-the-old-classic-psn-logo-on-your-ps3-a-step-by-step-guide.1432/) also by me

---

## Features

- Restores the classic PSN icon on the XMB,both in-game & on the menu
- Works on both CFW and HEN setups
- 100% safe and reversible
- Simple drag-and-drop via FTP

---

## Prerequisites

- A PS3 running Custom Firmware (CFW) or Homebrew Enabler (HEN)
- FTP access to your PS3 (via multiman or webMAN) 
- Basic familiarity with PS3 file structure

---

## Installation Steps

### Method 1: Using FTP

For those who prefer using FTP, the options below will both guide you through the process. There are two options depending on your setup and preference.


#### Option 1: Using Rebug Toolbox

1) Enable HEN (if you're using HFW): If you are using a PS3 with HEN (Homebrew Enabler), enable it first. If you are on Custom Firmware (CFW), you can skip this step.

2) Access Rebug Toolbox: Download and launch [Rebug Toolbox](https://store.brewology.com/get/homebrew.php?id=308&fid=2336) to enable the "dev_rebug" directory on your PS3.

3) Connect via FTP: Connect your PS3 to your computer using an FTP client like [FileZilla](https://download.filezilla-project.org/client/FileZilla_3.67.1_win64_sponsored2-setup.exe).
Enter your PS3?s IP address in the "Hostname" text box, then click "Quickconnect."
Navigate to the "resource" Directory: In the FTP client, navigate to dev_rebug/vsh/resource

4) Backup the Original Logo Files: Locate the following files and back them up to your computer:
xmb_ingame.rco (for the in-game XMB)
xmb_plugin_normal.rco (for the main XMB)

5) Replace with New Logo Files: Upload the new classic PSN logo files (xmb_ingame.rco and xmb_plugin_normal.rco) to the same directory, replacing the original ones.

6) Restart Your PS3: After the transfer is complete, restart your PS3 to see the changes.

#### Option 2: Enabling Writing to dev_blind

1) Enable HEN (if applicable): If you?re using HEN, enable it, or skip this step if on CFW.

2) Enable dev_blind/dev_flash: Use a tool like [webMAN MOD](https://github.com/aldostools/webMAN-MOD/releases/download/1.47.46/webMAN_MOD_1.47.46_Installer.pkg) to enable writing to dev_blind (or dev_flash). For file management, use [multiMAN](https://store.brewology.com/get/homebrew.php?id=24&fid=2412) or [File Manager Nightly v1.42](https://store.brewology.com/get/homebrew.php?id=284&fid=2395).
? webMAN MOD: Install [webMAN MOD](https://github.com/aldostools/webMAN-MOD/releases/download/1.47.46/webMAN_MOD_1.47.46_Installer.pkg) if not installed before,and use it from the XMB Game tab to enable writing to dev_blind.

3) Connect via FTP: Connect your PS3 to your computer via FTP using [FileZilla](https://download.filezilla-project.org/client/FileZilla_3.67.1_win64_sponsored2-setup.exe).
Navigate to the "resource" Directory: Go to dev_blind/vsh/resource or dev_flash/vsh/resource using the FTP client.

4) Backup the Original Logo Files: Locate and back up the following files:
xmb_ingame.rco
xmb_plugin_normal.rco

5) Replace with New Logo Files: Upload the new logo files to the vsh/resource directory, replacing the originals.

6) Restart Your PS3: Restart your PS3 to apply the changes.

### Method 2: Using a FAT32 USB Drive and Homebrew File Explorer

If you prefer not to use FTP, you can manually replace the logo files using a FAT32 USB drive and a homebrew file explorer.

1) Prepare the USB Drive: Format a USB drive to FAT32 and copy the new xmb_ingame.rco and xmb_plugin_normal.rco files to the drive.

2) Enable HEN (if applicable): Enable HEN if necessary.

3) Launch a Homebrew File Explorer: Open a homebrew file explorer on your PS3, such as [multiMAN](https://store.brewology.com/get/homebrew.php?id=24&fid=2412) or [File Manager Nightly v1.42](https://store.brewology.com/get/homebrew.php?id=284&fid=2395).
4) Navigate to the "resource" Directory: Use the file explorer to navigate to dev_blind/vsh/resource or dev_flash/vsh/resource.

5) Backup the Original Logo Files: Copy the original xmb_ingame.rco and xmb_plugin_normal.rco files to the USB drive as a backup.

6) Replace with New Logo Files: Copy the new files from the USB drive to the vsh/resource directory on your PS3, replacing the originals.

7) Restart Your PS3: After replacing the files, restart your PS3 to see the new logo.

---

## Disclaimer

1) This tutorial assumes you have basic knowledge of handling files, using homebrew applications, and navigating file directories on your PS3. If you are unfamiliar with these concepts, you may want to seek additional resources or assistance before proceeding.

2) I am not responsible if this mod causes any damage or results in your console being soft-bricked! It should be a straight forward guide and easy to apply.

---

## Credits

- Me, for creating this modification & releasing it
- Sony,for creating the PlayStation?Network Logo
- The awesome PS3 modding community for keeping the console alive
