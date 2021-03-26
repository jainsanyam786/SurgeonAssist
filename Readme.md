# SurgeonAssist.
> SurgeonAssist is a computer vision based application to detect, identify, and track the usage of surgical instruments during surgery to prevent surgical instrument retention.
<img src="./Img/RSI.png" alt="RSI" width="800" height="500"/>  

## Table of contents
* [General info](#general-info)
* [Application Flow Chart](#application-flow-chart)
* [Features](#features)
* [Code](#code)
* [Results](#results)

## General info
* Dataset for the project is taken from [kaggle](https://www.kaggle.com/dilavado/labeled-surgical-tools).
* Used transfer learning model “MobileNet” with “imagenet” weights.
* Dataset includes 4 surgical instruments -  Curved Mayo Scissor, Scalpel, Straight Dissection Clamp, Straight Mayo Scissor.
* Accuracy of the trained model is around 80%.
* Major challenge was to differentiate Curved Mayo Scissor from  Straight Mayo Scissor as both look similar.

## Application Flow Chart
* Below is the application flow chart.
<img src="./Img/FlowChart.png" alt="FlowChart" width="1000" height="500"/> 

## Code
* [Model Training, validation and testing.](https://github.com/jainsanyam786/SurgeonAssist/blob/main/SurgeonAssist_Transfer_Learning.ipynb)
* Jupyter-notebook to test [basic functionality](https://github.com/jainsanyam786/SurgeonAssist/blob/main/Interactive_UI_to_test_functionality.ipynb)
 
## Results
* Confusion matrix for the trained model.
<img src="./Img/ConfusionMatrix.png" alt="ConfusionMatrix" width="800" height="500"/>

* Result for a an sample image.
<img src="./Img/Result.png" alt="Result" width="800" height="500"/>
