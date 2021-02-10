# Binary Weather Classification

 <img align="right" src="https://upload.wikimedia.org/wikipedia/commons/3/30/Weather_icon_-_sunny_to_cloudy.svg" width="300" height="300"/>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
![Python](https://img.shields.io/badge/python-v3.6+-blue.svg)
![Contributions welcome](https://img.shields.io/badge/contributions-welcome-orange.svg)
[Tutorial en español](https://medium.com/@paulivrj.1512/clasificaci%C3%B3n-binaria-de-im%C3%A1genes-con-redes-neuronales-clima-soleado-o-nublado-8dd828a8fde0)

<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li>
     <a href="#about-the-project">About The Project</a>
   </li>
    <li><a href="#dataset">Dataset</a></li>
    <li><a href="#how-to-run">How to run</a></li>
    <li><a href="#tutorial">Tutorial</a></li>
    <li><a href="#results">Results</a></li>
    <li><a href="#version-history">Version History</a></li>
  </ol>
</details>

## About the project
This work deals with a binary (two classes) classification of images problem. The problem is detecting if the image represents a sunny or cloudy weather, within images taken from the ground (not satellite imagery). The image may be a photo of a landscape, a city, a person, etc. and may contain lots of different objects in it. The is written in Python. Pytorch library is used to implement the machine learning model. Supervised learning is used to solve the problem thru a deep learning model, a convolutional neural network.

## Dataset
The dataset is hosted in Kaggle. It is  made up of images of outdoors under two different kinds of weather: sunny or cloudy. It contains a total of 10253 images, divided in two folders:
* The train (training) folder: contains 'sunny' and 'cloudy' folders, each one has 5000 RGB jpg images.
* The test folder: contains 'sunny' and 'cloudy' folders, with 153 and 100 RGB jpg images respectively. 

You can find the dataset here: https://www.kaggle.com/polavr/twoclass-weather-classification. From this page, it's possible to create a new notebook in Kaggle (you must have an account). 

Moreover, a [notebook](https://www.kaggle.com/polavr/exploring-the-data) is included in order to show how to explore the dataset. 

## How to run
There are several free online pages where you can run a Jupyter notebook:
* Main notebook:
 - Binder: [![Binder](https://mybinder.org/badge.svg)](http://mybinder.org/v2/gh/paula-rj/binary_weather_classification/main?filepath=binary-weather-classification.ipynb)
 - Kaggle: https://www.kaggle.com/polavr/binary-weather-classification (you need to have an account)
* Exploring the data:
 - Binder:  [![Binder](https://mybinder.org/badge.svg)](http://mybinder.org/v2/gh/paula-rj/binary-weather-classification/main)
 - Kaggle: https://www.kaggle.com/polavr/exploring-the-data
 
Of couse, you can always download and run on your computer locally.

## Tutorial
You can find a step-by-step tutorial containing more detaled explanations in **spanish** about the project in this [link](https://medium.com/@paulivrj.1512/clasificaci%C3%B3n-binaria-de-im%C3%A1genes-con-redes-neuronales-clima-soleado-o-nublado-8dd828a8fde0).

## Results
The notebooks are also hosted in Jovian. There is a button in the upper right of the window thru which you can choose to run the code in Binder, Kaggle or Colab (you must have an account).
[Main notebook](https://jovian.ai/paula-rj/final-project-binary-weather-classification)

[Exploring the data](https://jovian.ai/paula-rj/exploring-data-binary-weather-classification)

The comparison of parameters set in different versions and the evaluation metrics are also hosted in Jovian, It's not necessary to have an account to see them. [link](https://jovian.ai/paula-rj/final-project-binary-weather-classification/v/24/records)

## Version History

* 0.1
    * Initial Release
