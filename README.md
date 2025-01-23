# Mini Chatbot Project in Python with Source Code
A Python-based chatbot that utilizes Natural Language Processing (NLP) techniques to process user inputs and provide appropriate responses. This project demonstrates key steps in building a chatbot, including preprocessing text, training a neural network model, and designing interactive conversations.

## Steps to Run the Project 
1. **Mount Google Drive**
Update the data_root variable to the correct path where intents.json is located in your Google Drive.
2. **Load Required Libraries**
The necessary libraries such as nltk, numpy, and tensorflow are imported.
3. **Load the Dataset**
The intents.json file is parsed to extract patterns, responses, and corresponding tags.
4. **Preprocess the Data**
Tokenize and lemmatize text.
Create a Bag of Words (BoW) representation.
One-hot encode class labels.
5. **Train the Neural Network**
A feedforward neural network with dropout is used.
6. **Train the model on the preprocessed data.**
Interact with the Chatbot
Use the chatbot in an interactive session. Type your queries, and the bot will respond based on the trained model.

