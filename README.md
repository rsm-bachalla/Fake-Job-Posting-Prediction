# Fake-Job-Posting-Prediction
**Overview**
This project aims to develop a model for identifying fraudulent job listings on online job platforms. The dataset, sourced from Kaggle, comprises 18,000 job descriptions, with over 800 labeled as fake.

**Data Preprocessing**
Employed Natural Language Processing (NLP) techniques such as stopword removal, stemming, and case normalization to clean the data using the bag of words approach.

**Exploratory Data Analysis (EDA)**
Conducted statistical analysis and visualizations to identify common words in fake vs. real job postings.
Analyzed the distribution of job types and identified patterns.
Broke down fake job postings based on experience and employment types, revealing that 78.4% were for full-time jobs, with 179 targeted towards entry-level positions.
Visualized fake job postings across various sectors, highlighting Oil & Energy, Accounting, Health care, and Marketing as industries with a high percentage of questionable postings.

**Geographical Analysis**
Explored the geographical distribution of fake job postings, revealing the USA as the top contributor with 730 instances, followed by Australia.
Houston emerged as the city with the most fake job postings.

**Data Split**
Split the dataset into 95% training and 5% testing sets.

**Model Development**
Employed a Random Forest machine learning algorithm for distinguishing between real and fake job postings.
Achieved an accuracy of 82.8%, indicating that the model can predict whether a job posting is fake with an 83% success rate.
Acknowledged the potential for further improvement using alternative algorithms to enhance accuracy.

**Project Significance**
The model developed can assist online job platforms in automatically identifying and filtering out potentially fraudulent job postings.
Enhances user trust and platform reliability by reducing the presence of fake job listings.
Highlights the importance of leveraging machine learning for fraud detection in online job markets.

**Future Improvements**
Explore alternative machine learning algorithms for potential improvements in accuracy.
Continuously update the model with new data to adapt to evolving patterns of fake job postings.
Feel free to explore the code and findings in this repository. Your feedback and contributions are valuable for ongoing improvements in fake job posting detection
