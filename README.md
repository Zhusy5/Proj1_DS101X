# Exploratory Data Analysis (EDA) Project: What made you happy today?

![image](figs/happy.jpg)

### [Project Description](doc/)
Hi guys, in this project, you are provided with a corpus of 100,000 crowd-sourced happy moments. Your job is to do exploratory data analysis on this text corpus to find out the causes that makes people happy. 

## Introduction

Many things can make one's heart smile with joy. HappyDB is "a corpus of 100,000 crowd-sourced happy moments". Survey participants were given a simple task:

What made you happy today? 

Reflect on the past 24 hours, 
and recall three actual events 
that happened to you that made you happy. 
Write down your happy moment 
in a complete sentence.
(Write three such moments.)
The goal of this project is to look deeper into the causes that make us happy. Natural language processing and text mining are natural tools to derive interesting findings in this collection of happy moments.

## Example Project

+ This example project is conducted by Siyu Zhu

+ Project summary: 

	+ Explore the causes that makes people happy with diffrent visualization methods, such as wordcloud, stacked area graph, heatmap, bigrams, etc.
	+ Used text2vec package to construct a document-term matrix (DTM) from text corpus. Fit a logistic model to build a text classifier for marital status with 83% AUC

+ Then final output is `/output/HappyDB_analysis.html`. And all the source code and Rmd is in the `/doc/HappyDB_analysis.Rmd`.


This folder is orgarnized as follows.

```
proj/
├── lib/
├── data/
├── doc/
├── figs/
└── output/
```

Please see each subfolder for a README file.
