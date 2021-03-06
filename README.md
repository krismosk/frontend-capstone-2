# ToneSense

## Introduction
ToneSense is a React web app that allows a user to enter in a sentence and receive a sentiment analysis result from a Machine Learning Model. This repository contains the source code for the React web app.

The app is integrated with two versions of a [Flask RESTful API.](https://github.com/krismosk/backend-capstone-2) The user is able to toggle between the first version (utilizing pre-trained Google NLP API model) and the second version (utilizing a fine-tuned Naive Bayes Classifier model).

The user will be able to interact with a machine learning model by submitting a sentence and receiving a result of "likely positive", "likely neutral", or "likely negative" (if Google NLP API option is toggled). If the Naive Bayes Classifier option is toggled, the user will see only "likely positive" or "likely negative" because the Naive Bayes Classifier was fine-tuned with binary classification. Both versions return suggested emojis to include along with the user's message to match it's tone.

Deployed with [Google Firebase.](https://capstone-1577215364656.firebaseapp.com/)

### Installation
1. Clone this repository.
2. Checkout master branch.
3. Install dependencies with `npm install`.
4. Start server with `npm start`.
5. To interact with the server-side Flask API, follow the installation instructions in the [corresponding repository.](https://github.com/krismosk/backend-capstone-2)

### Demo
[![ToneSense Demo](http://img.youtube.com/vi/cTv0F3Z7DK4/0.jpg)](http://www.youtube.com/watch?v=cTv0F3Z7DK4 "ToneSense Demo")

ToneSense is developed by Kristina Moskalets as a capstone project for [Ada Developers Academy](https://adadevelopersacademy.org/).
