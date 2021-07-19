# Titanic Datset 
This is the legendary Titanic ML competition – the best, first challenge for you to dive into ML competitions and familiarize yourself with how the Kaggle platform works.

## The Challenge:
The sinking of the Titanic is one of the most infamous shipwrecks in history.

On April 15, 1912, during her maiden voyage, the widely considered “unsinkable” RMS Titanic sank after colliding with an iceberg. Unfortunately, there weren’t enough lifeboats for everyone onboard, resulting in the death of 1502 out of 2224 passengers and crew.

While there was some element of luck involved in surviving, it seems some groups of people were more likely to survive than others.

In this challenge, we ask you to build a predictive model that answers the question: “what sorts of people were more likely to survive?” using passenger data (ie name, age, gender, socio-economic class, etc).

## Updated Methadology:
I have made a custom transformer pipeline that makes the transformation to the data with a single function. For people who wants to get familarize with making custom transformers using sci-kit learn, this project is a good practice. 

## Updated File:

I have tried 5 models including Logistic Regression, Random Forest, XGBoost, Neural Networks and SVM. It was found that XGboost and SVM performed better than the others so I made the voting classifier out of these two algoirthms. The model achived the accuracy of 78% now, previously for a plain feed forward MLP model the accuracy was 76%. 

