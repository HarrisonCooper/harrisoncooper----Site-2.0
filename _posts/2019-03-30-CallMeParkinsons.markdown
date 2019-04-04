---
layout: post
title: Call Me - Parkinsons 
permalink: hackmed19
image: /images/parkinsons.jpg
tags: [Python, Hackathon]
---

Devpost can be found [here](https://devpost.com/software/hackmed19)
Code can be found on GitHub [here](https://github.com/HarrisonCooper/HackMed19)

# Prizes
Winner: Nexmo Sponsor Prize

# The Problem

Design, develop and present a solution to a problem facing the healthcare industry in 24 hours.

Estimated 10 million people suffering with Parkinson’s There are currently no treatments that can stop or slow Parkinson’s disease Catching it early and quickly can improve outcome and quality of life Currently the process of being diagnosed is very slow

# Our Solution

Patients request a call through our online form krupa-17.github.io Patients reply to a short automated phone call - powered by Nexmo The sound file is processed using parselmouth.praat - a python library returning phonetic features We train a model using KNN from data supplied by University of California, Irvine - producing an accuracy of 70% We classify the patients speech against this model, sending the diagnosis and likelihood to their doctor

# The Future

This technology could be used for early diagnosis of parkinson's disease, giving the potential for treatments to be started sooner. This can be rolled out on other devices to a mobile phone, such as an Amazon Alexa skill or Web Application - further increasing accessibility and user base.

# Build With
* Python
* HTML5
* CSS
* Nexmo
* K-Nearest Neighbours ML
