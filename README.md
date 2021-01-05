# Udacity-Car_Radar_Lanes


[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/guilistocco/Udacity-Car_Radar_Lanes/main?filepath=Radar_analysis.ipynb) 

[Link to Medium post](https://guilistocco.medium.com/the-proof-that-your-assumptions-about-traffic-are-right-3820c23d496f)


 
 
## Why this is an important project?
As an engineer student, I saw the oportunity to use data science in a traffic context. The porpuse of this project is to reflect about a few assumptions every one that uses public or private transportation wonder: Does cars on the left lane run faster? Does heavy vehicles alwyas stay on right lanes? How can we predict the speed of new cars? Those questions were answered using data science skills.

## Summary of analysis

Models using with real world data will hardly give surprising results, and here it couldn't be diferent. Using only a few tools like subseting, sorting and mapping is possible to answer good questions and even generalise some results.

The findings are that the left lane of a road has higher speeds then others; speed and lane are well correlated as well as lengh and type of a vehycles; Random Forest scores 13% for one day of data.

## Libraries
* Pandas
* Numpy
* Matplotlib
* Seaborn
* Scikit Learn


## About the archives
This repository works with data from radars all over São Paulo

* Radar_Data_2.03.2018.csv contains all vehicles that radars could capture on the 2nd of March, 2018. Data is avaliable at this [link](https://drive.google.com/file/d/1VG-t8t1mq_HZV-Ue6zkth_3Ne4IfCOrq/view?usp=sharing) . Some of the columns are speed (in dm/s, must be converted), length (in dm, must be converted), date of capture, type of vehicle, etc.
* Lanes_type.xlsx tells the use of each lane
* The .png files are images used on the medium post about the project
* enviroment.yml contains the version of python and libraries used on this project. The purpose of this file is to allow the code to be reproducible
* LICENCE indicates the MIT license for this project
* Radar_analysis.ipynb is the jupyter notebook used to take coclusions for this project 

Udacity-Car_Radar_Lanes/

├── README.md

├── Radar_Data_2.03.2018.csv

├── Lanes_type.xlsx

├── lanes.png

├── correlation_lanes.png

├── enviroment.yml

├── LICENSE

└── Radar_analysis.ipynb

## Acknowledgements

All code, analysis and descriptions in this repository were made by this user and can be modyfied by anyone.

Data is provided by CET-SP and is avaliable for anyone to use and modify.

If you wantt to contribute to this project just fill a pull request.
