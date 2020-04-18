# Image-OCR---Extraction-to-Excel---Workflow
An attempt to automate the process of extracting the transaction details from bank forms and store details in an excel file using Optical Character Recognition using Tesseract engine and PyTesseract library

Initial declaration

Most of the code snippets are sourced from PyImageSearch site and various inputs from stackoverflow. 
The sequencing of the steps and modification for the need of the project was done by me but i am not claiming anything as my original working pure sense
I thank all the experts who have solved the tough problems and were gracious enough to share them in public domain

There is a lot of scope for automated OCR solution which would read data from images of Bank forms and then converting it into an excel file
The objective of this project was to read the images of the bank forms in a folder, extract required fields from the from and then add everything to an excel file

The workflow has 3 steps
Step1 - Standardizing and correcting the errors in the incoming images files - The code does this process in batch (20200110_Image_Standardization_codes_V1.0)
Step2 - Read the standardized images and then extract all data to a set of text files using Tesseract engine and pytesseract library
Step3 - Extract required fields and data elements from text files and consolidate all the input image file data into an excel file

It was an pilot project done to test the knowledge and also the possibilities. It is in no way perfect
Hope somebody can make it perfect and also hope to help and inspire programmers trying Image OCR

