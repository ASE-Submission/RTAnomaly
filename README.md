# RTAnomaly

![](https://img.shields.io/badge/version-1.0-blue.svg) 
![](https://img.shields.io/badge/language-python-orange.svg)

Here is the repository for ASE submission "Correlation-Aware Performance Issue Identification in Cloud Service Systems".
The industrial dataset can not be directly used at this time, though the model can run. We will provide our compelete feature defination list upon acceptance.
After that, you can directly extract the features using our calculation code and detect anomalies using our isolation forest.

## Architecture

#### Overview
![RTAnomaly](https://github.com/ASE-Submission/RTAnomaly/assets/131580646/e6a21e32-d5bf-49c4-9e48-18f124f4083e)
![PU](https://github.com/ASE-Submission/RTAnomaly/assets/131580646/5d25a172-4f02-4423-8c5f-f5c54d99e0c9)

#### Model M

![Maat 003](https://user-images.githubusercontent.com/112700133/216756602-736d7dc2-9253-44e6-83ab-f13f8f188733.jpeg)

## Data
The data should be stored in csv files with the first column being ``timestamp'' and the last column being ``label''. If labels are not avaliable, it can be all zeros.

We put an example dataset (part of the AIOps18 dataset due to the space limit) in the ``data'' director.

## Requirements


## Running
For the prediction phase, run:
```$ cd src && python predict.py```

For the detection phase, run:
```$ cd src && python detect.py```
