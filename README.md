# Chatbot Project (Rule-Based + Smart NLP)

## Overview

This project contains **two versions of a chatbot**:

- Simple Rule-Based Chatbot
-  Advanced NLP Chatbot

It shows how a basic chatbot can evolve into a smarter system using NLP techniques.



#  SIMPLE CHATBOT

##  Description

A basic chatbot built using Python conditional statements (`if-elif`) that responds to predefined inputs.



##  Features

- Greetings (hi, hello, hey)
- Basic responses
- Help command
- Exit commands (bye, exit, quit)



##  How It Works

The chatbot matches user input with predefined rules.

```python
if user_input in ["hi", "hello", "hey"]:
    print("ChatBot: Hello!")



#  Project 2 — Iris ML Project (Simple + Advanced in one README)
```markdown
#  Iris Classification Machine Learning Project

##  Overview

This project contains **two machine learning models** using the Iris dataset:

-  Simple ML Model (Decision Tree)
-  Advanced ML Model (Random Forest)

---

#  SIMPLE MACHINE LEARNING MODEL

##  Description

A basic classification model using a **Decision Tree Classifier**.


##  Features

- Load Iris dataset
- Basic data exploration
- Train-test split
- Decision Tree model
- Accuracy evaluation


##  Workflow

```python
model = DecisionTreeClassifier()
model.fit(X_train, y_train)
