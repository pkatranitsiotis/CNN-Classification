# CNN-Classification
Master Thesis: Classification approach for wristwatch price estimation regarding the financial benefits when launching a new product.

# Topic
This thesis focuses on an industry-level application of Deep Learning. Particularly, its objective
is the creation of an Artificial Intelligent algorithm capable of predicting accurately the price of a
wristwatch. Wristwatches industries have suffered substantial evolution throughout the years and
due to the growth of technologies, their potentialities became outnumbered. Consequently, their
price range has been overextended and has provided the opportunity for all social classes to supply
a wristwatch for their daily scheduling. The proposed model will forecast this price by using only
visual data, and thus it will provide significant benefits to the wristwatch industry regarding the
launching of a new product. More specifically, a designed image could be fed into the model and by
considering the predicted price, the company can proceed to a variety of modifications to find the
most optimal one. Therefore, it will be able to design the most income-effective wristwatch before
the production level and raise its annual revenue. For the efficiency of the model, Amazon’s data
will be used, since it is the market leader in this category as it provides products in a wide variety of
prices and capabilities

## Techincal perspective
The model takes as input visual data i.e., image of a wristwatch and predicts its price class.

# Dataset
A dataset that contains wristwach images along with their corresponding specifications was created with Web-Scrapping using Python and CSS.
The aforesaid dataset can be found on Kaggle: https://www.kaggle.com/datasets/pkatranitsiotis/for-the-watch

# Model
A Convolutional Neural Network (written in PyTorch) was trained achieving 93% accuracy.
![output](https://user-images.githubusercontent.com/101392986/210436739-5f9d1f0f-8ccb-4f69-9c0c-628c46deb906.png)

# Predictions
![predictions](https://user-images.githubusercontent.com/101392986/210436769-8f0e745e-7d84-4d8b-85c1-f5af09444bba.png)
