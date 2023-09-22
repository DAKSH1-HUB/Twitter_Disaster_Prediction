# Twitter_Disaster_Prediction

Dataset was sourced from Kaggle. Data set contains:-</br>
id - a unique identifier for each tweet</br>
text - the text of the tweet</br>
location - the location the tweet was sent from (may be blank)</br>
keyword - a particular keyword from the tweet (may be blank)</br>
target - in train.csv only, this denotes whether a tweet is about a real disaster (1) or not (0).</br>

Methodology.
Exploratory Data analysis was performed on the data to find some of the Insights and find some of the relations and trends in the data.</br>
Using Text Analytics, textual data was converted to numerical data using TF-IDF method in order to train the model, using Random forest classifier.</br>
Test data was put into our trained model and Mean absolute error was used to test the efficiency of the model.</br>

Insights before prediction:-</br>

![image](https://github.com/DAKSH1-HUB/Twitter_Disaster_Prediction/assets/81084807/38d82fb1-61ee-45c4-bf9c-7175b24af6f1)
</br>
**Number of Fake and Real tweets**
![image](https://github.com/DAKSH1-HUB/Twitter_Disaster_Prediction/assets/81084807/02600ea3-17e0-44ee-bd11-63efaed8d041)
</br>
**Comparison of length of Real and Fake tweets.**
![image](https://github.com/DAKSH1-HUB/Twitter_Disaster_Prediction/assets/81084807/c00f54d0-6eae-4400-b4cc-d97ef5e77185)
</br>
**Sentiment Analysis of the tweets and trying to find some relation. Most of the tweets were neutral.**
![image](https://github.com/DAKSH1-HUB/Twitter_Disaster_Prediction/assets/81084807/7e1d56ba-1cfa-46ae-8c47-a50a4ec67d90)
</br>
**Average Sentiment rating according to our traget variable**
![image](https://github.com/DAKSH1-HUB/Twitter_Disaster_Prediction/assets/81084807/e479d8ec-8531-4096-82f6-161e408a94c9)
</br>



