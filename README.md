# SAFE READ: Bangla Content Classification & Recommendation System

**A keyword-based classification system for political, religious, and abusive Bangla content, with recommendations based on age-appropriateness.**

##  Project Overview

The widespread availability of Bangla text content raises concerns over exposing minors to inappropriate material. To address this, **SAFE READ** classifies input text based on keyword-matching into three categories:
-  Religious
-  Political
-  Abusive

 The system then recommends whether the content is suitable for all ages, specific age groups, or adults only.

## Features

-  Keyword-based classification using unigram, bigram, and trigram matching.
-  Recommender logic based on abusive and political keyword frequency.
-  User-friendly **Streamlit** web interface.
-  Efficient Bangla PDF-to-text conversion using `pdf2image` + OCR threading.
-  Built-in dataset and private abusive dictionary.

##  System Workflow

## Dataset Preparation


