# Final_Project_Fake_News_Detection

## Business case : 
 Nowadays, Fake news becomes to be a significant issue on the internet and social media affecting the mental and physical health of children and adults.
 The goal of my project is to build a Fake News Detection model using Machine Learning. The model will focus on identifying fake news sources, based on combined articles formed  from a source. Once a source is labeled as a producer of fake news, we can predict with high level of confidence that any future articles from that source will also be fake    news
 
 ## Data set : 
  the Data set was the csv file from Kaggle consisting of news articles and posted between 2015-2018. Two sets of data were used, one consisting of all fake news, and another     of all real news. The overall format and columns were the same across both datasets.
  The colonnes in the data was
     Id  title  autho  text  label
    
 ## Data Pipline :
    Acquiring and loading the data
    Cleaning the dataset
       Removing extra symbols 
       Removing punctuations
       Removing the stopwords
       Stemming
       Tokenization
    EDA
    TF-IDF vectorizer
    vectorizer with TF-IDF transformer
    Machine learning model training and verification
 ## Results : 
 ## EDA : 
  
 WordCloud : <img width="323" alt="Capture d’écran 2022-02-10 115340" src="https://user-images.githubusercontent.com/89710477/153392607-5f0a04ba-c723-4889-b05b-d45cc146069e.png">

 The count of most frequent word in Merge Column : <img width="435" alt="image" src="https://user-images.githubusercontent.com/89710477/153180271-33df28fb-2162-423c-9606-cf15408f4ad6.png">
