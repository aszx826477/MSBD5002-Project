# MSBD 5002 Group Project

## Task Description

This project is based on the KDD Cup 2017, one of the most famous competitions in data mining area. We select the first task:  *To estimate the average travel time from designated intersections to tollgates*.

## Dataset

The whole dataset can be downloaded via the [link](https://wiki-1252789527.cos.ap-shanghai.myqcloud.com/article/MSBD5002-Project/data.zip). Except for training and test data, you are provided with a list of extra data sources:

* The road network topology
* Vehicle trajectories
* Historical traffic volume at tollgates
* Weather data

## Project Structure

* `main.ipynb` the main notebook to demonstrate the whole process
* `feature.py` feature engineering
* `model.py` including 4 models
  * Bagging: Random Forest Regression
  * Boosting: LightGBM
  * Feedforward Neural Network
  * Bilinear-Based Res Network
* `utils.py` utils function
  * *function* `split_val()`: Split validation set
  * *funtinon* `compute_MAPE()`: Calculate the value of MAPE 