# Mini Chatbot Project in Python with Source Code
A Python-based chatbot that utilizes Natural Language Processing (NLP) techniques to process user inputs and provide appropriate responses. This project demonstrates key steps in building a chatbot, including preprocessing text, training a neural network model, and designing interactive conversations.

## Features 
- Interactive and responsive chatbot for text-based inputs.
- Utilizes Bag of Words (BoW) for feature extraction.
- Customizable intents with responses provided in intents.json.
- Neural network model built with TensorFlow/Keras.
- Designed to be lightweight and easy to modify.

## File Structure 
- **intents.json** contains predefined patterns, tags, and responses for the chatbot.
- The **.ipynb notebook file** has the Python code implementing the chatbot with detailed explanations.
- README.md has the documentation for the project (this file).

## Requirements 
To run this project, ensure the following dependencies are installed:
- tensorflow
- numpy
- nltk

You can install them using pip:

pip install tensorflow numpy nltk


## Steps to Run the Project 

1. **Mount Google Drive**

Update the data_root variable to the correct path where intents.json is located in your Google Drive.

2. **Load Required Libraries**

The necessary libraries such as nltk, numpy, and tensorflow are imported.

3. **Load the Dataset**

The intents.json file is parsed to extract patterns, responses, and corresponding tags.

4. **Preprocess the Data**

- Tokenize and lemmatize text.

- Create a Bag of Words (BoW) representation.

- One-hot encode class labels.

5. **Train the Neural Network**

- A feedforward neural network with dropout is used.

- Train the model on the preprocessed data.

6. **Interact with the Chatbot**

Use the chatbot in an interactive session. Type your queries, and the bot will respond based on the trained model.

## Customization 
To modify or extend the chatbot:
- Update intents.json with new patterns and responses.
- Retrain the model to include the changes.

## How It Works
1. **Text Preprocessing**
- Tokenizes user inputs and patterns from intents.json.
- Converts text into numerical features using BoW.
2. **Neural Network Training**
- Trains a model on feature-label pairs.
- Predicts the most relevant tag for a given user query.
3. **Response Generation**
- Matches the predicted tag to the appropriate response from intents.json.



For a detailed explanation of each step and the fundamentals, read the complete blog: [Python Chatbot Project-Learn to build a chatbot from Scratch](https://www.projectpro.io/article/python-chatbot-project-learn-to-build-a-chatbot-from-scratch/429)

Feel free to fork this repository, raise issues, or submit pull requests to enhance the project!

