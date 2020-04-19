1. What Is Overfitting, and How Can You Avoid It? 
=> The model only fit on the training data not on the test data, to avoid we drop out to make model simple or change the learning rate.
   Test (cross-validation k folds) => danh gia toan bo data.

2. What Is Underfitting, and How Can You Avoid It? 
=> The model neither fit on the training data nor on the test data. To avoid we train model with more time, train with more data, make model more complex. 

3. What Are the Different Types of Machine Learning?
=> Sup, Unsup, Reinforcement 

4. How Do You Handle Missing or Corrupted (khong doc dc) Data in a Dataset?
=> Remove, Mean, Lay thang pho bien nha, Random by Gaussian

5. Machine Learning vs Deep Learning
=> Deep learning is belong to Machine Learning, Deep Learning based on Neural Network, it needs more data, strong computer. 
   Deep learning can learn features by itself, Machine Learning does it manually.
   
6. Decission tree vs Random Forest 
=> Decission tree trains from root, Random Forest has many trees.

7. What’s the trade-off between bias and variance?
=> Minimum bias & minimum variance => Balance
https://towardsdatascience.com/understanding-the-bias-variance-tradeoff-165e6942b229

Project
• Based on energy use, water use, indoor environmental quality and material to predict the green building
=> Algo: Logistic Regression, Naïve Bayes classifiers, SVM, Deceission Tree, KNN.
   Libraries: sklearn, after that Tensorflow
   Visualization: mathplotlib, 
   
• Helped the company to save time and money when implemented the Customer Service Chatbot.
=> + Preprocessing Data (re, nltk, *)
   re: \d* => <number>, ....
   nltk. remove stop word, tokenize, NER  
   
   text -> csv (question, answer)
   + Wrote restfull API 
   
• Use the Computer Vision to check the quality of paper in factory.
=> RestNet18, RestNet50, pretrain model.

• Build the Machine Learning model to predict the number of selling products in the next month.
=> Features: Date, Location, Sold out, Product.
   Each product has one model.
   Year by year.
   Based on: 2 months
   

Job requirement

Scala

Familiarity with some key concepts in Computer Vision
 Recognition
 Motion analysis
 Scene reconstruction
 Image restoration

Experience in a variety of Deep Learning architectures and models including Residual Networks, RNN/CNN.
