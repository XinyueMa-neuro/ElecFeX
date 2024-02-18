<!-- <p style="text-align:left;">
    Previous: <a href=readme.md>Tutorials</a>
    <span style="float:right;">
        Next: <a href=extract_feature.md>2. Extract electrical properties</a>
    </span>
</p> -->

Previous: [Tutorials](readme.md)

---

# 1. Load data files

<!-- <div align=center><img src="https://media.giphy.com/media/VxbvpfaTTo3le/giphy.gif" alt="" style="width:100%;height:50%;"></div> -->

<div align=center><img src="./Figures/gif_flycat.gif" alt="" style="width:800px;height:170px"></div>

<br>

Importing your data is the first step to get started with ElecFeX. This page guides you through loading the data files, including **Axon Binary File (ABF)**, **Igor Binary Wave (IBW)**, and **Neurodata Without Borders (NWB)**, and save your settings.

<br>

1.  **Select file directory that contains all your data files.** Click `Select folder` button and it opens a dialog for directory selection. The selected directory will be displayed in the `Current dir` textbox. You can also type in the directory into the `Current dir` textbox directly.
2. **File display.** After the directory selection, all the .abf, .ibw, and .nwb files in the folders and the subfolders of the selected directory will be listed.
3. **File selection.** Select the files by clicking their checkboxes. When running the batch analysis, this step specifies files to undergo the same analysis procedures. You are recommended to select all the data files obtained by the same current protocol, same experimental condition, and/or when the parameter settings for the measurements are appliable to them all.
4. **Save selection.** Once all files are selected, you can save the selection for retrieving your selection and all the parameter settings in the future. To do so, name the session by typing in the `Pile label` textbox. Click `Save pile` button and it opens a dialog for you to specify the save directory and this will create a “.mat” file.
5. **Reload the selection.** To reload the selected file piles, click `Load pile` button and select the corresponding ‘.mat’ file. 

<img src="./Figures/Tutorial_loadFile.gif" alt="Tutorial_loadFile" style="width=100%">

---

Next: [2. Extract electrical properties](extract_feature.md)
<!--
<p style="text-align:left;">
    Previous: <a href=readme.md>Tutorials</a>
    <span style="float:right;">
        Next: <a href=extract_feature.md>2. Extract electrical properties</a>
    </span>
</p>
-->


<!-- <div align=center>
<img src="./Figures/Tutorial_loadFile.gif" alt="Tutorial_loadFile" style="position:absolute;clip:rect(1px 650px 800px 174px);left:30px"></div> -->
