# MMAI894
# Deep Learning
![beauty4](https://user-images.githubusercontent.com/67903463/160304953-87bccf5b-b285-4114-b206-31b2ec113e05.png)




•Data Exploration

•Word2Vec

•Glove

•Data Augmentation

•LTSM

•CNN

•Zero Shot Learning


# Executive Summary 

Productivity: 

Though emails can be a valuable source of information and have remained the primary method of communication in the workplace, they can also have a significant negative impact on worker productivity. In fact, reading preview text alone costs workers 87 hours a year.6 That is almost eleven working days (based on an 8-hour day) spent without anything to show for, not even having replied to the emails themselves. With classification, workers are directed to focus their attention on the areas that matter most and are less likely to feel overwhelmed by a full inbox. 
![Beauty1](https://user-images.githubusercontent.com/67903463/160304263-d4718d04-e3c3-4d88-804f-58616e337d98.png)

By running clusters using k-means we were able to uncover the themes in the vector representations and identified 6 departments. We augmented the list of keywords in each department by using cosine distance. After applying feature engineering, label encoding and tokenization, the data was ready to be modeled. We began by running 3 LSTM models using the same parameters side by side and compared them. The data fed into each of the models respectively was: 

-       Experiment 1: Word2Vec pre-trained embeddings without tuning  

-       Experiment 2: GloVe  pre-trained embeddings without tuning  

-       Experiment 3: GloVe  embeddings that we fine-tuned using our Enron database 

Experiment 3 had the highest accuracy score. Now that we know that tuning the pre-trained model with our data set gives us a better score, we tested a CNN model which accomplised an even higher accuracy score.  

Recommendations and observations 

There are still many recommendations we would propose to make our classifier even more effective. Having more data to train our model as well as more capabilities of the model itself such as project-level sorting, triaging, and recognizing phishing attempts can result in a model that is more likely to be positively received for widespread adoption. 

Operationalization and scaling: 


![beauty2](https://user-images.githubusercontent.com/67903463/160304269-fb017d40-dc1a-468b-ae33-7dd89e6bb872.png)

Prior to production and deployment, there are still many scaling factors to consider for the future. Having a strategy for continuous training after the model has been deployed, data security and compliance, and explainability are all important in ensuring that the model can have an impact in the workplace not only in the short-term but also for the foreseeable future. 
