---
layout: archive
title: "Software"
permalink: /software/
author_profile: true
---

## Industry Collaborations
------

### Co-registration of Eyetracking & EEG systems for the measurement of fixation- and saccade-related brain activity.
**Pereira, E. J.** (2019). _EyeLink-Biosemi EEG software integration, Experiment Builder v.2.2.1. Development & Testing_; SR Research.
[link](https://www.sr-research.com/eyelink-biosemi-integration/)

### Visualization & manipulation of synchronous ordinal or categorical time series data.
**Pereira, E. J.** (2015). _GridWare State Space Grids macro software design, Macro Catalogue v.2. Programming_; Queen's University Adolescent Dynamics Laboratory.
[link](http://statespacegrids.org/)


## Software Coding
------

In addition to my industry collaborations, I'm an avid programmer and I've created Python scripts and MATLAB GUIs for processing synchronous big data (e.g., behavioural data; eye tracking signals from EyeLink, Tobii, and SmartEye; electrophysiological signals from BioSemi and EGI). All available applications are listed below. To download them, send me a quick email at effie.pereira[at]uwaterloo.ca. I only ask that if you do use any of the code or applications for research purposes, an acknowledgement of the code / application would be appreciated.
{: .notice}


### <ins>DAMARIS (Dynamics in Attentional & Mind Wandering States)</ins>
DAMARIS was built off of recurrence quantification analysis (Zbilut & Webber Jr., 1992; Webber Jr. & Zbilut, 1994), which is a method of nonlinear data analysis that has been used extensively within economic forecasting to assess, quantify, and predict long-term trends over time. Within my work, I have been compiling ways that we can use these methods across cognitive domains, and DAMARIS represents these analyses in attentional and mind wandering time series data. This includes being able to:
* Assess whether attentional time series have repetive or predictable patterns over time using auto-correlations, cross-correlations, and recurrence metrics.
* Quantify the underlying structure of attentional time series via determinism, dispersion, entropy, and trend analyses.
* Predict future states of attention based on prior time series data using algorithmic clustering and markov chains.

DAMARIS mostly exists across a series of Python scripts but I am currently building a GUI on Kivy so that the application can be deployed more broadly. Look for the new version towards the beginning of the new year.



### <ins>EEGAN (Experimental & EEG Analyses)</ins>

EEGAN came together through the need to process synchronous behavioural and EEG data in a structured manner. Although EEGlab has some great functionality for electrophysiological analyses, I wanted to create an additional layer that could work concurrently with EEGlab to simplify the steps needed to link these two sets of data together. EEGAN can currently:
* Compare behavioural and EEG data files to check for missing data.
* Mark or filter trials based on behavioural and EEG criteria.
* Average behavioural and EEG experimental conditions.
* Plot EEG components across participants or conditions.
* Find peak activity within time windows and flag this within behavioural data.

![internal](/images/software_EEGAN.jpg)

EEGAN currently works with BioSemi and EGI data files, though if functionality is needed for other EEG systems, this could easily be accommodated. Although having a knowledge of EEGlab prior to using EEGAN is recommended, the documented 'Help' file should cover all aspects of data analyses.


### <ins>FELIX (Fixation Listing Compiler)</ins>

FELIX has quick and easy functionality to compile behavioural and eye tracking data into one large data file. This includes being able to:
* Select variables that you'd like to carryover into your data file.
* Specify start and end tags for fixation and saccadic listings.
* Define multiple regions of interest for analyses.

![internal](/images/software_FELIX.jpg)

FELIX currently works with EyeLink, Tobii, and SmartEye data files.


### <ins>EMMA (Eye Movement Measures Analyses)</ins>

EMMA allows for the analyses of eye movement data across fixation, saccade, and global processing measures, and EMMA can currently handle the following analyses:
* Fixation measures that look at total number of fixations, number of fixations to regions of interest, and number of fixations within regions of interest.
* Saccadic measures that process total saccadic path, angle of initial saccade, initial saccade length, saccadic path into regions of interest, and saccadic path within regions of interest.
* Global processing measures that summarize time to first fixation, time to first fixation on regions of interest, time of first fixation on regions of interest, average time spent within regions of interest, and total time in regions of interest.

EMMA is currently being revamped for a more functional GUI, so look for the new version over the next few months.