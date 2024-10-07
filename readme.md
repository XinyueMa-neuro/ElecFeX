<div align=center><img src="./Figures/applogo.png" alt="applogo" style="width:90%;height:90%;">
</div>

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0) ![GitHub all releases](https://img.shields.io/github/downloads/XinyueMa-neuro/ElecFeX/total) [![View XinyueMa-neuro/ElecFeX on File Exchange](https://www.mathworks.com/matlabcentral/images/matlab-file-exchange.svg)](https://www.mathworks.com/matlabcentral/fileexchange/171844-elecfex) [![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=XinyueMa-neuro/ElecFeX)

![GitHub followers](https://img.shields.io/github/followers/XinyueMa-neuro?style=social) ![GitHub watchers](https://img.shields.io/github/watchers/XinyueMa-neuro/ElecFeX?style=social) ![GitHub Repo stars](https://img.shields.io/github/stars/XinyueMa-neuro/ElecFeX?style=social) ![Twitter Follow](https://img.shields.io/twitter/follow/XinyueMa_neuro?style=social)


- [What is ElecFeX?](#What_is_ElecFeX?)
- [Installation](Installation/readme.md)
- [Tutorials](Tutorials/readme.md)

---

The current version of ElecFeX GUI is not perfect and we’ll keep updating it. If you're intersted in contributing, please contact Xinyue Ma (xinyue.ma.neuro@gmail.com) or submit a pull request on github.

If you find ElecFeX helpful, buy me a coffee :coffee: at

[![paypal](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/donate/?business=CP7CFSMFTQP6C&no_recurring=1&item_name=If+ElecFeX+is+helpful+to+you%2C+buy+the+developer+a+cup+of+coffee%F0%9F%98%8A.&currency_code=CAD).

---
# What is ElecFeX?

ElecFeX is a MATLAB-based <u>**Elec**</u>trophysiological <u>**Fe**</u>ature e<u>**X**</u>traction toolbox for single-cell intracellular recordings. This software was designed to analyze your recordings in an intuitive and efficient way so as to be accessible to everyone no matter their level of expertise in coding. This repository provides detailed instructions on the installation and usage of the toolbox.


### ElecFeX is featured by:

- Graphical user interface (GUI)
- Running on MATLAB or stand-alone
- No coding/programming required
- Support multiple data formats: Axon Binary File (ABF) by pClamp, Igor Binary Wave format (IBW) by Igor Pro, and Neurodata Without Borders (NWB)
- Customizable methods for a wide range of commen electrophysiological features
- Interactive visualization 
- Multiple file processing (batch analysis)
- Formatted output for further analysis such as statistical analysis and clustering

### Overview of ElecFeX’s graphical user interface:

The graphical user interface (GUI) of ElecFeX is designed to be user-friendly with texts that guide the user through the feature extraction workflow. The main GUI window encompasses all the essential elements required for the analysis process, and callable windows for advanced settings related to loading NWB data and customizing spike property measurements. It is organized in accordance with the analysis procedures and is divided into six sections including (1) load file, (2) data info, (3) feature extraction, (4) visualization, (5) batch analysis setting, and (6) export results. 

Details regarding [installation](Installation/readme.md) and [tutorials](Tutorials/readme.md) are provided.

<div align=center><img src="./Figures/Figure2_Layout.png" alt="GUI" style="width:100%;height:100%;"></div>


### Customizable methods for seven categories of electrophysiological features:

ElecFeX provides a collection of methods to extract commonly studied electrophysiological features. These methods are customizable by parameters in white boxes and their outputs are displayed in gray boxes. See [Tutorial-Extract electrophysiological properties](Tutorials/extract_feature.md) for detailed definitions on these electrical properties.

<div align=center><img src="./Figures/Figure3_Method.png" alt="GUI" style="width:100%;height:100%;"></div>


### Credit

If you use ElecFeX, please cite the following publication:

>Ma, Xinyue, et al. "ElecFeX: A user-friendly and efficient toolkit for feature extraction from electrophysiological data" *bioRxiv* (2023): 2023-05. doi: https://www.biorxiv.org/content/10.1101/2023.05.27.542584v1

In the paper, you can find a neuroscientist-oriented introduction of the toolbox and three examples of using ElecFeX to identify neuronal subgroups from the datasets across different brain regions, across species, and of large size from the [Allen Cell Types Database](https://doi.org/10.48324/dandi.000020/0.210913.1639).

To cite the library in general, you could use this BibTeX entry:

```bibtex
@misc{ElecFeX,
  title = {ElecFeX: A user-friendly toolkit for efficient feature extraction from single-cell electrophysiological recordings},
  author = {Xinyue Ma},
  note = {https://github.com/XinyueMa-neuro/ElecFeX},
  year = {2023},
}
```

---
<p>
Author: Xinyue Ma <br>
Email: xinyue.ma.neuro@gmail.com <br>
Integrated Program in Neuroscience <br>
McGill University <br>
Montreal, QC, H3A 1A1 <br> 
Canada <br>
</p>


Special thanks to [Anmar Khadra’s lab](https://www.medicine.mcgill.ca/physio/khadralab/) and [Reza Sharif-Naeini’s lab](https://www.shariflab.org/) for testing the toolbox and providing valuable suggestions.

Logo: Xinyue Ma, 2023

----
