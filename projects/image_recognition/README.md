# Data Pipeline Case-Study

## Introduction

The objective is to create a tool that converts given csv data file into 2 different formats. 

## Software Requirements

This project was built and tested on Debian GNU/Linux 9 (stretch) OS with default inbuilt python of version 2.7.13

## Files

### fileformat_conversion.py

This is a python module which will be used as a tool to convert csv file into different format such as xml, html, json, yaml.
We can extend this module to add any new functionality as this was implemented using Object Oriented Programming.

### test_fileconvert.py

This is a standalone script that I developed to test this tool.

## Packages Required(Optional) 

You need to install the package the yaml in debain using the following command. This is required only if you want to test the file in yaml format.
But I have implemented tool to convert the given csv file into 4 formats. Incase if only 2 formats is required for you, then you can skip this format and
choose 2 out of remaining 3 formats.


sudo apt-get install python-yaml

## Data Validation

Data V



## Execution Instructions

Modify the object initialization in the file test_fileconvert.py to include the input csv file and output file name without 
any extension, then execute the script by simply issuing the following command:

python test_fileconvert.py

