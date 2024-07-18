# Stock-market-Arima

## Project Overview

Using an Arima model to predict the stock market.

### Table of Contents

- [Dataset](#dataset)
- [Project Phases](#project-phases)
  - [Phase 1 - Data Collection and Pre-processing](#phase-1---data-collection-and-pre-processing)
  - [Phase 2 - Model](#phase-2---model)
  - [Phase 3 - Model Evaluation and Refinement](#phase-3---model-evaluation-and-refinement)
- [Languages](#Languages)
- [Packages](#Packages)

## Dataset

The dataset used in this project can be found at the Yahoo finance website. This data was import using a package in python but could also be request through yahoo api. This data is reliable but is not directly from the company. However, for the extent of which this data will be used this is good enough. The data uses a ticket code to identify what data you want from which company.
## Project Phases

### Phase 1 - Data Collection and Pre-processing

- Download the dataset.
- Explore the dataset.
- Pre-process the data.

First the data is imported and cleaned before finding the optimal parameters for the ARIMA model. The parameters where found both manually and automatically for comparison. In the end I found that the d,p,q values were best respresented by 2,1,1 respectively.
### Phase 2 - Model

- Data Splitting 
- Training

I split the data in training and test sets and started training the ARIMA model. This meant we can test the accuracy of the parameters used.
### Phase 3 - Model Evaluation and Refinement

- Hyper parameter Tuning 

I believe different ranges of data will affect the outcome of the ARIMA model. The ARIMA model should also tested for price signals and used against simple strategies like the moving average.

## Languages

- Python
- Jupyter Notebook
- 
## Packages

Main packages:
- Numpy
- Pandas
- Sklearn
- Matplotlib
- Stats models
