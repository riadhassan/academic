---
title: 'The way of treatments for different types of data before analysis'
date: 2023-06-08
permalink: /posts/2023/06/different-type-of-data-analysis/
tags:
  - Research
  - Data Science
  - Data Pre-processing
---

Data refers to a collection of facts, statistics, or information that can be processed, interpreted, or analyzed. It can be in various forms, such as numbers, text, images, audio, or video. Data is typically used as input for decision-making, analysis, or research purposes.

Based on different context, we can categorized data. 
- Structured and unstructured
- Qualitative and Quantitative

**Structured Data:** The data which follow a structured manner considered as structured data. like, tabular data (csv, xml, Json etc)

**Unstructured Data:** The data which do not follow any structured manner considered as unstructured data. like, texts in a book.

Data Organization:

- Structured Data: Organized in a predefined structure (e.g., tabular format) with rows and columns representing records and attributes, respectively.
- Unstructured Data: Lacks a predefined structure, can be in the form of text documents, images, audio, or video.

Data Cleaning:

- Structured Data: Handling missing values, duplicates, and outliers using techniques like imputation, deduplication, and outlier detection.
- Unstructured Data: Text cleaning by removing special characters, punctuation, or stop words. Cleaning steps specific to other data types like image resizing or audio filtering may also be required.

Data Transformation:

- Structured Data: Transformations such as scaling numerical features, encoding categorical variables, or creating derived features.
- Unstructured Data: Feature extraction techniques to represent the data in a structured format suitable for analysis. Techniques like bag-of-words, TF-IDF, word embeddings, or topic modeling for textual data. Image processing, audio feature extraction, or video frame extraction for other unstructured data.

Feature Engineering:

- Structured Data: Feature engineering involves creating new features from existing ones or domain knowledge to improve machine learning algorithms.
- Unstructured Data: Feature extraction techniques are typically applied to represent unstructured data in a structured format for analysis. Additional techniques like sentiment analysis or object detection may be used based on the data type.

Dimensionality Reduction:

- Structured Data: Dimensionality reduction techniques like PCA or feature selection methods to reduce the number of features while preserving relevant information.
- Unstructured Data: Dimensionality reduction techniques can be applied after feature extraction to reduce the dimensionality of the extracted features if necessary.

Analysis Techniques:

- Structured Data: Statistical analysis, regression modeling, and other numerical optimization techniques are commonly applied.
- Unstructured Data: Specialized analysis techniques specific to the data type, such as sentiment analysis, text mining, natural language processing, computer vision, or audio processing algorithms.

Additional Processing:

- Unstructured Data: Unstructured data may require additional processing steps specific to the data type, such as image resizing, cropping, audio feature extraction, or video frame extraction.


**Quantitative Data:** This data can be expressed with number and the number contains mathematical significance. Like, student count in class, obtained marks etc.

**Qualitative Data:** : This type of data can be expressed with natural language (text, number....). But those text and numbers have no mathematical significance. Like, Class room number. Room-1 and Room-2 have no mathematical significances. Another example is ZIP code of areas. Addition or average of different areas' zip code have no meaning.

Data Representation:

- Quantitative Data: Quantitative data is numerical and can be represented as continuous (e.g., height, temperature) or discrete (e.g., count, age) values. It can be easily manipulated using mathematical operations.
- Qualitative Data: Qualitative data consists of non-numerical information, such as categories, labels, or textual descriptions. It often represents attributes or characteristics that cannot be measured on a numerical scale.

Data Cleaning:

- Quantitative Data: Cleaning quantitative data involves handling missing values, duplicates, and outliers. Techniques like imputation, mean or median substitution, and outlier detection can be used.
- Qualitative Data: Data cleaning for qualitative data focuses on identifying and addressing missing values, inconsistencies, or errors specific to categorical variables. For text-based qualitative data, cleaning may involve removing punctuation, special characters, or stop words.

Data Transformation:

- Quantitative Data: Quantitative data may require scaling or standardization to ensure comparability among variables with different scales. Other transformations, such as logarithmic or power transformations, may be applied to handle skewed distributions or heteroscedasticity.
- Qualitative Data: Qualitative data often requires encoding or transformation to represent categorical variables numerically. Techniques like one-hot encoding, label encoding, or frequency encoding can be used to convert categorical data into a format suitable for analysis.

Feature Extraction:

- Quantitative Data: Feature engineering in quantitative data often involves creating new features based on mathematical operations, domain knowledge, or data understanding. It may include generating interaction terms, polynomial features, or aggregating information from existing variables.
- Qualitative Data: Feature extraction for qualitative data is typically focused on transforming textual or categorical information into numerical representations. Techniques such as bag-of-words, TF-IDF, word embeddings, or topic modeling can be used to extract meaningful features from text-based qualitative data.

Analysis Techniques:

- Quantitative Data: Quantitative data lends itself well to statistical analysis, regression modeling, numerical optimization, and various mathematical techniques. Statistical assumptions and methods like hypothesis testing, regression analysis, and correlation analysis are commonly used.
- Qualitative Data: Qualitative data is often analyzed using techniques such as sentiment analysis, text mining, content analysis, or topic modeling. These methods aim to uncover patterns, themes, or sentiment within the textual or categorical data.


