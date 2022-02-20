# Real-time condition monitoring of wind turbines based on self-supervised learning and supervisory control and data acquisition data

## 1. Introduction
This is the code repository for the manuscript, which is submitted to the Special Issue ***Call for papers on Energy Utilization and Conservation for Sustainable Development using Real-Time Intelligent Methods*** of ***Renewable and Sustainable Energy Reviews***.  

Codes and data will be available upon acceptance of the manuscript.  

## 2. Requirements
```numpy==1.21.2
pandas==1.3.3
torch==1.9.0
scikit-learn==0.24.2
matplotlib==3.4.2
```  

## 3. Code Structure
* `/data` contains SCADA data from an actual wind turbine.
* `main.py` contains the starting point of execution.
* `model.py` contains the implementation of the developed method. Please check our paper for the detailed descriptions.
* `data_labelling.py` provides the codes for data labelling based on warning messages and status codes.
* `features_selection.py` provides the codes for extracting features in original measurements.
* `draw_result.py` provides the codes for drawing figures of the results.


## 4. Contacts
If you have any problem, please do not hesitate to contact me at <sunsl0115@163.com> or <ssl19@mails.tsinghua.edu.cn>.
