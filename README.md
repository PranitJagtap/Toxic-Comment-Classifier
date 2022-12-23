Problem Statement:
Online forums and social media platforms have provided individuals with the means to put forward 
their thoughts and freely express their opinion on various issues and incidents. In some cases, these 
online comments contain explicit language which may hurt the readers. Comments containing 
explicit language can be classified into myriad categories such as Toxic, Severe Toxic, Obscene, 
Threat, Insult, and Identity Hate. The threat of abuse and harassment means that many people stop 
expressing themselves and give up on seeking different opinions.
To protect users from being exposed to offensive language on online forums or social media sites, it 
is important to flag comments and block users who are found guilty of using unpleasant language. 
Several Machine Learning/Deep Learning models can be developed and deployed to filter out the
unruly language and protect internet users from becoming victims of online harassment and 
cyberbullying.

About Dataset:
The dataset used was Wikipedia corpus dataset which was rated by human raters for toxicity. The 
corpus contains comments from discussions relating to use pages and articles dating from 
2004-2015. The dataset was hosted on Kaggle by Jigsaw as a challenge. The comments were 
manually classified into following categories: 
1. Toxic 
2. Severe toxic 
3. Obscene 
4. Threat 
5. Insult 
6. Identity hate
train.csv - the training set, contains comments with their binary labels

Project Objectives:
To build a multi-headed model that’s capable of detecting different types of toxicity like threats, 
obscenity, insults, and identity-based hate

Models used:
LSTM, SVM, Random Forest, Logistic Regression, Multinomial NB

Model chosen:
LSTM
