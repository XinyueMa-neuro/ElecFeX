<div align=center><img src="./Figures/applogo.png" alt="PVIN model synaptic current stimulation" style="width:90%;height:90%;">
</div>

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0) ![GitHub all releases](https://img.shields.io/github/downloads/XinyueMa-neuro/PVIN-model-MaEtAl2023/total) [![View XinyueMa-neuro/ElecFeX on File Exchange](https://www.mathworks.com/matlabcentral/images/matlab-file-exchange.svg)](https://www.mathworks.com/matlabcentral/fileexchange/130144-elecfex) [![OneDrive](https://img.shields.io/badge/OneDrive-white?style=for-the-badge&logo=Microsoft%20OneDrive&logoColor=0078D4)](https://mcgill-my.sharepoint.com/:f:/g/personal/xinyue_ma_mail_mcgill_ca/EhKPMQ7N5atGvc4yw9JcKGcBTYxrdA4Gc5KHxQ7JAq3j8Q?e=kVDaI1)

![GitHub followers](https://img.shields.io/github/followers/XinyueMa-neuro?style=social) ![GitHub watchers](https://img.shields.io/github/watchers/XinyueMa-neuro/ElecFeX?style=social) ![GitHub Repo stars](https://img.shields.io/github/stars/XinyueMa-neuro/ElecFeX?style=social) ![Twitter Follow](https://img.shields.io/twitter/follow/XinyueMa_neuro?style=social)


- [What is ElecFeX?](#What_is_ElecFeX?)
- [Installation](Installation/readme.md)
- [Tutorials](Tutorials/readme.md)
---

If you find ElecFeX helpful, buy the developer a cup of coffee :coffee:

[![paypal](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/donate/?business=CP7CFSMFTQP6C&no_recurring=1&item_name=If+ElecFeX+is+helpful+to+you%2C+buy+the+developer+a+cup+of+coffee%F0%9F%98%8A.&currency_code=CAD).

---

# What is ElecFeX?

ElecFeX is a MATLAB-based <u>**Elec**</u>trophysiological <u>**Fe**</u>ature e<u>**X**</u>traction toolkit for current-clamp recordings. This software was designed to analyze electrophysiological recordings in an intuitive and efficient way so as to be accessible to everyone no matter their level of expertise. This repository provides detailed instructions on the installation and usage of the toolkit.

### The ElecFeX toolkit includes the following features:

- Graphical user interface (GUI)
- Running on MATLAB or stand-alone
- No coding/programming required
- Support multiple data formats including Axon Binary File format by pClamp (ABF), Igor Binary Wave format (IBW) by igor Pro, and Neurodata Without Borders (NWB)
- Customizable methods for a wide range of electrophysiological features
- Multiple file processing 
- Formatted output for further analysis such as statistical analysis and clustering
- Interactive visualization 

### An overview of ElecFeX’s graphical user interface:

The graphical user interface (GUI) of ElecFeX is designed to be user-friendly with texts that guide the users through the workflow of feature extraction. The main GUI window encompasses all the essential elements required for the analysis process, and there is a callable window for advanced settings for the measurements on spike properties. 

The main window of GUI is organized in accordance with the analysis procedures and is divided into four sections including (1) import and select data file(s), (2) extract electrophysiological properties, (3) Process selcted data file(s) (batch analysis), and (4) export data analysis results. Detailed instructions regarding installation and implementation of the toolkit can be found at the [Tutorials](Tutorials/readme.md) page.

<div align=center><img src="./Figures/Figure2_Layout.png" alt="GUI" style="width:100%;height:100%;"></div>


### A summary of customizable methods for six categories of electrophysiological features:

ElecFeX provides a collection of methods to extract commonly studied electrophysiological features. These methods are equipped with customizable parameters (indicated as white box texts in the figure below), allowing for flexibility in processing signals with various waveforms. For a detailed definition on each electrical properties, see the [Tutorial](Tutorials/extract_feature.md) page and also the Methods section in the [preprint](https://www.biorxiv.org/content/10.1101/2023.05.27.542584v1).

<div align=center><img src="./Figures/Figure3_Method.png" alt="GUI" style="width:100%;height:100%;"></div>


### Credit

If you use ElecFeX, please cite the following publication:

>Ma, Xinyue, et al. "ElecFeX: A user-friendly and efficient toolkit for feature extraction from electrophysiological data" *bioRxiv* (2023): 2023-05. doi: https://www.biorxiv.org/content/10.1101/2023.05.27.542584v1

In the paper, you can find a neuroscientist-oriented introduction of the toolbox and some examples of using ElecFeX to identify neuronal subgroups from the datasets across different nervous systems, across species, and the large datasets from the [Allen Cell Types Database](https://doi.org/10.48324/dandi.000020/0.210913.1639).

The current version of ElecFeX GUI is not perfect and we’ll keep updating it. We encourage everyone who found this GUI is right for you or even interest to contribute to this tool, to provide your feedback in our GitHub page and help the development of ElecFeX.


---
Author: Xinyue Ma <br>
Email: xinyue.ma@mail.mcgill.ca <br>
Integrated Program in Neuroscience <br>
McGill University <br>
Montreal, QC, H3A 1A1 <br>
Canada <br>

Special thanks to [Anmar Khadra’s lab](https://www.medicine.mcgill.ca/physio/khadralab/) and [Reza Sharif-Naeini’s lab](https://www.shariflab.org/) for testing the toolkit and providing valuable suggestions.

Logo: Xinyue Ma, 2023

----
