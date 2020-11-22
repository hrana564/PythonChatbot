[![N|Solid](https://pbs.twimg.com/profile_images/1250694336079167488/tNdu-jYT_400x400.jpg)](https://pbs.twimg.com/profile_images/1250694336079167488/tNdu-jYT_400x400.jpg)
# Python Chat Bot Framework !
[~ By Mayuresh Patil]()

A chatbot is an intelligent piece of software that is capable of communicating and performing actions similar to a human. Chatbots are used a lot in customer interaction, marketing on social network sites and instantly messaging the client. There are two basic types of chatbot models based on how they are built; Retrieval based and Generative based models.

1. Retrieval based Chatbots
A retrieval-based chatbot uses predefined input patterns and responses. It then uses some type of heuristic approach to select the appropriate response. It is widely used in the industry to make goal-oriented chatbots where we can customize the tone and flow of the chatbot to drive our customers with the best experience.

2. Generative based Chatbots
Generative models are not based on some predefined responses.

## How it works

In this Python project with source code, we are going to build a chatbot using deep learning techniques. The chatbot will be trained on the dataset which contains categories (intents), pattern and responses. We use a special recurrent neural network (LSTM) to classify which category the user’s message belongs to and then we will give a random response from the list of responses.

## Prerequisites

The project requires you to have good knowledge of Python, Keras, and Natural language processing (NLTK). Along with them, we will use some helping modules which you can download using the python-pip command.

## Installation

Here are the 5 steps to create a chatbot in Python from scratch:

1) Import and load the data file
2) Preprocess data
3) Create training and testing data
4) Build the model
5) Predict the response

 - Intents.json – The data file which has predefined patterns and responses.
 - train_chatbot.py – In this Python file, we wrote a script to build the model and train our chatbot.
 - Words.pkl – This is a pickle file in which we store the words Python object that contains a list of our vocabulary.
 - Classes.pkl – The classes pickle file contains the list of categories.
 - Chatbot_model.h5 – This is the trained model that contains information about the model and has weights of the neurons.
 - Chatgui.py – This is the Python script in which we implemented GUI for our chatbot. Users can easily interact with the bot.

## Train the Modal
```
python train_chatbot.py
```

## Run the chatbot

```
python chatgui.py
```

# Summary
In this Python data science project, we understood about chatbots and implemented a deep learning version of a chatbot in Python which is accurate. You can customize the data according to business requirements and train the chatbot with great accuracy. Chatbots are used everywhere and all businesses is looking forward to implementing bot in their workflow.
