# Installation

source code download:
+ [release v1.1.0](https://github.com/XinyueMa-neuro/ElecFeX/archive/refs/tags/v1.1.0.zip)

\
\
**Platform compatibility**: windows, Linux, macOS

To download the package, you can input "https://github.com/XinyueMa-neuro/ElecFeX/tree/main/Installation/AddsOn" to [Download Directory](https://download-directory.github.io/) (Credits to [fregante](https://stackoverflow.com/users/288906/fregante)) and press 'Enter'.

There are two installation options given the accessibility of a licensed MATLAB:
- [<b>Adds-on package to MATLAB</b>](#bulbto-install-elecfex-as-an-adds-on-package-into-matlab): If you have installed MATLAB, you can install ElecFeX as an adds-on toolbox into MATLAB. MATLAB R2022a is recommended as it has been tested in.

- [<b>Standalone desktop application</b>](#bulbto-install-elecfex-as-a-standalone-desktop-application): You don't need to have MATLAB installed not a Matlab licence. 

- [<b>MATLAB Online</b>](#bulbto-install-elecfex-in-matlab-online) by clicking [![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=XinyueMa-neuro/ElecFeX)
 <br>

---

## :bulb:To install ElecFeX as an adds-on package into MATLAB 

**Requirements**: MATLAB R2022a (recommended version), Signal Processing toolbox, Curve Fitting toolbox.

> Using a earlier Matlab version can lead to errors.

### :arrow_forward:Before the installation...

:grey_question:*If you don’t have MATLAB installed...* 

To install MATLAB R2022a, go to https://www.mathworks.com/downloads/, select and download release “R2022a”. Next, double-click on “setup.exe” and follow the installation steps. In the “PRODUCTS” selection window, check at least the “Signal Processing toolbox” and the “Curve Fitting toolbox”. 

:grey_question:*If you have installed MATLAB...* 

Check if the required toolboxes are installed. You can check them by:

- In the Command windows, type in *ver*, and it will display all the packages you have installed

OR

- In the Toolbar, go to “Home” panel and select “Add-ons”-“Manage Add-Ons” and it will display all the packages you have installed. 

:grey_question:*If the required toolboxes are not installed...* 

Go to “Home” panel and select “Add-ons”-“Get Add-ons” where you can search and install them.

After completing the above requirements, you can install ElecFeX as an add-on package into MATLAB.

### :arrow_forward:Installation steps

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

---

## :bulb:To install ElecFeX as a standalone desktop application

A standalone desktop application doesn’t demand a licenced MATLAB installed in your operating system. 

### :arrow_forward: Installation steps
**For Windows users:**

1. Download and double click “../Installation/Standalone/ElecFeX_Installer_web.exe” and follow the instruction to installs ElecFeX. 
2. Once installed, go to the file installed location and find “../application/ElecFeX.exe” to run the application.


**For Linux users:**

1. Download and double click “../Installation/Standalone/ElecFeX_Installer_web.exe” and follow the instruction to installs ElecFeX. 
2. In the terminal, type: `sudo -H ./ElecFeX_Installer_web.exe`
You may need to allow the root user to access the running X server:
> 
>	`xhost +SI:localuser:root`
>	
>	`sudo -H ./install`
>	
>	`xhost -SI:localuser:root`
>	
> sudo is only required if you install to a directory that you do not have write access to.


**For macOS users:**

1. Download and double click “../Installation/Standalone/ElecFeX_Installer_web.exe” and follow the instruction to installs ElecFeX. 
2. In the terminal, type `./ElecFeX_Installer_web`
You may need to enter an administrator username and password after you run `./ElecFeX_Installer_web.exe`.

---

## :bulb:To install ElecFeX in MATLAB Online

1. By clicking [![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=XinyueMa-neuro/ElecFeX), you will open this Git™ repositories directly in [MATLAB® Online™](https://www.mathworks.com/products/matlab-online/matlab-online-versions.html). MATLAB® Online™ enables you to access MATLAB in your browzer. You may need to register an MathWorks account.
2. Once in MATLAB® Online™, select the folder 'AddsOn' and double-click "ElecFeX.mlappinstall" and a installation dialog will show.
3. Once installed, open the app from the MATLAB® Online™ Toolbars “Apps”, dropdown and under ‘MY APPS’ click “ElecFeX” and the GUI will appear. 


<br><br><br>
