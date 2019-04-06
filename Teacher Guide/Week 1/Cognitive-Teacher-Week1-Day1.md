# Cognitive Hackathon: Week 1 - Teacher's Guide
## Day 1

The first day is about exploring what is possible in the world of cognitive computing. The years ahead of us will see astounding growth and change in this area, and the related changes to our culture and commerce are expected to supercede even the Internet. It will be an exciting time ahead and the examples and concepts in this course provide a hint of what is to come. 

Today, demonstrate examples of cognitive computing while introducing the foundational concepts, including machine learning, models, and artificial intelligence. Explore the Azure Cognitive API in all of its facets, with special focus on Computer Vision and Text Analytics.


## Cognitive Computing Demos

These first examples use cognitive Computer Vision capabilities that allow the machine to look at an image and make certain determinations. 

## How Old - Demo

In this first one, it's to guess peoples' age. Now typically that's not polite, particularly in mixed company, but this is for computer science.

    https://www.how-old.net/

Discuss what's going on in this cognitive app. The app must first find the person, so it needs to know what a face looks like, then it draws a rectangle around the face. But sometimes there's more than one face in the frame (show example) so the app must identify two or more faces. Then the app analyzes each face, looking for traits that help it guess the age. We don't know what those traits are exactly but however it's doing it the result is often very close. It's amazing enough that a computer can tell that it's looking at a person, but even moreso that it knows if they're young or old!

## What Dog - Demo

How about creatures other than humans? Like dogs, for instance. Wouldn't it be useful to identify the species or breed of an animal?  What-dog.net does just that:

    https://www.what-dog.net/

Again, the app must know something about the anatomy of what its looking at, likely finding the dog's face, so it can look at things like the shape of the eyes, and the length of the ears and snout. Using pattern recognition to navigate anatomy, the app is  most certainly looking at the color of the dog's fur, and may even identify a tail although it's impossible to know for certain without knowing more about the app.


How does the app know the species of the dogs in those pictures with such accuracy?

## Cognitive Computing Concepts

Cognitive systems use something called machine learning, which allows apps to learn almost like children do, by observing lots and lots of examples. Thousands of dogs are shown to this app, with the species of each dog named to the app, until it compiles an understanding of the traits of each species of dog.  This understanding is stored in a construct called a model.  Cognitive computing is the creation of a model using machine learning then the utilization of that model by the cognitive algorithms to make determinations and recommendations.

Here are those concepts again: (slides or notebook images?)

* Cognitive Computing - use of models created by machine learning to identify and qualify images, speech, text, etc. 
* Machine Learning - the creation of models through the analysis of large amounts of data (often called "Big Data")
* Model - data representation of the computer's understanding of a data set using machine learning, used by cognitive computing APIs and apps to conduct analysis and make complex determinations

In this course we'll be using a cognitive API which contains ready-made machine learning models that your applications can consume using REST APIs. Think of it as a shortcut. There's no need to gather the training data, create a learning algorithm, or train the model. Configuring machine learning systems to analyze large swathes of data to build models could take an entire semester. We will focus on APIs with prepared functionality to give you more time to explore the possibilities of cognitive computing.

So what are these cognitive APIs?

## Cognitive Computing APIs

There are quite a few features in the cognitive API we're working with:

    https://azure.microsoft.com/en-us/services/cognitive-services/directory/

See the tabs up top for our Azure Cognitive Services:

* Vision
* Speech
* Language
* Anomaly Detection
* Search

Each of these tabs contains a group of cognitive APIs: (definitions?)

### Vision
* Computer Vision
* Video Indexer
* Face 
* Custom Vision
* Content Moderator

### Speech
* Speech to Text
* Text to Speech
* Speaker Recognition
* Speech Translation

### Language
* Text Analytics
* Bing Spell Check
* Content Moderator (again)
* Translator Text
* QnA Maker
* Language Understanding

### Anomaly Detection
* Anomaly Detector

### Search
* Bing Web Search
* Custom Search
* Video Search
* Image Search
* Local Business Search
* Visual Search
* Entity Search
* News Search
* Autosuggest

