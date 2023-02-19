# House Price Prediction Using House Image and Details
The objective, is to create a machine-learning model to predict the retail price of houses given tabular data like house sqft, # of toilets/rooms, and location, along with an image of the house. 


![Screenshot 2023-02-19 235955](https://user-images.githubusercontent.com/94728532/219967808-84558d1e-6412-48ee-afdb-373f6a65ac61.png)


So I have created a deep learning  model using ensembling concept, creating two models, one is image encoder and second one uses details.
The input pipe line is like we have to give image and house detail in form of list {[image,details]} and image is feeded to image_encoder (basically it use CNN to extract features according to house price ) and details to second neural network,
And then the outputs of both neural networks is concated and feeded to a Simple NN 
