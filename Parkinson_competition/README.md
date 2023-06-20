# Parkinson competition

## Team
Special thanks to my team:  
[Eric Glukhov](https://www.kaggle.com/ernestglukhov)  
[Veronika Averkova](https://www.kaggle.com/averkovanika)  
[Valery Baryshev](https://www.kaggle.com/vrbaryshev)  

On the public leaderboard, we were in 29th place towards the end of the competition (silver medal).  
However, on the private leaderboard, we dropped to [359th place](https://www.kaggle.com/competitions/tlvmc-parkinsons-freezing-gait-prediction/leaderboard?search=practicum) out of 1400 teams due to severe overfitting and imbalance on the private test data.

## Data

70 Gb of csv and parquet table data.  

[dataset_on_kaggle](https://www.kaggle.com/competitions/tlvmc-parkinsons-freezing-gait-prediction/data?select=train)  

## Tasks

The goal of this competition was to detect freezing of gait (FOG), a debilitating symptom that afflicts many people with Parkinson’s disease. We developed a machine learning model trained on data collected from a wearable 3D lower back sensor.  

## Used libraries
  
Pandas, numpy, os, pywt, sklearn, pytorch_lightning, torch.
