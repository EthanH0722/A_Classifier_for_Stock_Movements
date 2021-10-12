# A-Classifier-for-Stock-Movements

This Classifier was built base on stocks movements and the data is from https://www.kaggle.com/cnic92/200-financial-indicators-of-us-stocks-20142018/notebooks .First, applied SVM, Random Forest, and Neural Network to bulid different classifiers and found that SVM and RF performed better than others. Then, extracted the top ten features and tested both SVM and RF again. The results are below:
SVM (10 features) : accuracy on training set: 0.984821
                    accuracy on test set: 0.976321.
Random Forest (10 features) : accuracy on training set: 1.000000
                              accuracy on test set: 0.999089.
In conclusion, these two models have a better performance even after feature extraction.
