## Job Advertisement Data Analysis

---

### Introduction

The project revolves around the analysis, cleansing, and integration of job advertisement datasets. The data is derived from various job hunting platforms. The primary focus is to enhance the user experience on job hunting websites by addressing potential data quality issues and presenting a unified and clean dataset.

### Content

1. **Parsing and Cleansing Data (`task1_2.ipynb`)**
    * Overview of the job advertisement dataset and its significance.
    * Exploration of the XML structure of the dataset.
    * Parsing the XML data into a Pandas DataFrame.
    * Identification of several data quality issues:
      - Typos and spelling mistakes.
      - Irregularities in data values and formats.
      - Integrity violations.
      - Outliers and duplications.
      - Missing values and inconsistencies.
    * Detailed instructions and methodologies for auditing and cleansing the parsed dataset.

2. **Data Integration (`task3.ipynb`)**
    * A detailed introduction to the consolidated job listings dataset.
    * Schema and data level conflict identification:
      - Schema mismatches.
      - Naming conflicts.
      - Data type discrepancies.
      - Missing and inconsistent data values.
    * Steps for examining and loading the secondary dataset.
    * Procedures for resolving identified schema and data conflicts.

### Datasets

1. XML Dataset (`<student_id>_dataset1.xml`): Contains job advertisements with details such as job title, location, company, contract type, salary, and more.
2. CSV Dataset (`<student_id>_dataset2.csv`): An additional set of job listings, which will be integrated with the primary dataset.

### Libraries Utilized

- pandas
- numpy
- re

### Objectives

- Parse job advertisement data from an XML format and store it in a structured manner.
- Identify and rectify potential data quality issues in the parsed data.
- Integrate the primary dataset with an additional dataset to form a comprehensive job listings dataset.
- Address and resolve schema and data level conflicts during data integration.

### Links to Jupyter Notebooks

- [Data Parsing & Cleansing](https://github.com/ayushpatel2002/Job-Data-Analysis/blob/main/s3891013_task1_2.ipynb)
- [Data Integration](https://github.com/ayushpatel2002/Job-Data-Analysis/blob/main/s3891013_task3.ipynb)

### Future Work

- Use the cleaned and integrated dataset for exploratory data analysis.
- Develop a recommendation system for job seekers based on the refined dataset.
- Investigate trends in job markets using time series analysis.

---

For any queries or suggestions, please reach out at [ayushpatel054@gmail.com](mailto:ayushpatel221002@gmail.com).
