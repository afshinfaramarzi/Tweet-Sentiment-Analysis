# Tweet-Sentiment-Analysis


## Data set explanations: 

This dataset is meant for sentiment analysis of Twitter data. The objective is to determine the 
sentiment of a message towards an entity. The dataset comprises three classes: Positive, Negative, and Neutral. 
Messages that are not related to the entity are considered as Neutral. We have two data sets, one for training (training.csv)
and the other for validation (validation.csv).

## Methods used in this project : 

**Non-pretrained models:**  
 
* RNN (With Gradient Clipping and Proper Weight Initialization) 
* BiLSTM 
           
**Pretrained models:** 
        
* BERT 
* Mobile BERT 
* ALBERT
         
**Important Note:** Please note that due to my limited computational resources (laptop), I was unable to run pre-trained models on the dataset. Even fine tunning the model for e few epochs takes a significant amount of time in my system. Therefore, I only created the models and ran the first epoch to ensure there were no errors or bugs. If you have access to more powerful computational resources (GPU or TPU), you are welcome to run the pre-trained models and compare the results with those of RNN and BiLSTM!        
          
