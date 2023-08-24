## Data Science Portfolio

---

### Computer Vision

#### Muay Th.AI Trainer
[Link to Github](https://github.com/wynne-chen/DSI-37-Capstone)

Inspired by my own hobby and the difficulties of training alone over COVID, I built a first-of-its-kind recommender app. Making use of MoveNet and machine learning methods and a data set entirely created by myself, this fitness buddy app can distinguish between two moves (a jab and a roundhouse kick) with an ROC-AUC of 1.0, count the number of reps, and give live posture advice. 

Eventually, I hope to scale it up to include all the basic moves in both orthodox and southpaw stances (jabs, crosses, hooks, uppercuts, elbows, teeps, roundhouse kicks, knees). 

<img src="images/dummy_thumbnail.jpg?raw=true"/>



---

### NLP

#### Analysing r/Keto and r/Paleo For Diet Trends
[Link to Streamlit](https://consumer-dietary-preferences.streamlit.app/)

To challenge ourselves, we chose two highly similar communities on Reddit: the keto diet subreddit and the paleo diet subreddit. We then scraped the posts using the Reddit API to build an NLP model to distinguish between users of these subreddits. We also did detailed EDA on these two communities to identify the interests they have. Our final classification model had an ROC-AUC of 0.98 and our deployed product allows users to either type in queries to identify whether they are more likely to be keto or paleo dieters, or to upload an excel spreadsheet of comments/reviews from their own client base so they can have better insights about them. 

<img src="images/Screenshot 2023-08-21 at 11.28.07 AM.png?raw=true"/>
<img src="images/Screenshot 2023-08-21 at 11.29.11 AM.png?raw=true"/>
<img src="images/Screenshot 2023-08-21 at 11.29.58 AM.png?raw=true"/>


---
### General

#### West Nile Virus Prediction
[Link to Streamlit](https://west-nile-virus-prediction.streamlit.app/)

In this project, we studied extremely fragmented, granular datasets from the city of Chicago relating to the West Nile Virus epidemic from 2010-2014. Using SMOTETomek to rebalance our dataset, we ran through 7 different models with hypertuning before we settled on an XGBoost model which hit an ROC-AUC of 0.88. Our final deployed product allows users to look at different areas in Chicago to evaluate the relative risk of WNV. 

<img src="images/Screenshot 2023-08-21 at 11.31.23 AM.png?raw=true"/>
<img src="images/Screenshot 2023-08-21 at 11.42.37 AM.png?raw=true"/>

#### HDB Price Predictor
[Link to Streamlit](https://hdb-price-predictor.streamlit.app/)

Making use of linear regression, ridge, and lasso models trained on a dataset of resale public flats (HDB) from the SG government, my group built a price predictor model with an R2 of 0.90. Users can check an interactive map or fill up a short form to receive a predicted price for their flat. We specifically built our model with the end product in mind--as such, we refined the model to the point that we only used features that our users would likely be able to answer, while maintaining a reasonably high model accuracy. 

<img src="images/Screenshot 2023-08-21 at 11.33.12 AM.png?raw=true"/>
<img src="images/Screenshot 2023-08-21 at 11.33.23 AM.png?raw=true"/>

