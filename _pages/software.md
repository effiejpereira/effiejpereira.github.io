---
layout: archive
title: "Software"
permalink: /software/
author_profile: true
---

As an avid programmer, I've used my technical skills to formally collaborate on industry projects and to personally create open-source platforms and GUIs for the collection and processing of synchronous big data (e.g., behavioural, mouse tracking, eye tracking, and electrophysiological signals). Formal collaborative work can be found through the industry contacts listed below, and all personal projects are freely available for download by reaching me at effie.pereira[at]uwaterloo.ca.
{: .notice}


## Industry Collaborations
------

### Co-registration of Eyetracking & EEG systems for the measurement of fixation- and saccade-related brain activity.
**Pereira, E. J.** (2019). _EyeLink-Biosemi EEG software integration, Experiment Builder v.2.2.1. Development & Testing_; SR Research.
[link](https://www.sr-research.com/eyelink-biosemi-integration/)

### Visualization & manipulation of synchronous ordinal or categorical time series data.
**Pereira, E. J.** (2015). _GridWare State Space Grids macro software design, Macro Catalogue v.2. Programming_; Queen's University Adolescent Dynamics Laboratory.
[link](http://statespacegrids.org/)


## Software Platforms
------

### <ins>TESSA (Temporal Experience Sampling Smartphone Application)</ins>
`Programming Language:` Java, Swift

TESSA is a temporal experience sampling smartphone application that can be used for data collection outside of the laboratory. I've built TESSA to contain pre-built survey and task templates while also accepting customized Java and Swift scripting to create easy and simple experience sampling study designs.

![internal](/images/software_TESSA.jpg)


### <ins>VICTOR (Video Teleconferencing Platform)</ins>
`Programming Language:` Javascript

VICTOR is a video teleconferencing platform that has similar functionality to Zoom and Teams, while providing full experimental control during collaborative dyad or group activities. VICTOR supports up to four participants at a time and any task that can be coded on Javascript can be integrated into the platform.

![internal](/images/software_VICTOR.gif){:width="600px"}


### <ins>MECO (Message Communication Platform)</ins>
`Programming Language:` Javascript

MECO is a message communication platform that allows you to simulate chat conversations during online lectures. The conversations can be hard-coded and time-stamped, but my colleagues and I have been using natural language processing to create AI-powered chatbots that can build these conversations dynamically.

![internal](/images/software_MECO.gif){:width="600px"}


## Software GUIs
------

### <ins>DAMARIS (Dynamics in Attentional & Mind Wandering States)</ins>
`Programming Language:` R, Shiny

DAMARIS leverages recurrence quantification analysis from the physiological and economic sciences (Zbilut & Webber Jr., 1992; Webber Jr. & Zbilut, 1994) to analyze nonlinear patterns in data over time. Within my work, I have been compiling ways that we can use these methods across cognitive domains, and DAMARIS represents these analyses in attentional and mind wandering time series data. DAMARIS can currently:
* Assess whether attentional time series have repetive or predictable patterns over time using auto-correlations, cross-correlations, and recurrence metrics.
* Quantify the underlying structure of attentional time series via determinism, dispersion, entropy, and trend analyses.
* Predict future states of attention based on prior time series data using algorithmic clustering and markov chains.

DAMARIS currently works with .txt and .xls data files. Its GUI is currently being rebuilt on Shiny so that the application can be deployed more broadly, so look for the new version towards the beginning of the new year.


### <ins>EEGAN (Experimental & EEG Analyses)</ins>
`Programming Language:` MATLAB

EEGAN adds an additional layer of processing power to EEGlab by synchronously linking and concurrently analyzing behavioural and EEG datasets in a structured manner. EEGAN can currently:
* Compare behavioural and EEG data files to check for missing data.
* Mark or filter trials based on behavioural and EEG criteria.
* Average behavioural and EEG experimental conditions.
* Plot EEG components across participants or conditions.
* Find peak EEG activity within time windows and flag this within behavioural data.

![internal](/images/software_EEGAN.jpg)

EEGAN currently works with BioSemi and EGI data files, though if functionality is needed for other EEG systems, this could easily be accommodated. Although having a knowledge of EEGlab prior to using EEGAN is recommended, the documented 'Help' file should cover all aspects of data analyses.


### <ins>FELIX (Fixation Listing Compiler)</ins>
`Programming Language:` MATLAB, Python

FELIX provides quick and easy functionality to compile behavioural and eye tracking datasets into one large data file. FELIX can currently:
* Select variables to carryover into the data file.
* Specify start and end tags for fixation and saccadic listings.
* Define multiple regions of interest for future analyses.

![internal](/images/software_FELIX.jpg)

FELIX currently works with EyeLink, Tobii, and SmartEye data files.


### <ins>EMMA (Eye Movement Measures Analyses)</ins>
`Programming Language:` MATLAB, Python

EMMA provides for the analyses of eye movement data across fixation, saccade, and global processing measures, and is meant to work concurrently with FELIX. EMMA can currently analyze:
* Fixation measures that look at total number of fixations, number of fixations to regions of interest, and number of fixations within regions of interest.
* Saccadic measures that process total saccadic path, angle of initial saccade, initial saccade length, saccadic path into regions of interest, and saccadic path within regions of interest.
* Global processing measures that summarize time to first fixation, time to first fixation on regions of interest, time of first fixation on regions of interest, average time spent within regions of interest, and total time in regions of interest.

EMMA currently works with .txt data files from FELIX. Its GUI is currently being revamped for a more functional layout, so look for the new version over the next few months.