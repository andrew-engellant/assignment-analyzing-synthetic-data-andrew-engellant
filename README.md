# Synthetic Data Analysis

This assignment asks you to analyze a classmate's synthetic data. You're going to 
analyze the data in two different ways: with a regression model and with a tree-based model. 

In both cases you'll estimate the accurracy of the model using the training-test approach
described in lecture. You'll write up both models and post your write-up to the form for
Week 8 on Moodle. The person who created the data set will read your work and tell 
you how good a job the models did uncovering the data generating process. 

## Tasks

1. Download the data posted to Moodle. This file contains all the topics, though you only need to analyze 1.
2. Go to the sign-up [sheet](https://docs.google.com/spreadsheets/d/1WiI-SKpnVmlSC0fGCjLHO0ZZYEHmovoV7ndgPWV2GYs/edit?usp=sharing) and pick your topic. Make sure that all the rows are filled for column `Analyzer n` before you move to `Analyzer n+1` 
3. Build and refine a regression model. Your goal is to make the model that captures your classmate's data generating process. 
4. As part of the modeling process, split the data 80/20 into training and testing data sets. Fit your model on the training data and predict the values for the testing data. Measure your best model's performance.
5. Fit a tree based model using `rpart`. I've included some code from BMIS 326/526 that you can use as a refresher on this technique.
6. Repeat the training/test process for the tree model.
7. Write up your results in an RMD, similar to what you've done the last couple of times. Report the full regression model and the accuracy. Plot and describe the tree model and report the accuracy. Knit to HTML, PDF, or Word. 
8. Post your knitted results to the forum on Moodle at the bottom of the Week 8 page. Let the data creator know you've posted so they can review your work. 

I implore you: read your finished knitted document! By this point in the semester you should be producing reports that look good and are free of typos. 
