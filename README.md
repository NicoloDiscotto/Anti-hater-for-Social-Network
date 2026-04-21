# Anti-Hater Filter for Social Networks

## Project Description

Develop a deep learning model with recurrent layers (LSTM/GRU) to automatically identify toxic content in online comments, classifying them into six categories:
- Toxic
- Severely Toxic
- Obscene
- Threat
- Insult
- Identity hate
  
## Objective

The model produces for each comment a binary vector of 6 elements, one for each toxicity category, with values ​​0/1.
The solution automates moderation, reducing human workload and improving the security of the platforms where it is used. 
The pipeline is efficient and ready to scale.
  
## Datasets 

The training and testing images are hosted in a separate repository:
🔗 [Filter_Toxic_Comments_dataset](https://proai-datasets.s3.eu-west-3.amazonaws.com/Filter_Toxic_Comments_dataset.csv)

## Library

- `iterative-stratification`
- `numpy `
- `pandas`
- `matplotlib`
- `seaborn`
- `wordcloud `
- `scikit-learn`
- `nltk`
- `tensorflow`
- `joblib`
