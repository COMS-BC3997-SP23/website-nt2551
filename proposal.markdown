---
layout: page
title: Project Proposal
permalink: /proposal/
---

# Project Proposal

### Project Mission
The aim of this project is to provide insight for neurodegenerative diseases such as Alzheimer’s.

### Problem and Solution
The lab I’m currently working with has generated a single cell dataset that is composed of gene information using living and dead brain tissue from a sample of patients with various neurodegenerative diseases. This gene data is seen in the form of count matrices, which are extremely large (containing millions of elements), and are thus difficult to extract relevant information from. The goal of this project is thus to utilize different machine learning methodologies in order to determine whether there are any gene markers that have a high association between them.

### Goals and Objectives
Clean up the dataset and narrow it down to the information/genes of interest
Create the neural net using the nnet function in Keras and use over a small subset of the data
Apply neural network to the entire data subset and fine tune parameters
Use K Means Clustering among the entire dataset containing genes of interest
Use Support Vector Machine (svm) among the entire dataset containing genes of interest

### Method
The machine learning portion of this experiment will be done in R, using the keras package and different algorithms in order to see which ones are the best at fitting the data. The three main algorithms that will be tested are using Neural Networks, Support Vector Machine (svm), and K Means Clustering. The neural net was chosen based on the ability to fine tune parameters, as well as for the ability to test using a small subsection of the data, which would allow for more trial testing to be done and thus is a good first method to start with. The final two methods, which are K Means Clustering and SVM were ones that were recommended by the lab, since they have been used on similar datasets in the past and once fine tuned, were good fits for the data of interest.

### Similar Projects
This past summer, I had the opportunity to intern with Pfizer and worked with a similarly large online dataset known as NHANES. That project gave me insight into how to best handle iterating through and trimming down large datasets, which is essential in making sure that information of interest gets properly examined.
