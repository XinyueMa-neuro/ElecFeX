# 1. Import and select data files

Importing your data is the first step to get started with ElecFeX. This tutorial guides you through importing single-cell electrophysiological data files, including **Axon Binary File (ABF)**, **Igor Binary Wave (IBW)**, and **Neurodata Without Borders (NWB)**.

1.  **Select file directory that contains all your data files.** Click “Select folder” button and it opens a dialog for directory selection. The selected directory will be displayed in the “Current dir” textbox. You can also type in the directory into the “Current dir” textbox directly.
2. **File display.** After the directory selection, all the .abf, .ibw, and .nwb files in the folders and the subfolders of the selected directory will be listed in the large textbox below.
3. **File selection.** Select the files by clicking their checkboxes. This step is to specify files that will undergo the same analysis procedures. For instance, you can select all the data files obtained by the same current protocol, same experimental condition, and/or to measure their time series of the spike train.
4. **Save selection.** Once all files are selected, you can save your selection, so that you reload the selected “pile” of files in the future. To save your file selection, name your selection pile by typing in the “Pile label” textbox. Click “Save pile“ button and it opens a dialog for you to specify the save directory and this will create a “.mat” file.
5. **Reload the selection. **To reload the selected file piles, click “Load pile” button and select the ‘.mat’ file you created before. 