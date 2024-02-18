
Previous: [2. Extract electrical properties](extract_feature.md)

---

# 3. Batch analysis setting

<div align=center><img src="./Figures/gif_flycat.gif" alt="" style="width:1300px;height:170px;margin:0px 0px 0px -10px"></div>


This page describes how to perform the batch analysis in ElecFeX. Here you can specify the electrical properties to be measured from which sweep(s) and which spike(s) from the selected files.

**Setting.** To perform the batch analysis, you need to specify:
1. **Specify the sweep(s) and spike(s).** Type in the sweep(s) and spike(s) to measure the electrical properties. Numbers are separated by comma, and consecutive numbers can be expressed by two numbers connected by a hyphen, such as 1, 2, 5-7.
2. **Select the electrical properties.** Click the checkbox to select the electrical properties to be measured from the data file.
3. **Click the `Process the analysis for all selected files` button.** This will open a dialog to confirm your selection and settings. If confirmed, a progress bar will appear during the process. The total processing time and the number of processed files will be displayed in the progress bar. A dialog will the appear when the analysis is complete. The analysis result is arranged in a table format and displayed in the `export result` panel (see [4. Export results](tutorials/export_result.md)).

**Note.** Typically, electrophysiological experimental design aims at standardizing the protocols to facilitate comparisons between experimental batches, i.e., using same current-clamp protocols to multiple cell samples. Batch analysis is *recommended* to be performed for recordings from each protocol separately, but can also be flexible given the user’s goal of analysis, which includes: (1) if the electrical property is protocol-related, (2) if the measurement settings are appliable for all the selected sweeps/recordings. 

One example of protocol-related electrical properties is “input resistance”. It specifies the protocol to have $\geq 2$ hyperpolarizing step-current ssweeps for a linear fitting of I-V curve. During the batch analysis, recordings that don’t meet the above requirements will not collapse the analysis process, but only have their measured values assigned as “NaN”. On the other hand, the measurements on protocol-unrelated electrical properties, such as “spike number”, are independent from sweep to sweep and don’t necessarily require each sweep to match across the recordings. However, if the parameter settings, e.g.  those for spike detection, differ from recordings to recordings, it is recommended to separate them into different batch analysis sessions. 

Settings in batch analysis, such as “sweep#” and “spike#”, also don’t require matched sweeps for all the recordings. The “sweep#” and “spike#” specifies the maximal number of sweeps and spikes to be measured; recordings of less sweep/spike will have the measurements of these “missing” sweep/spike assigned as “NaN”.


<div align='center'><img style="width:90%;margin:0px 20px 20px 20px" src="./Figures/method_BatchAnalysis_edit.gif"></div>

---

Next: [4. Export results](export_result.md)

