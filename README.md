# A-Classifier-for-Stock-Movements

This Classifier is built base on stocks movements and the data is from https://www.kaggle.com/cnic92/200-financial-indicators-of-us-stocks-20142018/notebooks .First, apply SVM, Random Forest, and Neural Network to bulid different classifiers and find that SVM and RF perform well. Then, extract the top ten features and test both SVM and RF again. The results are below:
SVM (10 features) : accuracy on training set: 0.984821
                    accuracy on test set: 0.976321.
Random Forest (10 features) : accuracy on training set: 1.000000
                              accuracy on test set: 0.999089.
In conclusion, these two models are still working well after feature extraction.
