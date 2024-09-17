## Sentiment Analysis Using LSTM

This project aims to develop a sentiment analysis model that categorizes text as either positive or negative using a Long Short-Term Memory (LSTM) neural network. The dataset, obtained from Kaggle, consists of labeled text reviews, each labeled as positive or negative. To prepare the data, preprocessing techniques such as tokenization and padding are applied, ensuring that the text is transformed into sequences of uniform length, which is essential for the model's effective training. The architecture includes an embedding layer to convert tokens into dense vectors, followed by an LSTM layer that captures contextual information from the sequences. Finally, a dense layer with a sigmoid activation function is used to predict sentiment.

The project employs a simple yet effective LSTM-based architecture. The data is divided into training and testing sets, enabling the model to learn from 80% of the data while assessing its performance on the remaining 20%. To combat overfitting, techniques like dropout are utilized. The model is compiled with binary cross-entropy as the loss function, Adam as the optimizer, and accuracy as the metric for performance evaluation. After training, the model's effectiveness is measured by its accuracy on the test data, resulting in dependable sentiment predictions.

Beyond automated predictions on the test data, the project also features a manual sentiment prediction tool. Users can enter any sentence, and the model will forecast its sentiment, indicating whether it is positive or negative along with a confidence score. This interactive element enhances the project's practicality for real-world sentiment analysis applications.
