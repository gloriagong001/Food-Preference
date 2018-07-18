# Food-Preference

The project is to analyze food choices and preferences of college students and therefore find out the possible factors influencing performance


In order to answer questions like : 
How important is nutrition information for today's college kids? 
Is their taste in food defined by their food preferences when they were children?
Are kids of parents who cook more likely to make better food choices than others?
Are these kids likely to have a different taste compared to others?

## Dataset

The dataset is from Kaggle: https://www.kaggle.com/borapajo/food-choices/home

In Summary, the dataset has 61 attributes. All the attributes were assigned into three categories.
The first category is personal profile which contains attributes including Gender, BMI, Grade
level, GPA etc. the second one is nominal food preferences attributes related to foods with
several about exercises. The third one is open questions and is ideal for text mining.

![capture](https://user-images.githubusercontent.com/36937610/42911689-e1822c0a-8aa0-11e8-9f3f-f41254bd77f5.PNG)

## Method

**Statistical analysis** and **Natural Language Processing** were used.

## Results:
1. Data Visualization \n
The frequency of different comfort food answered by different respondents were visualized
![capture](https://user-images.githubusercontent.com/36937610/42911934-d58b89d6-8aa1-11e8-9b1d-458e6a67d4b7.PNG)

Answers of one of the open questions “reasons for having comfort food” are also
read into python sliced into bags of words using nltk toolkit5. After deleting stop words like
“the”, “that”, the frequency of different words was visualized. The first 3 frequent words are
“boredom”,” stress”,” sadness”. That complies with common sense.
![capture](https://user-images.githubusercontent.com/36937610/42911987-0657298a-8aa2-11e8-8a22-8a05b1ce410d.PNG)

Also, frequency words of current diet were visualized based on different BMI6. Firstly, records
were discretized into 2 bins of below or above average BMI. The most frequent words for high
BMI group are “Eat”, “Lot”, “Food” and “Time”. As for the group with lower BMI, most
frequent food also contain words including “Healthy”, “Vegetable” and “Fruit”.
![capture](https://user-images.githubusercontent.com/36937610/42912016-2496cffe-8aa2-11e8-89db-b74bdb8492b5.PNG)




## Files:

**Diet_Classifer.ipynb**   --------        Healthy Diet Prediction model using Natural Language Processing  

**GPA &diet.ipynb**     -------------Statistical analysis between diet habbit and GPA





