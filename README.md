# LOTUS-compiled
This repository hosts the compiled versions of LOTUS software for wearable data processing. The primary repository for LOTUS can be found [here](https://github.com/jack-fogarty/LOTUS)
<br>

# The LOTUS Toolkit
The LOTUS toolkit features two GUIs built to read, compile, and analyse raw Empatica EmbracePlus data over user-defined periods of time (i.e., EDA, BVP, systolic peaks, temperature, accelerometer, and event tags).
The two GUI components include the LOTUS reader and analyser, which may be downloaded and used independently of one another.
1. **LOTUS Reader** can selectively reconstitute fragmented 'chunks' of raw  EmbracePlus data (i.e., avro files) as a continuous timeseries. Batch processing is enabled to allow users to reconstitute data across multiple subjects and multiple days.
2. **LOTUS analyser** allows users to visualise and navigate the raw signal data, edit event tags, and complete basic preprocessing.
<br>
Feedback and suggestions may be sent to: <a href="mailto:jack.fogarty@nie.edu.sg">jack.fogarty@nie.edu.sg</a>
<br>

# Citation
If using LOTUS reader or anlyser please reference:
<br>
<ul>Fogarty, J. S. (2024). LOTUS Software to Process Wearable EmbracePlus Data. Sensors, 24(23), 7462. https://doi.org/10.3390/s24237462
</ul>
<br>

# Installation of the Compiled Toolbox
Install the toolbox using the exe files from one of the folders. Note, these both install LOTUS reader, but one also installs Matlab runtime if it is required and the other does not (see below). Further details on the differences between these can be found from Mathworks at this link [here](https://www.mathworks.com/help/compiler/files-generated-after-packaging-application-compiler.html).
1. **for_redistribution folder** contains the installation file for LOTUS reader _with_ Matlab compiler runtime. Use this if you do not have Matlab or matlab runtime.
2. **for_redistribution_files_only folder** contains only the necessary installation files for LOTUS reader. Use this if you already have Matlab compiler runtime installed.

N.B. Prior to using this compiled version, you may also need to ensure that Python and Avro python library are installed as required in the [installation instructions for LOTUS in the main repository](https://github.com/jack-fogarty/LOTUS).
