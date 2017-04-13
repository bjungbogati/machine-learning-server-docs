---

# required metadata
title: "Quickstarts for MicrosoftML"
keywords: ""
author: "bradsev"
manager: "jhubbard"
ms.date: "04/03/2017"
ms.topic: "get-started-article"
ms.prod: "microsoft-r"
ms.service: ""
ms.assetid: ""

# optional metadata
ROBOTS: ""
audience: ""
ms.devlang: ""
ms.reviewer: ""
ms.suite: ""
ms.tgt_pltfrm: ""
ms.technology: "r-server"
ms.custom: ""

---

# Quickstarts for MicrosoftML

Samples are described and linked here to help you get started quickly using MicrosoftML.

## Breast cancer prediction using rxFastLinear

This starter [breast cancer prediction sample](https://github.com/Microsoft/microsoft-r/tree/master/microsoft-ml/Samples/101/BinaryClassification/BreastCancerPrediction) builds a model to predict breast cancer. It uses the well known Breast Cancer UCI dataset with [`rxFastLinear`]() algorithm provided by the MicrosoftML package.

The type of machine learning task exhibited in this sample is a binary classification problem. Specifically, a given set of cell mass characteristics is used to predict whether the mass is benign or malignant.

## Sentiment analysis using featurizeText

The [Sentiment analysis](https://github.com/Microsoft/microsoft-r/tree/master/microsoft-ml/Samples/101/BinaryClassification/SimpleSentimentAnalysis) sample is a text analytics sample that shows how to use the [featurizeText](microsoftml/packagehelp/featurizetext.md) transform to train a model to predict if a sentence expresses positive or negative sentiments. The type of machine learning task exhibited in this sample is a supervised binary classification problem.

More specifically, the example provided shows how to use the [featurizeText](microsoftml/packagehelp/featurizetext.md) transform in the MicrosoftML package to produce a bag of counts of n-grams (sequences of consecutive words) from the text for classification. The sample uses the [Sentiment Labelled Sentences](https://archive.ics.uci.edu/ml/datasets/Sentiment+Labelled+Sentences) dataset from the UCI repository, which contains sentences that are labeled as positive or negative sentiment.

## Retail churn tutorial

The [Retail churn tutorial](https://github.com/Microsoft/microsoft-r/tree/master/microsoft-ml/Microsoft%20ML%20Tutorial) guides you through the steps for fitting a model that predicts retail churn. Customer churn is an expensive problem in retail. We focus on predicting which customers are likely to churn, but do not address how to prevent customers from churning.

The tutorial imports data from a retail database, creates a label identifying customers who have churned and features based on customer purchase history, fits a model using multiple learning algorithms, and then compares the performance of these fit models to select the best one. 


## Image featurization

TBD

## Run an ML analysis on an Azure Spark cluster

TBD