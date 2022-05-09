# production_env

Project is based on Perceptron model used for classification of tulips species based on sepal and petal length (file Perceptron.py). 
Trained model is serialized with Pickle module (file model.py).  
In app.pl app based on flask server is created and sql alchemy engine is used for database connection. Then database perceptron_predict.db is created. User inserts in localhost link sepal and petal length and model generate results of classification. Both result and inserted dimensions are then saved to our database. 
