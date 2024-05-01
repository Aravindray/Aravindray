## Table of Content

- [Style Block](#style-block)
- [How to do it?](#how-to-do-it)
    - [How to login and setup in git?](#how-to-login-and-setup-in-git)
    - [How to add date \& time in command prompt or terminal in windows PC?](#how-to-add-date--time-in-command-prompt-or-terminal-in-windows-pc)
    - [How to download PC Battery Report in windows 10/11](#how-to-download-pc-battery-report-in-windows-1011)
    - [How to turn off external devices wake up PC?](#how-to-turn-off-external-devices-wake-up-pc)
    - [How to import modules from different folders in python?](#how-to-import-modules-from-different-folders-in-python)
    - [How to open MS Store using Run?](#how-to-open-ms-store-using-run)
    - [How to clear cache and temp files in windows PC?](#how-to-clear-cache-and-temp-files-in-windows-pc)
    - [How to install MySql in windows 10/11?](#how-to-install-mysql-in-windows-1011)
    - [How to create and activate virtual environment in python?](#how-to-create-and-activate-virtual-environment-in-python)
    - [What are the requirements needed to work with JavaScript in Windows PC?](#what-are-the-requirements-needed-to-work-with-javascript-in-windows-pc)

<br>

# Style Block

<style>
    red {color: Red}
    green {color: Green}
</style>

# How to do it?

### How to login and setup in git?

To add name - git config --global user.name "your_name" <br>
To add email - git config --global user.email "your_email"


### How to add date & time in command prompt or terminal in windows PC?

This 3 arrows is called prompt >>> in python or c:\Users\name> in windows terminal. For more information type **prompt /?**.

Once you decided the format we have to save it in registry editor. The format I chose is Date & Time | Path > 


### How to download PC Battery Report in windows 10/11

Open the cmd prompt as admin and type this command

```command line interface
powercfg /batteryreport /output "D:\battery_report.html"
```


### How to turn off external devices wake up PC? 

open device manager select _HID Keyboard Device & ID-compliant mouse_ go to Properties then select Power Management tab and uncheck **Allow this device to wake the computer**

### How to import modules from different folders in python?

Question: I have _person.py_ script inside the **JAN2024** folder and I have another folder called **FEB2024** which have _employee.py_ script I need to import _person.py_ script to use it as a base class of _employee.py_, how to import it in python?<br>
Note: both **JAN2024** and **FEB2024** folder are inside **Python** folder

Answer: The simplest way to add the file path in sys path for python to check the folder. In windows PC don't forget to add **\\\\** between folder hierarchy.

```python
import sys
sys.path.append('d:\\Github\\Python\\JAN2024')
from person import Person
```

### How to open MS Store using Run?

```command line interface
ms-windows-store:updates
```

### How to clear cache and temp files in windows PC?

Recursive Task for every month first day or week ҉

Step 1: Go to Local Disk (C:) > Windows > SoftwareDistribution > Download > <red>Inside Download Deleted All</red> <br>
Step 2: Open Run > %temp% > <red>Inside temp Deleted All</red> <br> Another method to open this folder is going through User Name > AppData > Local > Temp > <red>...</red> <br>
Step 3: Open Run > temp > click continue > <red>Inside temp Deleted All</red> <br> Another method to open this folder is going through This PC > Local Disk (C:) > Windows > Temp > <red>...</red> <br>
Step 4: Open Run > prefetch > click continue > <red>Inside prefetch Deleted All</red> <br> Another method to open this folder is going through This PC > Local Disk (C:) > Windows > Prefetch > <red>...</red>  <br>
Step 5: To reset windows store > Open Run > wsreset > <red>This will clear the cache for windows store</red> <br>
Step 6: Go to Edge > <red>Clear browser cache and cookies</red> <br>
Step 7: click windows key + s > type clear location history > <red>click clear</red> <br>
Step 8: Go to CMD as administrator > <red>type ```ipconfig /flushDNS```</red> <br>
Step 9: Advance --- Disk Cleanup > Select Disk > recommended to watch the video in youtube for reference

### How to install MySql in windows 10/11?

First download and install [Microsoft Visual C++ Redistributable](https://learn.microsoft.com/en-us/cpp/windows/latest-supported-vc-redist?view=msvc-170)

At this time my system is 64 bit and go to [MySql Webiste](https://dev.mysql.com/downloads/installer/)

Then download the Windows (x86, 32-bit), MSI Installer with maximum MB (the second one)

Don't need to sign in just click download without sign in.

### How to create and activate virtual environment in python?

Working of finding answers!

### What are the requirements needed to work with JavaScript in Windows PC?

Check out this article [Install NodeJS on Windows](https://learn.microsoft.com/en-us/windows/dev-environment/javascript/nodejs-on-windows)

First Download <abbr title="Node Version Manager">NVM</abbr> from [NVM For Windows](https://github.com/coreybutler/nvm-windows#installation--upgrades) click Download Now! refer the image , then select nvm-setup.exe to download and then install it.
After that open PowerShell as Admin, and check the available version with this command ```nvm list available``` and choose the LTS version you needed, then install the node js with this command ```nvm install <version>``` (replacing ```<version>``` with the **number**, ie: ```nvm install 12.14.0```). To confirm the download use this command to check the installed version number with this command ```nvm ls``` and check the 9th, 10th and 11th points from the above attached article.
