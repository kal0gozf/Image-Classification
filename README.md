# Image Classification

[**Dataset**](https://www.kaggle.com/datasets/sujaykapadnis/emotion-recognition-dataset/data?select=dataset)

**Procedure:**
  1. Using CNN model to extract the feature
  2. Comparing Adding Fully Connected Layer (FC) layer and adding Global Average Pooling (GAP) layer
  3. For the better performance method, Using PCA method and backward selection to optimize the accuracy

**Result**
  1. FC layer provide better performance
  2. logistic regression after PCA and backward selection method provide the similar result with original logistic regression model (reduce the feature from 512 to 16)
  3. The selected model (Logistic Regression) accuarcy and F1 scores are 83.51% and 84% 

**NB**
This project only utilize 3 classes in the dataset, namely Angry, Surprise and Ahegao, as the limited computing resource
