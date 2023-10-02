# Anticipating Health Outcomes in Equines

## Introduction
This repository contains data, several models, and visualizations related to predicting health outcomes of horses.
Equine health is crucial for ensuring the well-being of these magnificent creatures, and understanding the factors that influence their health is essential for effective care.

## Dataset
The dataset used for this analysis is avaible through Kaggle Competition https://www.kaggle.com/competitions/playground-series-s3e22

It contains various features related to equine health, such as surgery, age, rectal temperature, pulse, and more.

### Sample of the Dataset

|   id  | surgery |   age   | hospital_number | rectal_temp | pulse | respiratory_rate | temp_of_extremities | peripheral_pulse | mucous_membrane | capillary_refill_time |
|-------|---------|---------|-----------------|-------------|-------|------------------|---------------------|------------------|-----------------|-----------------------|
| 1235  |    no   |  adult  |     534053      |     38.6    |  40.0 |       20.0       |        normal       |      normal      | normal_pink     |     less_3_sec
| 1236  |   yes   |  adult  |     528469      |     38.2    | 112.0 |       48.0       |         cool        |     reduced      |  bright_pink    |     more_3_sec
| 1237  |   yes   |  adult  |     528178      |     37.7    |  66.0 |       12.0       |         cool        |      normal      |  bright_red     |     less_3_sec
| 1238  |    no   |  adult  |     534784      |     37.1    |  88.0 |       20.0       |         cool        |     reduced      | pale_cyanotic   |     less_3_sec
| 1239  |   yes   |  adult  |     529840      |     38.3    |  50.0 |       12.0       |         None        |      normal      |  bright_pink    |     less_3_sec

## Visualizations

### Histograms of Numerical Features


### Stacked Bar Chart: Age, Surgery, and Outcome


### Violin Plots: Health Outcomes vs. Numberical Features


### Feature Importance


## Conclution
