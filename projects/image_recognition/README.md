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

You need to install the package the yaml in debain using the command below. This is required only if you want to test the file in yaml format.
I have implemented tool to convert the given csv file into 4 different formats. In case, only 2 formats is required for you, then you can skip this format 
and choose 2 out of remaining 3 formats.

### Command to install yaml package
sudo apt-get install python-yaml

## Data Validation

Data will be validated as per the requirements i.e., 
	
	1. Valid utf-8 characters for the hotel name.
	2. Valid url.
	3. Star rating cannot be negative.
	
	
If any of these requirement is not satisfied, then that particular row will be removed before writing into another format.
	

## Execution Instructions

Modify the object initialization in the file test_fileconvert.py to include the input csv file and output file name without 
any extension, and you can remove any object method call according to your needs as I would all the available methods.
Then, execute the script by simply issuing the following command:

python test_fileconvert.py

