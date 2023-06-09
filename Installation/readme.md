# Installation

**Platform compatibility**: windows, Linux, macOS

We provided two options to install ElecFeX given the accessibility of a licensed MATLAB:

- [<b>Add-on package to MATLAB</b>](
##_:bulb:_To_install_ElecFeX_as_a_standalone_desktop_application): If you have installed or have access to a licensed MATLAB in your system, you can install ElecFeX as an adds-on toolbox into MATLAB. MATLAB R2022a is recommended for the toolbox to achieve the best performance.

- [<b>Standalone desktop application</b>](##_:bulb:_To_install_ElecFeX_as_a_standalone_desktop_application): You don't need to have MATLAB installed. 

 <br>


## :bulb: To install ElecFeX as an add-on package into MATLAB

**Requirements**: MATLAB R2022a (recommended version), Signal Processing toolbox, Curve Fitting toolbox.

### Before the installation...

*If you don’t have MATLAB installed.* To install MATLAB R2022a, go to https://www.mathworks.com/downloads/, select and download release “R2022a”. Next, double-click on “setup.exe” and follow the installation steps. In the “PRODUCTS” selection window, check at least the “Signal Processing toolbox” and the “Curve Fitting toolbox”. 

*If you have installed MATLAB.* Check if the required toolboxes are installed. You can check them by:

- In the Command windows, type in *ver*, and it will display all the packages you have installed

OR

- In the Toolbar, go to “Home” panel and select “Add-ons”-“Manage Add-Ons” and it will display all the packages you have installed. 

*If the required toolboxes are not installed.* Go to “Home” panel and select “Add-ons”-“Get Add-ons” where you can search and install them.

After completing the above requirements, you can install ElecFeX as an add-on package into MATLAB.

### Installation

**For Windows users:**

1. Use the “Download ZIP” option to download the latest version from the Github page and unzip it to a local directory. 
2. Double-click on the “..\Installation\AddsOnn\ElecFeX.mlappinstall” and a dialog window will appear.
3. Click “Install” in the opened dialog window and the “ElecFeX” is installed.
4. Once installed, open the app from the MATLAB Toolbars “Apps”, dropdown and under ‘MY APPS’ click “ElecFeX” and the GUI will appear.

**For Linux and macOS users:**

1. In the MATLAB Toolbar, go to “APPS” panel and select “Install Apps”. Select the file “../Installation/AddIn/ElecFeX.mlappinstall” and a dialog window will appear. 
2. Click “Install” in the opened dialog window and the “ElecFeX” is installed.
3. Once installed, open the app from the MATLAB Toolbars “Apps”, dropdown and under ‘MY APPS’ click “ElecFeX” and the GUI will appear.

<br>

## :bulb: To install ElecFeX as a standalone desktop application

A standalone desktop application doesn’t require you to have MATLAB installed in your operating system. 

**For Windows users:**

1. Go to https://mcgill-my.sharepoint.com/:f:/g/personal/xinyue_ma_mail_mcgill_ca/EhKPMQ7N5atGvc4yw9JcKGcBTYxrdA4Gc5KHxQ7JAq3j8Q?e=kVDaI1 to download ElecFeXInstaller.exe. 
2. Double-click the file “../Installation/Standalone/ElecFeXInstaller.exe” and follow the instruction to installs ElecFeX. 
3. Once installed, go to the file installed location and find “../application/ElecFeX.exe” to run the application.


**For Linux users:**

1. Go to https://mcgill-my.sharepoint.com/:f:/g/personal/xinyue_ma_mail_mcgill_ca/EhKPMQ7N5atGvc4yw9JcKGcBTYxrdA4Gc5KHxQ7JAq3j8Q?e=kVDaI1 to download ElecFeXInstaller.exe. 
2. In the terminal, type: `sudo -H ./ElecFeXInstaller.install`
> You may need to allow the root user to access the running X server:
>	`xhost +SI:localuser:root`
>	`sudo -H ./install`
>	`xhost -SI:localuser:root`
> sudo is only required if you install to a directory that you do not have write access to.


**For macOS users:**

1. Go to https://mcgill-my.sharepoint.com/:f:/g/personal/xinyue_ma_mail_mcgill_ca/EhKPMQ7N5atGvc4yw9JcKGcBTYxrdA4Gc5KHxQ7JAq3j8Q?e=kVDaI1 to download ElecFeXInstaller.exe. 
2. In the terminal, type `./ElecFeXInstaller`
> You may need to enter an administrator username and password after you run `./ElecFeXInstaller`.

<br><br><br>
