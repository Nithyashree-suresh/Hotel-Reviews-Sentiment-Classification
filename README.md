# Sentiment Analysis of Hotel Reviews

## Overview
This project aims to enhance customer satisfaction and brand loyalty in the hospitality industry by performing sentiment analysis on hotel reviews. The goal is to track customer sentiment using machine learning and intervene promptly when necessary to address negative feedback.

## Table of Contents
1. [Introduction](#introduction)
2. [Business Problem Statement](#business-problem-statement)
3. [Proposed Solution](#proposed-solution)
4. [Data Collection](#data-collection)
5. [Text Representation Techniques](#text-representation-techniques)
6. [Model Development](#model-development)
7. [Model Evaluation](#model-evaluation)
8. [Results and Business Outcomes](#results-and-business-outcomes)
9. [Contributing](#contributing)
10. [License](#license)

## Introduction
Team Emotion Analysts developed a sentiment analysis model to track and analyze customer reviews in real-time, enabling prompt responses to negative feedback. This project aims to improve customer satisfaction and loyalty by addressing issues highlighted in reviews.

## Business Problem Statement
Negative feedback in hotel reviews can significantly impact bookings, revenue, and brand loyalty. Fragmented feedback sources delay issue recognition, making timely responses crucial to mitigate customer dissatisfaction.

## Proposed Solution
1. **Real-time Sentiment Analysis Platform:**
   - Aggregates feedback from various channels.
   - Detects negative sentiments using NLP techniques.
2. **Task Force for Rapid Response:**
   - A specialized team addressing feedback immediately to enhance guest satisfaction.
3. **Feedback Loop & Continuous Improvement:**
   - Analyzes response effectiveness and implements targeted improvements.

## Data Collection
- **Data Source:** Hotel Reviews from Booking.com (Kaggle).
- **Dataset Details:**
  - 13,000+ data points from various hotels worldwide.
  - Includes reviewer nationality, stay duration, trip type, and detailed textual feedback.

## Text Representation Techniques
1. **TFIDF (Term Frequency-Inverse Document Frequency):**
   - Highlights important words by reducing the weight of common words.
2. **Bag of Words:**
   - Simple model capturing word frequencies.
3. **nGrams:**
   - Captures sequences of words to understand context.

## Model Development
- The model was developed using contextual text representation techniques and binary classification algorithms to determine if reviews are positive or negative.
- **Algorithms Used:**
  - Logistic Regression
  - Support Vector Machine (SVM)
  - Random Forest

## Model Evaluation
- **Evaluation Metrics:**
  - Precision
  - Recall
  - ROC AUC
- **Best Model:** TFIDF Representation with Logistic Regression showed the highest performance in terms of precision, recall, and ROC AUC.

## Results and Business Outcomes
- **Enhanced Guest Satisfaction:**
  - Boost satisfaction and bookings through proactive feedback resolution.
- **Operational Efficiency:**
  - Streamline feedback handling to reduce response times and operational costs.
- **Data-Driven Continuous Improvement:**
  - Implement targeted service improvements based on feedback analysis.
- **Competitive Advantage:**
  - Gain strategic insights to tailor offerings and differentiate from competitors.

