# INTRODUCTION

The Spam Classification project aims to classify emails as spam or not spam , based on the set of words and the number of times each word has occurred.
Unlike my project on the Titanic Survival Predictor (link given below) , this is much more compact , due to less requirements of preprocessing . Moreover , certain cells have been executed and then deleted to maintain a simple workflow.
For example , cells that ran automatic hyperparameter tuning programs have been deleted , but the values have been incorporated in the model classes directly.
There was no need of vectorization of the dataset as it had already been vectorized. An attempt to add TF-IDF weights to the dataset cost the accuracy of the models dearly , due to high regularization. 
Hence , I decided against it.
Please note that only four models have been put to competition , this being the initial version of the project . However , as time progresses and my learning grows , a lot more ML models along with neural networks 
would be trained on this dataset.

# ABOUT THE DATASET

This data consists of 3002 columns and 5172 rows , each row representing an email.
The columns consist of the Email number , the various words used in the emails and finally a prediction column that decides whether an email is spam or not.

# SOLUTION PROCESS

* Upload and Understand Data -> Preprocess Data -> Train ML models on data -> Test and validate models -> Deploy the best model
* Libraries used : numpy , pandas , matplotlib , scikit-learn

# REFERENCE LINKS :-

Google Colab Notebook link for this project :- https://colab.research.google.com/drive/1YP2ujTx3ThHLrQZrNdCplmppl1eQQeOX?usp=sharing

Link to access the dataset :- https://www.kaggle.com/datasets/balaka18/email-spam-classification-dataset-csv/data

Link to the Titanic Survival Predictor project :- https://github.com/sriharisrivathsanml-afk/Titanic_Prediction_SrihariSrivathsan
