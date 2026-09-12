# Practical Data Wrangling


Data is essential in data-driven projects, as it forms the foundation for all subsequent analysis, modeling, and decision-making. Depending on the specific task, raw data may be collected from a wide variety of sources such as databases, APIs, sensors, logs, documents, or images. Before it can be effectively used for analysis or machine learning, raw data must be cleaned, transformed, validated, and organized into a consistent and usable format. As data comes in many different forms, including numerical, categorical, time series, text, event/log, and image data, the tools and techniques used for data wrangling can vary significantly depending on the data type and the requirements of the task.

In this workshop, we will cover practical data wrangling techniques for numerical, categorical, time series, text, event/log, and image data. Participants will learn how to detect and handle missing values, outliers, inconsistencies, duplicates, and formatting problems. We will demonstrate methods for transforming and encoding categorical variables, parsing and aggregating temporal data, processing unstructured text, analyzing event logs, and preparing image datasets for machine learning and analytics. Each session combines concepts, demonstrations, and hands-on exercises using realistic datasets to help participants develop practical skills that can be applied immediately in downstream modeling tasks.

This workshop is designed for data practitioners who regularly work with raw or semi-structured data and need to prepare it for analysis or modeling, including data analysts, data scientists, machine learning engineers, and software engineers looking to strengthen their practical data preprocessing skills, as well as researchers and engineers working with real-world datasets who need a structured approach to data cleaning and transformation.



:::{prereq}

- Familiarity with Python basics (lists, dictionaries, loops, functions) and libraries like NumPy, Pandas, and Matplotlib/Seaborn.
- Be familiar with tabular data, rows and columns, missing values, data types, and basic descriptive statistics.
- Have introductory experience using NumPy and pandas for loading, inspecting, filtering, transforming, and summarizing data.
- Elementary understanding of statistics (mean, variance, correlation, basic probability).
- Basic command-line or Jupyter Notebook experience (navigating files, running scripts, installing packages).
:::



:::{toctree}
:caption: Software Setup
:maxdepth: 1

env/0-setting-up
:::



:::{toctree}
:caption: Lesson Episodes
:maxdepth: 1

episodes/1-getting-to-know-your-data
episodes/3-processing-categorical-data
:::
