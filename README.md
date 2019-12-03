# Google Play Store App Rating Prediction


### Overview of Project


The project mainly focus on predicting the rating of Apps in Android market based on the collected features of published apps. It covers data preprocessing, EDA, ML pipeline to predict the ratings and corresponding results. 


The dataset was scraped from Google Play Store for about 10k Android Apps and documented from Kaggle.  
https://www.kaggle.com/lava18/google-play-store-apps   
The dataset contains 10840 entries and 13 features with each app. In this case, target variable is App rating and it is a regression problem. The description of each feature is given below:  
1. App: Application name  
2. Category: Category the app belongs to  
3. Rating: Overall user rating of the app out of 5 stars(as when scraped)  
4. Reviews: Number of user reviews for the app (as when scraped)  
5. Size: Size of the app (as when scraped)  
6. Installs: Number of user downloads/installs for the app (as when scraped)  
7. Type: Paid or Free  
8. Price: Price of the app (as when scraped)  
9. Content Rating: Age group the app is targeted at -- Children / Mature 21+ / Adult  
10. Genres: An app can belong to multiple genres (apart from its main category). e.g. a musical family game will belong to Music, Game, Family genres  
11. Last Updated: Date when the app was last updated on Play Store (as when scraped)  
12. Current Ver: Current version of the app available on Play Store (as when scraped)  
13. Android Ver: Min required Android version (as when scraped)  


### Versions


  - matplotlib-base=3.1.1
  - pandas=0.25.0
  - scikit-learn=0.21.3
  - py-xgboost=0.90
  - numpy=1.17.1
  - lime=0.1.1.36
  - jupyter_client=5.3.1
  - jupyter_core=4.4.0
  - jupyterlab=1.1.1
  - jupyterlab_server=1.0.6
  - jupytext=1.2.4
  - python=3.7.3

```python

```
