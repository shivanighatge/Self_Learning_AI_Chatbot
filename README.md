# Self-Learning-Chat-bot-using-Keras
Self Learning Chat bot using Cornell Movie Data Set

The dataset is provided in the folder. The data requires two files movie_converstions and movie_lines. The folder contains the following  code files
1) Chatbot with glove embeddings and LSTM
This file contains the model trained by using LSTM using the glove embeddings. The file used for loading the grove embeddings is glove.6B.50d. The model is trained using 100 epochs which requires a lot of time so we have saved the trained model in lstm_model_glove_embeddings.h5 file. This model can be loaded from in lstm_model_glove_embeddings.h5 provided in the folder and then the user can chat with the chatbot.

2) Chatbot with skip-gram embeddings and LSTM
This file contains the model trained by using LSTM using the skip-gram embeddings. The model is trained using 100 epochs which requires a lot of time so we have saved the trained model is lstm_model_skip_embeddings.h5 file. This model can be loaded from lstm_model_skip_embeddings.h5 file provided in the folder and then the user can chat with the chatbot.

