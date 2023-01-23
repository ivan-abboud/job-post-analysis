# job-post-analysis

In this project, we will be analyzing job posts data to gain insights into the **Syrian tech job market**. We will be focusing on identifying patterns and trends in job titles, skills required, and industries. By performing this analysis, we hope to gain a better understanding of the job market and how it is changing over time. We will be using a variety of data science techniques such as data cleaning, data visualization, and statistical analysis to extract meaningful insights from the data. Additionally, we will be using natural language processing **(NLP)** techniques and **ChatGPT** to analyze the text in the job posts, also we will be using computer vision algorithms to extract text from images of the job post and particulary we will use **PaddleOCR**. The goal of this project is to provide valuable insights that can assist job seekers and employers in their job search and hiring process.

## Problem

The problem between job seekers and the job market in the tech industry can be defined as a mismatch between the skills and qualifications that job seekers possess and the skills and qualifications that employers are looking for. In the tech industry, there is a high demand for certain specialized skills, such as programming languages and experience with specific tools and technologies. However, many job seekers may not possess these skills or may not have experience in the specific areas that employers are looking for. This can make it difficult for job seekers to find job opportunities that match their qualifications. Additionally, there may also be a gap in the understanding of what the employer are looking for and what the job seekers have in their resumes. This can lead to job seekers applying for jobs that they are not qualified for and missing out on jobs that they are qualified for.

In this project we will try to minimize the gap between job seekers and employers, by analysing the job market, define the top required titles and skills needed for each title, understand salary range, and job types.

## Content

this project is divided into 6 notebooks, each notebook is a seperate process of analysis. I like to keep notebooks short and simple, it's better than creating a single very long and complex notebook.

### 01 Data Understanding

In this notebook, we will check out the data, understand its structure, take a look at the columns, and finally convert it into a more convenient form suitable for further analysis.

### 02 Extracting Text From Images

we will be using PaddleOCR to extract text from images, PaddleOCR is one of the most accurate open-source projects used for optical character recognition, it can detect and recognize 80+ languages, it supports multiple detection and recognition algorithms and models, and also have very straight forward documentation. Their most significant feature is detecting the text-in-the-wild problem, which is not possible in other OCR systems like Tesseract. <br>
Our problem is considered a text-in-the-wild problem, because the job post advertisement, may have variant designs and structure, so it's not a document, nor a structured image, and paddle-ocr would be the best choice.

### 03 ChatGPT

we will be using ChatGPT API to extract useful details from job post string such as the job title, job type, company name, salary and other info, data is not structured and do not follow any pattern so it's difficult to extract info using simple regex.

### 04 Analyze Job Posts

Analysing ChatGPT responses and try to extract info and convert it into structured form for better analysis and visualization

### 05 Data Formatting

The last step before we continue to our visualization process, here we will clean data for the last time, standarize columns and fill missing values.

### 06 Data Visualization

Here we explore our final data using Plotly for visualization, we will understand data and extract valuable insights that I hope can help job seekers to create their learning road map in order to be ready to enter the job marker.
