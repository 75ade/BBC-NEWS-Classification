# BBC-NEWS-Classification

## About
This is a small project about appyling machine learning models to predict the category of a piece of BBC news, which can be: Business, entertainment, politics, tech and sport, based on its context. Since this is the first time we have made a data science project therefore there will be some errors and mistakes in processing, exploring the data and using the machine learning models.

## Usage
You can run this project on platforms like Google Colab, Kaggle or even using Jupyter Notebook on your own PC or laptop (our project does not need the GPU usage therefore you do not need to worry about the hardware part).
After installing the three files, you need to run them in order: 
- Cleaning the data
- Exploring the data
- Applyting machine learning

## Details
In this project, we will implement 3 steps:
- Cleaning the data:
  - Remove duplicate rows

  - Remove stop words in English (First time): a, an, the, then, after, before, ...

  - Remove non-English words

  - Lowercasing all the words

  - Removing punctuation and special characters: comma, dot, question mark, exclamtaion mark,...

  - Lemmatization: building, builds, built -> build

  - Remove stop words in English (Second time): a, an, the, then, after, before, ...

  - Use TF-IDF to calculate the weight of words, then base on the mean to remove words that are not important
  
- Exploring the data:
  - Find the top 10 words have the most influence to each category
  - Visualize the top 10 words with bar chart
 
  ![image](https://github.com/user-attachments/assets/67937557-1479-45f9-97f4-5945a5d75d63)
  - Find the label distribution of the training

  ![image](https://github.com/user-attachments/assets/b12b19a5-8f8f-4c8d-886b-67f05d361164)
  
- Applying machine learning model:
  - After cleaning and exploring the data, we will then fit the data to the models, in this project we will use 2 models:
    - Random Forrest
    - SVM (specifically SVC)

## Results:
- Random Forrest:
  
![image](https://github.com/user-attachments/assets/d7fb9f8f-bce4-4b49-9bf9-70b07853f161)

- SVC:
  
![image](https://github.com/user-attachments/assets/062f8c1a-28ed-4c22-b785-4c7d85baf9be)

