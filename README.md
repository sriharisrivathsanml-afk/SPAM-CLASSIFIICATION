The Spam Classification project aims to classify emails as spam or not spam , based on the set of words and the number of times each word has occurred.
The link for the dataset has been posted below . It could not be uploaded in this repository due to file size constraints in GitHub.
Unlike my project on the Titanic Survival Predictor (link given below) , this is much more compact , due to less requirements of preprocessing . Moreover , certain cells have been executed and then deleted to maintain a simple workflow.
For example , cells that ran automatic hyperparameter tuning programs have been deleted , but the values have been incorporated in the model classes directly.
There was no need of vectorization of the dataset as it had already been vectorized. An attempt to add TF-IDF weights to the dataset cost the accuracy of the models dearly , due to high regularization. 
Hence , I decided against it.
Please note that only four models have been put to competition , this being the initial version of the project . However , as time progresses and my learning grows , a lot more ML models along with neural networks 
would be trained on this dataset.

Attached below are links for the necessary references. Stay tuned for further updates !

REFERENCE LINKS :-

Google Colab Notebook link for this project :- https://colab.research.google.com/drive/1YP2ujTx3ThHLrQZrNdCplmppl1eQQeOX?usp=sharing
Link to access the dataset :- https://www.kaggle.com/datasets/balaka18/email-spam-classification-dataset-csv/data
Link to the Titanic Survival Predictor project :- https://github.com/sriharisrivathsanml-afk/Titanic_Prediction_SrihariSrivathsan
