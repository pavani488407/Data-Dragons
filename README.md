# Data-Dragons
# COVID Crisis Communications -- CovBot


## Contents

1. [Overview](#overview)
2. [Video](#video)
3. [The idea](#the-idea)
4. [How it works](#how-it-works)
5. [Diagrams](#diagrams)
6. [Documents](#documents)
7. [Datasets](#datasets)
8. [Technology](#technology)
9. [Getting started](#getting-started)
10. [Resources](#resources)
11. [License](#license)

## Overview

### What's the problem?
In the pandemic times, design of chatbot can create awareness as well as prevent misinformation, aid in symptom and lessen the mental health burden of pandemic response,provide testing centers around the provided zipcode and the number of effected cases

### Idea/Innovation Opportunity Scenario 

Idea is to design a chatbot which will learn from the user as well as provide all the information to the end user up-to-date 
Learning from the User : Chatbot will assess the behavior pattern of the user by observing the way the questions been asked and will classify the user in to three categories like say panic ,moderate ,safe and will do the necessary science behind the scene on the collected data and will provide accurate data regarding the same to the corresponding government agencies 
Conflict handling : conflicting advice between global and local authorities and misinformation will be amplified in an accurate way .
Data classification : Business insights can be retrieved from the data collected from the chatbot interaction with the user which in turn helps in creating more awareness in the targeted areas (targeted areas can be predicted through applying classification algorithm on data retrieved through chat bot interaction with user) .Insights achieved through data can help government in maintaining testing kits accordingly while distribution and so on


IBM Watson Assistant service helps you build, train, and deploy conversational interactions into any application, device, or channel. Creating a chatbot using Watson Assistant can help address the issues that our users face while trying to gather accurate, relevant information. Whether you're trying to learn the latest news about Covid-19 or learn where there's testing in your area, a chatbot can play a major role in helping communities quickly understand crucial information and free up customer service resources to focus on higher-level issues.

## Video



## Business benefits 

Implementation of chat bot with all the features will reduce the maintenance of several application say coronavirusnearme.com , coronavirusbestpratices.com and so on .. it will act as one stop application which will provide entire source information from symptoms till precautions and with nearby information 
1) Prevents misinformation 
2) Aid in Symptom detection 
3) More business insights can be generated from the data retrieved through the data collected from user while interacting with the bot.
4) Lessens the mental health burden of pandemic response created due to social media news or other medium


## How it works


## Diagrams

### Website integration with COVID-19 crisis communication chatbot

![Crisis Comms Architecture diagram](/Images/Architecture.jpg)

1. User visits a website with the COVID-19 chatbot and asks a question.
2. Node.js web server calls the Watson Assistant service hosted in IBM Cloud.
3. Watson Assistant uses natural language understanding and machine learning to extract entities and intents of the user question.
4. Source COVID-19 FAQ information from trusted CDC data.
5. Watson Assistant invokes an OpenWhisk open source powered IBM Cloud Function.
6. IBM Cloud Function calls the Watson Discovery service running in IBM Cloud.
7. Watson Discovery scans news articles and responds with relevant articles.
8. Watson Assistant invokes an OpenWhisk open source powered IBM Cloud Function.
9. IBM Cloud Function calls the COVID-19 API to get statistics.
10. Watson Assistant replies to the user inquiry.
11. Node.js web server displays the chat answer to the user.


## Datasets

- [covid19api](https://covid19api.com/)

## Technology

### IBM technology

- [IBM Watson Assistant](https://www.ibm.com/cloud/watson-assistant/)
- [Watson Discovery](https://www.ibm.com/cloud/watson-discovery)
- [Watson Speech to Text](https://www.ibm.com/cloud/watson-speech-to-text)
- [Watson Text to Speech](https://www.ibm.com/cloud/watson-text-to-speech)
- [IBM Cloud Functions](https://cloud.ibm.com/functions/)

### Open source technology

- [Node.js](https://nodejs.org/en/)
- [Apache OpenWhisk](https://openwhisk.apache.org/)
- [Node-RED](https://nodered.org/)
