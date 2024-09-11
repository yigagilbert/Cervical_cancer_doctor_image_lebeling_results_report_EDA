# Cervical Cancer Image Data Analysis - EDA Project

## Project Overview
This project is part of an assignment for the **MCS 7103: Machine Learning** course. The focus of the project is to perform **Exploratory Data Analysis (EDA)** on a dataset related to cervical cancer images. The dataset contains various labeled attributes provided by medical professionals to aid in understanding the characteristics of the images, though the actual images are not included.

This assignment requires a step-by-step analysis of the dataset, including data wrangling, statistical exploration, and visualization, as well as drawing conclusions from the performed analysis.

## Dataset Information
- **Dataset Name**: Cervical Cancer Image Attributes Dataset
- **Source**: This dataset is part of a project from the organization I am currently working with. The dataset includes various labeled attributes such as image quality, VIA assessments, lesion size, SCJ visibility, etc., which were provided by several medical experts. It does not include the actual images to maintain patient confidentiality and ensure compliance with data protection regulations.
- **Link to Dataset**: [Dataset Link](https://docs.google.com/spreadsheets/d/1Qb841r2Am89Juk48gOzcxEm-e_B8ETN3/edit?usp=sharing&ouid=103595609441443377592&rtpof=true&sd=true)

The dataset consists of 371 rows, each representing an image with its corresponding labeled attributes. Below is a breakdown of the key attributes:
- **Image Quality**: Classification of the image based on visual clarity (e.g., good, poor).
- **SCJ Visibility**: Whether the squamocolumnar junction is fully or partially visible in the image.
- **VIA Assessment**: Results from Visual Inspection with Acetic Acid (VIA) test, categorized as positive or negative.
- **Lesion Size**: The proportion of the cervix area involved in a lesion.

## Objective
The goal of this assignment is to perform detailed **Exploratory Data Analysis (EDA)** on the dataset and gain insights into the relationships between the labeled attributes. We aim to:
1. **Assess Data Quality**: Evaluate missing values and data consistency across attributes.
2. **Analyze Key Variables**: Understand the distribution of image quality, VIA assessments, lesion sizes, and SCJ visibility.
3. **Investigate Correlations**: Examine the relationships between key variables, such as the correlation between image quality and diagnostic suitability or lesion size and VIA results.
4. **Draw Conclusions**: Summarize the insights derived from the data analysis and propose recommendations for further analysis.

## Assignment Requirements
This project was created as part of the following assignment for the **Machine Learning** course:

> **Assignment 1: Exploratory Data Analysis Process**
> 
> The goal of this assignment is to carry out a thorough Exploratory Data Analysis (EDA) process on a dataset, focusing on in-depth data wrangling, statistical exploration, and generating insights based on the data. The EDA report should be at least three pages long and should clearly outline the steps taken during the analysis process.
> 
> ### Steps to be followed:
> 1. Present and answer critical questions before, during, and after the analysis.
> 2. Perform detailed data wrangling to prepare the data for analysis.
> 3. Carry out a comprehensive EDA process using appropriate graphs and visualizations.
> 4. Draw conclusions based on the EDA results.
> 5. Communicate all findings in a well-structured report.

## Repository Structure
- **/notebooks**: Contains Jupyter notebooks with code for data wrangling, EDA, and visualizations.
- **/data**: Contains the dataset (CSV file).
- **README.md**: The current file, which explains the project and dataset.
- **EDA_Report.pdf**: The final report documenting the EDA process and conclusions.
- **Assignment_Details.pdf**: Contains the original assignment question.

## Methodology
The analysis process follows the guidelines provided in the assignment:
1. **Data Wrangling**: Handle missing values, encode categorical variables, and ensure data consistency.
2. **Exploratory Data Analysis (EDA)**: Visualize key features such as image quality distribution, lesion size, and SCJ visibility. Analyze relationships between variables using correlation analysis and bivariate plots.
3. **Conclusion**: Summarize the key findings from the analysis and suggest areas for improvement or further research.

## Results and Conclusions
- Data quality is generally good, with some missing values in critical fields such as lesion size. These should be carefully addressed before applying predictive models.
- There are observable trends between image quality and diagnostic suitability. For instance, higher-quality images are more likely to be deemed suitable for VIA assessments.
- The relationship between lesion size and VIA results needs further exploration, as initial findings suggest that larger lesions tend to result in positive VIA assessments.
  
Further analysis can be done by building predictive models based on the available data, focusing on identifying the factors most strongly associated with VIA-positive diagnoses.

## How to Use
1. Clone this repository.
2. Open the **notebooks** folder and run the Jupyter notebooks to explore the data and reproduce the analysis.
3. The **EDA_Report.pdf** provides a detailed summary of the analysis and conclusions.

## Assignment Details
Please refer to the [assignment question](Assignment_Details.pdf) for more information about the objectives and requirements.
