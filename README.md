# ByteVerse

### Team: The Outliers
- Sarah Jane Topno
- Akanksha Gupta
- Subhoshri Pal
- Vaibhav Singh

## Unveiling Legal Insights: A Machine Learning Project on FIR Data Analysis
This project dives into the potential of machine learning in extracting valuable legal insights from FIR data. This README document provides an overview of the model, the objectives we have tackled, its features, and why it's an essential tool for the theme of law and justice.

## Objectives
- The primary objective is to develop a state-of-the-art (SOTA) model that can automatically process FIR images and identify the applicable IPC sections.
- Analyse the textual content within the FIR image to pinpoint the relevant sections of the Indian Penal Code (IPC) associated with the reported crime.

## Why the Law and Justice Theme?
The choice to focus on the law and justice topic stems from the vital role FIRs play in the legal system. FIRs form the basis for criminal investigations and judicial procedures. However, manual review of FIR papers can be time-consuming, causing delays in justice delivery.

We hope to address these difficulties by integrating machine learning and AI approaches to FIR analysis, thereby improving the legal system's efficiency and effectiveness. Our solution provides law enforcement authorities and legal experts with sophisticated capabilities for processing and extracting insights from FIRs, allowing for fair and timely administration of justice.

## Steps For Analysis
### 1. Text Extraction
We used the Tesseract OCR API and Pytesseract to extract text from images and store the output in a file.
   
### 2. Text Analysis
The spaCy library was used to analyze the text. Then the ‘en_blackstone_proto’ model was utilized to extract legal keywords from the extracted text.

### 3. Text Classification
The PySpark library to classify recognized keywords into crime categories. 

## Tech Stack:
1. Python
2. Pandas library
3. Numpy library
4. Tesseract OCR model
5. pytesseract library
6. spaCy library
7. PySpark library
8. en__blackstone_proto model

##Installations
1. tesseract ocr model
2. pytesseract library
3. en__blackstone_proto model
4. spaCy libray
5. PySpark library
   ** Everything was installed using the 'pip' command**

## This project was built before but has been enhanced during this hackathon
We used the PySpark library and implemented our third objective, i.e., classifying the keywords into crime categories.
The first two objectives were made in a previous project.



