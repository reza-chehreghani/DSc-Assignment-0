# Data Science Assignment 0: Web Scraping and Data Analysis

This repository contains my work for **Data Science Assignment 0**, which focuses on **web scraping** and **introductory data analysis**. The assignment involves extracting transaction data from the Ethereum blockchain using **Etherscan.io**, performing data cleaning, and conducting statistical analysis and visualization. Below is a detailed explanation of the tasks and the corresponding code in the Jupyter notebook.

## 1. Web Scraping

Using **Selenium** and **Beautiful Soup**, I scraped transaction data from the last 10 blocks on the Ethereum blockchain via Etherscan.io. The data collected includes details such as transaction fees and values, which were then stored in a structured format for further analysis.

## 2. Data Analysis

### Data Cleaning
The scraped data was imported into a **pandas DataFrame**, where I performed data cleaning tasks such as converting data types, handling missing values, and removing irrelevant information. This step ensured the dataset was ready for analysis.

### Statistical Analysis
I calculated the **mean** and **standard deviation** of the transaction values and fees to understand the distribution of the data. This provided insights into the central tendency and variability of the transactions.

### Visualization
To better understand the data, I created several visualizations:
- **Histograms** for transaction fees and values, with explanations for bin size selection.
- **Normal distribution plots** overlaid on histograms to compare empirical data with theoretical distributions.
- **Box plots** and **violin plots** to identify outliers and visualize the spread of the data.

## 3. Data Sampling and Analysis

### Simple Random Sampling (SRS)
I created a sample from the dataset using **simple random sampling**, where each transaction had an equal chance of being selected. This method provided a straightforward way to compare sample statistics with the population.

### Stratified Sampling
I also performed **stratified sampling** by dividing the data into strata based on transaction value. This method ensured that each stratum was represented in the sample, providing a more accurate reflection of the population.

### Comparison of Sampling Methods
I compared the **mean** and **standard deviation** of both sampling methods with the population statistics. Visualizations were used to compare the distributions of transaction values and fees between the samples and the population.

## Notebook Structure
The Jupyter notebook is organized as follows:
- **Web Scraping**: Implementation of data collection from Etherscan.io.
- **Data Cleaning**: Preparing the dataset for analysis.
- **Statistical Analysis**: Calculating mean and standard deviation.
- **Visualization**: Creating histograms, box plots, and violin plots.
- **Sampling**: Implementing simple random and stratified sampling methods.
- **Comparison**: Analyzing and comparing sample statistics with the population.
