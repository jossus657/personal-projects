# personal-projects

These are my personal works or projects I've contributed to or led. Descriptions for all projects as a directory are listed below. Please reach out (joshuasusanto02@gmail.com) if you have any concerns, I'd love to discuss my work with others!

**1. [Incomplete] [airbnb-listings-analysis] Airbnb Listings Analysis**
  - AB_NYC_2019.csv
  - airbnb-notebook.ipynb
    

**2. [movie-reviews-classification] Machine Learning-Based Sentiment Prediction for Movie Reviews**
   
A project that takes 50,000 IMDb movie reviews and uses various machine learning models to predict the review sentiment. I conducted in-depth analysis on a diverse set of 50,000 IMDb movie reviews, employing advanced NLP techniques for accurate sentiment prediction. I aimed to highlight two different methods in creating a feature dictionary: one utilizing term frequency-inverse document frequency and another using an outside resource in the form of a preset sentiment lexicon dictionary. With these two foundations I systematically compared and contrasted the efficacy of multiple machine learning models on the data, including Logistic Regression, Linear Discriminant Analysis (LDA), Quadratic Discriminant Analysis (QDA), and K Nearest Neighbors (KNN). Multiple different machine learning techniques were implemented to explore and highlight their strenghts, weaknesses, and their most useful scenarios. Doing so allowed me to demonstrate my knowledge of these techniques and proficiency in model selection. Additionally, I rigorously evaluated model performance through comprehensive classification reports and computation time analyses, highlighting a results-oriented approach and commitment to delivering impactful insights.

**Contains:**

  - imdb-reviews.ipynb
  - positive-words.txt (https://www.kaggle.com/datasets/nltkdata/opinion-lexicon)
  - negative-words.txt (https://www.kaggle.com/datasets/nltkdata/opinion-lexicon)


**3. [system-inefficiencies-datafest] ASA DataFest 2023: Analyzing System Inefficiencies Within Client Inquiries**

In this project I led a team in analyzing a large dataset from the American Bar Association (ABA) with the objective of identifying systematic inefficiencies in request processing. Due to privacy reasons, no code nor data can be pubicly accessed, but I'm happy to highlight my processes and contributions. I am only allowed to share the final concise slides used to present our findings to a panel of judge. While doing exploratory analysis I initially noticed large discrepancies in processing times, I was able to successfully identified key bottlenecks in the organization’s request processing, leading to actionable recommendations for improving efficiency. This was done by employing Non-negative Matrix Factorization (NMF) and other NLP tools to uncover patterns and latent features in the dataset, contributing to a deeper understanding of underlying structures. 

**Contains:**

- C10Boolean_Busters.pdf


**4. [code-samples] Other Coding Samples**

**Contains:**

- code_sample1.rmd


**5. [fingerhut-consultation] Fingerhut Consultation: Modeling Customer Behavior and Optimizing 'The Journey System'**

This is a team consultation project done for the Fingerhut retail company as a senior capstone project. We were given a large dataset highlighting a customer's 'journey' or intermediate steps of their time using their product platform. 'fingerhut-consultation-first-looks.Rmd' contains my intial exploration and progress of the dataset, while 'fingerhut-consultation.ipynb' is the notebook my team and I used to complete all of our analysis/modeling. In this project my team and I were able to predict customer journey successes and analyzed what factors are the most important in customer behavioral modeling. We were able to present our work to the company and provide actionable insights for website and user interface improvement. 

**Contains:**

- fingerhut-consultation-first-looks.Rmd
- fingerhut-analysis.ipynb
- final-notebook.ipynb


**6. [audit-logs-technical-interview] Streamlining Data Log Efficiency using Theoretical Lot Audits**

Project Overview:
This project involved analyzing a dataset from a fabric inventory system audit. The dataset consisted of information about fabric lots, including their lot numbers, stock pieces, and adjustments made by warehouse and administrative staff. The main objective was to identify unique and duplicate lots, provide insights into the auditing process, and develop tools to enhance future audits.

Key Deliverables:

Data Analysis in R: Conducted exploratory data analysis (EDA) in R to gather key insights such as the total number of unique lots, percentage of lots audited, and total adjustments made. Used R Markdown to showcase coding processes and analysis in a well-documented report.

Excel Spreadsheet Enhancements:

Duplicate Detection: Created tools to automatically flag duplicate lots and duplicate audited lots using conditional formatting and formulas. This helped streamline the audit process by allowing the admin team to quickly identify records that had already been audited.

Data Validation: Implemented a validation tool that prevents the entry of duplicate Lot#s, reducing data entry errors and improving system accuracy.

Dynamic Dashboard: Developed a fully automated dashboard that updates dynamically as new data is added, offering key insights into the project’s progress. This dashboard features visuals showing current audit completion status and a project board that lists missing audit logs and automatically updates as audits are completed.

Assumptions and Recommendations: Highlighted assumptions made regarding missing values and standards for complete audits, which were discussed in the R Markdown file for further review.


This project demonstrated a blend of programming expertise in R for data analysis, alongside Excel’s functionality for practical data management and reporting, ensuring a more efficient auditing process for future inventory reviews.


**Contains:**
- audit-logs-eda.Rmd
- audit-logs-eda.pdf
- theoretical-lot-audits-assessmentxlsx.xlsx


**7. [event-marketing-analysis] Analyzing User Data for Actionable Marketing Insights**

This project involved analyzing user and event data to assess patterns in event participation and user engagement. The primary objectives were to explore sign-up rates, identify key trends, and assess the impact of event types (virtual, hybrid, and in-person) on user behavior. 

Key Deliverables:

Data Cleaning and Preparation: Merged user and event datasets, created new variables such as event length and sign-up rates, and addressed potential issues like division by zero. Encoded platform types (mobile/web) and calculated the average platform usage per event to understand platform preferences.

Exploratory Data Analysis: Analyzed sign-up rates, identifying key trends in event size, duration, and sign-up totals. Hybrid and virtual events showed higher average sign-up rates compared to in-person events. Generated histograms and bar charts to visualize distributions of sign-up rates and event characteristics.

Statistical Analysis: Conducted a two-sample t-test to compare sign-up rates between virtual and in-person events. Results suggested a potential difference, though not statistically significant at the 95% confidence level. Performed a similar analysis for platform types, revealing no significant difference between mobile and web sign-up rates.

Time Series Analysis: Analyzed sign-up rates over time, observing an increase in average sign-up rates post-COVID, particularly for hybrid and virtual events.
Created time series plots to show trends in event sign-ups across different platforms and event types.

Recommendations:
Hybrid and virtual events demonstrated higher and more consistent sign-up rates, suggesting a focus on promoting these event types. Additionally, further statistical tests and potential machine learning algorithms could enhance future analysis of event data.

This project showcased proficiency in data analysis, visualization, and statistical testing using R, providing actionable insights into event participation patterns.

**Contains:**
- 2024-06-26_event-engagement-analysis_V01.Rmd


**8. [healthcare-technical-interview] Using Patient Data to Create Visualizations and Draw Conclusions**

This project involved cleaning and analyzing mock patient data, simulating real-world healthcare data challenges. The dataset included patient demographics, medical information, and surgery details, with many fields incomplete or containing errors. The objective was to clean the data, analyze trends, and generate visual insights to inform operational decisions.

Key Deliverables:

Data Cleaning: Merged patient background and surgery datasets using unique patient IDs. Handled missing values, blank fields, and error codes with standardized replacements to improve data consistency. Calculated Body Mass Index (BMI) for patients, removing extreme outliers to maintain data integrity.

Data Validation: Standardized patient IDs and categorized surgeries based on text patterns. Handled ambiguous and missing operation data effectively.

Data Visualization: Created a bar chart visualizing patient age and gender distribution, revealing demographic trends. Developed a follow-up recommendation chart to visualize post-surgery care needs. Automated the handling of multiple follow-up events for each patient. Generated a stacked bar chart to compare surgery durations, providing insights into lip and palate procedure lengths.

Recommendations: Suggested implementing data validation and error-handling systems during data collection to reduce missing or incorrect entries.
Proposed a data pipeline to automate cleaning and formatting, minimizing manual effort and improving processing efficiency.

This project demonstrated proficiency in data cleaning, analysis, and visualization using R, while providing insights to improve patient data management and operational efficiency in healthcare settings.

**Contains:**
- 2024-08-06_healthcare-patient-analysis_V01.Rmd



