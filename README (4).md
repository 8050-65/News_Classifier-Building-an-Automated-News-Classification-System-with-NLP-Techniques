# Project12--Web-Scrapping-and-News-Classification
## NewsClassifier: Building an Automated News Classification System with NLP Techniques
The project aims to build a news classification involving several steps, including 
* web scraping 
* data preprocessing 
* model training

# Tools Used
* BeautifulSoup (Web Scrapping)
* Python
* Pandas (Data Cleaning)
* TF -IDF
* Scikit Learn
* K-Means clustering
# Approach
### 1. Web Scrapping
 * Using BeautifulSoup, a Web-Scrapping Tool, to extract the news articles from Indianexpress website. The title and content of each news article was extracted covering 4 different topics(Lifestyle,Entertainment, Parenting, and Politics). The scrapped articles were converted to Dataframe and save as a csv file for further process
### 2. Data Cleaning
 * The Text data was cleaned by removing the punctuations, special characters and stop words.
 * Then TF-IDF, a vectorization technique was applied to convert words into numbers
### 3. Clustering
 * After dropping the label column, k-means clustering was applied to the dataset. 
### 4. Text Classification
* The data was split into training and testing sets.
* The Machine learning models like RandomForest Classifier, Linear SVC, Logistic Regression and MultiNomialNB were used to make the classifications. 
* After thorough evaluation, the Linear SV(97 % accuracy) was finally selected as the ideal algorithm.
* The model was then saved as a pickle file to perform future classifications.
   
 
   
