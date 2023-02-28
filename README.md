# linkedin-data-analyst-job-analysis
## Project Description
This project seeks to analyse the data analyst job listings found on LinkedIn. The aim of the jobs analysis is to find hidden insights about data analyst jobs such as what skills are most in demand by employers. Following that, I attempt to implement unsupervised Machine Learning by building a K-Means Clustering model.

The LinkedIn jobs dataset used in this project was obtained on Kaggle: https://www.kaggle.com/datasets/cedricaubin/linkedin-data-analyst-jobs-listings. There are datasets for USA, Canada, and Africa, and I have chosen to solely use the USA dataset 'linkedin-jobs-usa.csv' for this project. Because there are columns such as the 'criteria' column where each observation starts as a list of dictionaries, I had to do quite a bit of data cleaning and manipulation, using techniques such as one-hot encoding, to format and prepare the dataset for exploratory data analysis and K-Means Clustering. 

![Screenshot 2023-02-28 at 10 52 21 PM](https://user-images.githubusercontent.com/97609174/221890085-065e8160-83d1-4ed2-9181-179272c5aedc.png)


The backstory behind this project is that: when I source for internships, I tend to get overwhelmed because there usually is a huge variety of internship jobs offered by many different companies at once on platforms like LinkedIn. Hence, through this project, I want to simplify the internship sourcing process for myself by being able to analyse all the data analyst jobs at a glance and obtain useful insights from them. Though the dataset consists of data analyst jobs in USA rather than Singapore, insights such as what are the skills employers look for are still tranferrable to data analyst jobs in Singapore. The building of the K-Means Clustering model to spot clusters is an add-on to this project that I thought will be fun and interesting, and will allow me to learn more about unsupervised Machine Learning.

Topics covered in this project are:
- Data Mining
- Data Cleaning & Manipulation
- Exploratory Data Analysis
- Data Visualisation
- Unsupervised Machine Learning
- Feature Engineering & Extraction
- Natural Language Processing
