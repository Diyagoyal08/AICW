Complete Machine Learning Pipeline

Remember this sequence:

1. Data Collection
        ↓
2. Data Understanding (EDA)
        ↓
3. Data Cleaning
        ↓
4. Data Preprocessing
        ↓
5. Feature Selection & Engineering
        ↓
6. Train-Test Split
        ↓
7. Model Selection
        ↓
8. Model Training
        ↓
9. Model Prediction
        ↓
10. Model Evaluation
        ↓
11. Hyperparameter Tuning
        ↓
12. Model Deployment
algorrithm which work for both regression and classification -- desicion tree , svm , random forest , boosting 


decision tree

  impure node , pure node

  impurity condition 
  - gini impurity = i -p2
  entropy = -plogp -1class
  -plogp-(1-p)log(1-p)

  to avoid overfitting in this tree we use pruning if length of the tree go above 5 then cut the tree


  NAive based 


  svm - 

  knn

  ensemble 
   random foarest bgging and boosting - types of these

   
box plot -- lower limit , upper limit , quater 1 , quater 2  , quater 3 , q3-q1 = inter quite range iqr ,  ll box k niche q1-1.5 iqr , ul box k uper - q3+1.5 iqr 

NLP - 1 NLU :language translation , text classification , text summarization , sentiment analysis 
      2 NLG : text generation 

lib - NLTK , Spacy , regex
NLP Lifecycle - 
1. problem defination 
2. data collection 
3. case conversion (converting into lower case)
4. special character removal 
5. tokenization
6. stop word removal : helping verb , conjunction , articiles
7. converting words into root format : 1. stemming 2. lammetization 
8. POS tagging 
9. name entity recogizina5ion
10. Convert text data into numerical data  - embedding vector generation
11. model development 
12. model ealution , testing