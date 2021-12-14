# News Headline Topicker - From EDA to Production

## Introduction

This repo is a case study to apply the least minimal steps involved in an end-to-end deep learning project. It is compiled as the capstone project during the ["Machine Learning Zoomcamp"](https://datatalks.club/courses/2021-winter-ml-zoomcamp.html) course.

<br>

## Problem Description

The problem we will study belongs to __Natural Language Processing (NLP)__ subfield of machine learning and the objective of the problem is to predict topic or _'category'_ for a news headline, which makes it a __classification__ problem. The headlines are in English language and classes are pretty diverse (40+ topics).

A successful deep learning model will hopefully recognize the correct category or topic that out of sample news headlines belong to. Such a model can be useful in various situations like:

- When we need to categorize large sum of unlabeled news pieces into proper topics. An example? Organizing old archives.
- When a news agency wants to automatically recommend the topic or tag for a new piece of article being composed on its platform.

<p align="center">
    <img src="./assets/dataset-cover.jpg" width="500" />
</p>

<br>

## About the Dataset

The dataset used in this repo comes in __JSON__ format and is taken from dataset available in [Kaggle](https://www.kaggle.com/rmisra/news-category-dataset). Data is provided in single file and no additional separate test exists. The whole dataset contains __200k+__ samplesin 6 columns, the main ones for us being _'headline'_ and _'category'_.

Regarding the dataset's local availability, it should be noted that is __already provided__ in repo's <mark>__scripts/data__</mark> folder and you don't need to download it separately.

<br>

## Requirements

This entire repo relies on python programming language for demonstrating a deep learning workflow. Deep learning framework of choice for this project is [PyTorch](https://pytorch.org/). Workflow steps are explained and can be run in ["Jupyter Notebook"](https://jupyter.org) documents, allowing us to execute them in an interactive environment. The easiest way to install python and many popular libraries for data science is through setting up [Anaconda](https://www.anaconda.com). You may refer to ``virtual-env`` folder in this repo to review a quick guide on how to setup a virtual environment without running into conflicts with your current setup.
