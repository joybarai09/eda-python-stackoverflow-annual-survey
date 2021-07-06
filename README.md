# EDA-python-stackoverflow-annual-survey

# Project Purpose
Analyzing responses from the Stack Overflow Annual Developer Survey 2020

# Dataset Use
https://www.kaggle.com/aitzaz/stack-overflow-developer-survey-2020

The dataset contains over 64000 responses to 60 questions. 

# Introduction
In this project, analyze the StackOverflow developer survey dataset. The dataset contains responses to an annual survey condected by StackOverflow.

# Special library use
Use as helper library of python, called opendatasets, which contains a collection of curated datasets and provides a helper function for direct download.

# Installation
pip install opendatasets --upgrade 

# Save and upload the work

It is important to save the work from time to time, so that it can be accessed later. or share it online, or with friends and colleagues to let execute the code. Upload this notebook to Jovian.ml account using the jovian Python library. Jovian offers an easy way of saving and sharing Jupyter notebooks online.

# Select suitable project name
project = 'project_name'

# Install the jovian library
!pip install jovian --upgrade

# Save the project
import jovian

jovian.commit(project=project)
