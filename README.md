# MXR-Traffic-Modeling
This repository stores supporting documents to showcase the medical extended reality (MXR) traffic modeling workflow and select pattern examples. Please refer to our RST on MXR traffic modeling for more details.

#### PROGRAM NAME: Medical eXtended Reality (MXR) Traffic Models

#### PROJECT: FDA 5G MXR Traffic Pattern Recognition and Modeling

The project code was prepared to accompany with the FDA OSEL Regulatory Science Tool (RST) for modeling Medical Extended Reality (MXR) traffic. Implementation examples of the developed modeling method are presented as Python code in Jupyter Notebooks.

Please refer to our papers [1][2] for more details on modeling MXR traffic patterns and utilizing these models.

#### PROGRAMMER: YONGKANG LIU (FDA/CDRH/OSEL/DBP, yongkang.liu@fda.hhs.gov)

#### License: CC0 1.0 https://creativecommons.org/publicdomain/zero/1.0/

## Software requirements to run code

The Python code was prepared using Python 3.8.5. It can be run by Python 3.8.5 or later versions.

The Python code and markdown were prepared with the Jupyter Notebook from the Anaconda3-2024.02-1 Windows distribution consisting of the following modules,

IPython          : 8.20.0  
ipykernel        : 6.28.0  
ipywidgets       : 7.6.5 
jupyter_client   : 8.6.0  
jupyter_core     : 5.5.0  
jupyter_server   : 2.10.0   
jupyterlab       : 4.0.11  
nbclient         : 0.8.0  
nbconvert        : 7.10.0  
nbformat         : 5.9.2  
notebook         : 7.0.8  
qtconsole        : 5.4.2  
traitlets        : 5.7.1  


## File directory
/model_summary
- mxr_pcap_models_20240628.ipynb (summary of downlink/uplink traffic patterns in the MXR modeling examples)
   
/RFH  
- ana_pcap_MXR_rfh_ds_ver_1.0.0.ipynb (workflow showcase for modeling downlink traffic in the MXR RFH use case)
- ana_pcap_MXR_rfh_us_ver_1.0.0.ipynb (workflow showcase for modeling uplink traffic in the MXR RFH use case)

## Running the Jupyter Notebook
1. Clone the repo to your local computer.
2. Download the RFH link traffic raw data (in CSV files) from FDA Regulatory Science Tool (RST) Catalog (link here).
    1. Open the link and download the files.
    2. Change the file extension from .txt to .csv from removing ".txt" from the full file name.
    3. Save the files in the /RFH folder.
4. Open a notebook file (*.ipynb shown in the file directory) on your Jupyter Notebook editor (e.g., in Anaconda).
5. Run the cells from top to down for a study.

#### Tips on using Jupyter Notebook.
1. The notebook is organized by a sequence of program blocks (called as Cells). Each cell can host either Python code or markdown with plain text or html-style content.
2.	Each cell can be executed independently or in a batch (Menu Run -> Run all cells). Ctrl+Enter (run the current, single block of code) and Shift+Enter (run the current block and move to the next one) are the most used cell run shortcut commands. 
3.	The global variables and functions defined in a cell are visible to the other cells run afterward. Therefore, it is suggested to run all cells at once to create all results for the first-time study before exploring the details in individual cells.


## References to accompanying publications
[1] Y. Liu and M. O. Al Kalaa, "Link-Level Traffic Modeling of Medical Extended Reality (MXR) Applications," in IEEE Access, vol. 12, pp. 39166-39185, 2024, DOI: 10.1109/ACCESS.2024.3374230. Available: https://ieeexplore.ieee.org/document/10460522 [Accessed on 08/13/2024].

[2] T. Ropitault, Y. Liu, R. Rouil and M. O. Al Kalaa, “A Simulation Study of mmWave 5G-Enabled Medical Extended Reality (MXR),” 2024 IEEE International Conference on Communications Workshops (ICC Workshops), Denver, CO, USA, 2024, pp. 1907-1912, doi: 10.1109/ICCWorkshops59551.2024.10615578. Available: https://ieeexplore.ieee.org/document/10615578 [Accessed on 08/13/2024].


## FDA software disclaimer
This software and documentation (the "Software") were developed at the Food and Drug Administration (FDA) by employees of the Federal Government in the course of their official duties. Pursuant to Title 17, Section 105 of the United States Code, this work is not subject to copyright protection and is in the public domain. Permission is hereby granted, free of charge, to any person obtaining a copy of the Software, to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, or sell copies of the Software or derivatives, and to permit persons to whom the Software is furnished to do so. FDA assumes no responsibility whatsoever for use by other parties of the Software, its source code, documentation or compiled executables, and makes no guarantees, expressed or implied, about its quality, reliability, or any other characteristic. Further, use of this code in no way implies endorsement by the FDA or confers any advantage in regulatory decisions. Although this software can be redistributed and/or modified freely, we ask that any derivative works bear some notice that they are derived from it, and any modified versions bear some notice that they have been modified.


## UPDATES
08/16/2024, Version 1.0, Repo was created following DBP code sharing SOP.  
