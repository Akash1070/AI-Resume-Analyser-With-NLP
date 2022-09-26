# **AI Resume Analyser With NLP on Streamlit**

![Python 3.6](https://img.shields.io/badge/Python-3.6-brightgreen.svg)

• Please do ⭐ the repository, if it helped you in anyway.

## Preview
![Click HERE To View](https://github.com/Akash1070/AI-Resume-Analyser-With-NLP/blob/main/Screenshot.png)

## Authors

- [@Akash Kumar Jha](https://github.com/Akash1070)


## Deployment
 
    1. Model Building and Tuning
    2. Building Flask API
   
## Installation

To install the libraries used in this project. Follow the 
below steps:

```bash

#SET UP:

# 1. INSTALL BELOW LIBRARIES

        #pip install -r requirements.txt

        # pip install nltk

        # pip install spacy==2.3.5

        # pip install https://github.com/explosion/spacy-models/releases/download/en_core_web_sm-2.3.1/en_core_web_sm-2.3.1.tar.gz

        # pip install pyresparser

# 2. CREAT A FOLDER AND NAME IT (e.g. resume)

        #2.1 create two more folders inside this folder (Logo and Uploaded_Resumes)
        #2.2 create two python files (App.py and Courses.py)

# 3. START YOUR SQL DATABASE


# 4. CONTINUE WITH THE FOLLOWING CODE...

import streamlit as st
import pandas as pd
import base64,random
import time,datetime
#libraries to parse the resume pdf files
from pyresparser import ResumeParser
from pdfminer3.layout import LAParams, LTTextBox
from pdfminer3.pdfpage import PDFPage
from pdfminer3.pdfinterp import PDFResourceManager
from pdfminer3.pdfinterp import PDFPageInterpreter
from pdfminer3.converter import TextConverter
import io,random
from streamlit_tags import st_tags
from PIL import Image
import pymysql
from Courses import ds_course,web_course,android_course,ios_course,uiux_course,resume_videos,interview_videos
import pafy #for uploading youtube videos
import plotly.express as px #to create visualisations at the admin session
import nltk
nltk.download('stopwords')

```
    
## Running Flask Api

To run tests, run the following command

```bash
  python app.py
```

## 🚀 About Me

Data Scientist Enthusiast | Petroleum Engineer Graduate | Solving Problems Using Data 


# Hi, I'm Akash! 👋


## 🔗 Links
[![github](https://img.shields.io/badge/github-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://github.com/Akash1070)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/akashkumar107/)

## Tech Stack





![Logo](https://businesstoys.in/assets/programs/full-stack-data-science-professional-program/tools.png)
## Other Me
👩‍💻 I’m interested in Petroleum Engineering

🧠 I’m currently learning Data Scientist | Data Analytics | Business Analytics

👯‍♀️ I’m looking to collaborate on Ideas & Data




## 🛠 Skills
1. Data Scientist
2. Data Analyst
3. Business Analyst
4. Machine Learning 


## Future Plans 

⚡️ Looking forward to help drive innovations into your company as a Data Scientist

⚡️ Looking forward to offer more than I take and leave the place better than i found
