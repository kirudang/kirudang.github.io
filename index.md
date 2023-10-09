#  <span style="color: #2471A3;">My highlighted projects in data science and MLOps.</span>

---
## 📘 MLOPs
---
### ✨ Salary Prediction Application

This application predicts the salary of software engineers based on key pieces of information. It features two sections: a prediction page for salary prediction and an exploration page for EDA insights from the dataset. The predictions are generated using an **XGBoost model**, while the web app is built on **Streamlit** framework. To ensure the reproducibility, **virtual environments** are utilized on local hosts and contained by **Docker**. This app is deployed on **GCP** as well. A video guide on how to use the application is also available.

<video src="https://user-images.githubusercontent.com/91911269/232245448-62de1f12-1262-4efa-878b-150b9f3d96cc.mp4" controls style="width: 640px; height: 360px;">
</video>

[![](https://img.shields.io/badge/Python-white?logo=Python)](#) [![](https://img.shields.io/badge/Jupyter-white?logo=Jupyter)](#) [![](https://img.shields.io/badge/Streamlit-white?logo=streamlit)](#) [![](https://img.shields.io/badge/Virtual_Enviroment-white?logo=virtualenv)](#) [![](https://img.shields.io/badge/Docker-white?logo=docker)](#) [![](https://img.shields.io/badge/Google_Cloud_Platform-white?logo=googlecloud)](#)

[View code on Github](https://github.com/kirudang/salary_prediction_app)

---
## 📘 Data Science
---
### ✨ Dune Series Network Analysis and Community Detection

This project delves into the captivating "Dune" book series by Frank Herbert using advanced data analysis techniques. By harnessing natural language processing and network science, we uncover the intricate web of character relationships and communities within this iconic science fiction universe.
🔍 **Project Highlights:**
- Utilizes Named Entity Recognition (NER) to extract character and location names.
- Constructs a character relationship graph using NetworkX.
- Applies the Louvain Algorithm for community detection.
- Evaluates community structure with modularity analysis and centrality measures.
![ezgif com-video-to-gif](https://github.com/kirudang/kirudang.github.io/assets/91911269/b5f984fb-d84b-42d6-ae4a-19ac8a32632f)

[![](https://img.shields.io/badge/Python-white?logo=Python)](#) [![](https://img.shields.io/badge/SpaCy-white?logo=SpaCy)](#) [![](https://img.shields.io/badge/NetworkX-white)](#) [![](https://img.shields.io/badge/NER-white)](#) [![](https://img.shields.io/badge/Louvain-white)](#)

[View project on Github](https://github.com/kirudang/Network_analysis_Dune)

---
### ✨ CV and Job Matching

This application predicts the matching percentage of a candidate's resume to a job posting. It utilizes the Doc2Vec model, which represents job descriptions and resumes as numerical vectors. Doc2Vec combines the **Continuous Bag-of-Words (CBOW)** and **Skip-Gram** techniques to efficiently compare and calculate similarity between textual documents. The trained model can be easily deployed and hosted online (**Azure**), providing a convenient solution for matching CVs with job postings.
**Note:** The algorithm serves as the first step in a use-case scenario where a company receives multiple job applications for various job postings. The second step involves employing the modified **Gale-Shapley algorithm** to index candidates for each job and select the best match.



<img width="561" alt="Screenshot 2023-06-11 at 10 17 24 PM" src="https://github.com/kirudang/CV-Job-matching/assets/91911269/93041869-4641-4133-99f9-fd723acc89f5">

[![](https://img.shields.io/badge/Python-white?logo=Python)](#) [![](https://img.shields.io/badge/Jupyter-white?logo=Jupyter)](#) [![](https://img.shields.io/badge/Microsoft_Azure-white?logo=microsoftazure)](#) [![](https://img.shields.io/badge/Doc2Vec-white)](#) [![](https://img.shields.io/badge/Gale--Shapley-white)](#) [![](https://img.shields.io/badge/Beautiful_Soup-white)](#)

[View code on Github](https://github.com/kirudang/CV-Job-matching/tree/main)

---
### ✨ Sales forecasting using SARIMAX (Industry best practices)

This project follows industry best practices to address time series problems and involves key steps such as checking for stationarity, data transformation, decomposing models into components, anomaly detection, white noise checking, identifying orders, and performance measurement. The goal is to provide accurate sales forecasts for Walmart superstore and facilitate data-driven decisions.

<img src="https://user-images.githubusercontent.com/91911269/233193537-c8af8922-d348-4794-93de-1a11a7cc1848.png">


[![](https://img.shields.io/badge/Python-white?logo=Python)](#) [![](https://img.shields.io/badge/Jupyter-white?logo=Jupyter)](#) [![](https://img.shields.io/badge/pandas-white?logo=pandas)](#) [![](https://img.shields.io/badge/scikit_learn-white?logo=scikit-learn)](#) [![](https://img.shields.io/badge/statsmodels-white?logo=statsmodels)](#) [![](https://img.shields.io/badge/ARIMA-white)](#) [![](https://img.shields.io/badge/SARIMAX-white)](#)

[View code on Github](https://github.com/kirudang/Walmart_sales_forecast)

---
### ✨ Automated Text Data Extraction and Form Filling System

This project introduces an innovative solution for automating text data extraction and form filling, aiming to streamline data processing in the digital age. Leveraging a combination of OCR, natural language processing, and rule-based approaches, it offers an **efficient way to extract information from unstructured text and populate forms accurately**, saving time and reducing errors.

🔍 **Project Highlights:**
- Incorporates Optical Character Recognition (OCR) for text recognition.
- Employs Named Entity Recognition (NER) to identify and capture entities.
- Utilizes regular expressions for structured data extraction.
- Integrates rule-based approaches for specific data patterns.
- Offers a hybrid approach combining multiple methods for robust extraction.
- Harnesses large language models (ChatGPT API) for context-aware data extraction.

![Project Preview](https://github.com/kirudang/Automated_Text_Extraction/assets/91911269/86004f85-f431-49b7-8ad5-09f69776e09d)

[![](https://img.shields.io/badge/Python-white?logo=Python)](#) [![](https://img.shields.io/badge/OCR-white)](#) [![](https://img.shields.io/badge/NER-white)](#) [![](https://img.shields.io/badge/RegEx-white)](#) [![](https://img.shields.io/badge/Rule%20Based-white)](#) [![](https://img.shields.io/badge/ChatGPT-white?logo=OpenAI&labelColor=orange)](#)

[View project on Github](https://github.com/kirudang/Automated_Text_Extraction/tree/main)

Feel free to replace `yourusername/yourproject` with the actual URL of your project repository.
---
## 📘 Data Analysis and Business Intelligence
---
### ✨ Walmart Ecommerce Dashboard Project

This project showcases the creation of an interactive Ecommerce Dashboard for Walmart using **Power BI**. The goal was to analyze and visualize key performance indicators (KPIs) to gain insights into sales, revenue, customer behavior, and more. The project followed a structured approach, encompassing defining KPIs, working with raw data in **SQL Server** for efficient manipulation, building SQL queries for validation, connecting Power BI for visualization, and utilizing Power Query for data cleaning. By incorporating calculated measures and time intelligence functions, the dashboard provides a comprehensive overview of Walmart's ecommerce operations. The project follows a **standard pipeline** in BI and DA, starting from database to transformation and visualization.

<iframe width="560" height="315" src="https://www.youtube.com/embed/md89TPyT_lM" frameborder="0" allowfullscreen></iframe>

[![Power BI](https://img.shields.io/badge/Power%20BI-blue?logo=Power-BI)](#) [![SQL Server](https://img.shields.io/badge/SQL%20Server-blue?logo=Microsoft-SQL-Server)](#) [![Power Query](https://img.shields.io/badge/Power%20Query-blue)](#)

[View code on Github](https://github.com/kirudang/Ecom_dashboard_Walmart/tree/main)

---
### ✨ CO2 Emission Data Visualization Dashboard

This interactive dashboard project empowers users to explore and visualize carbon dioxide (CO2) emissions data from Our World in Data. It leverages cutting-edge Python libraries, including **Panel**, **Hvplot**, and **GeoPandas**, to create an intuitive and informative platform for analyzing CO2 emissions worldwide. The dashboard enables users to filter emissions data by year and country, compare emissions trends through scatterplots, and visualize geographical variations on a map. It serves as a valuable tool for gaining insights into the primary driver of global climate change and fostering data-driven discussions around emissions reduction.

<video src="https://github.com/kirudang/kirudang.github.io/assets/91911269/49da9b8f-290c-413e-9dee-ca6b72f45b6c" controls style="width: 640px; height: 360px;">
</video>

[![](https://img.shields.io/badge/Python-white?logo=Python)](#) [![](https://img.shields.io/badge/Panel-white)](#) [![](https://img.shields.io/badge/Hvplot-white)](#) [![](https://img.shields.io/badge/GeoPandas-white)](#)

[View code on Github](https://github.com/kirudang/Interactive_dashboard_Panel)

---


---
## 💻💻💻 Welcome to my portfolio 💻💻💻

Hello! My name is Kiel, and I set up this page to showcase some of the data science projects I've been working on.

Data science practitioner with robust business acumen, boasting 2 professional working years of hands-on experience in data preprocessing and predictive modeling. Expert in SQL, Python, and R, with a track record of success in applying machine learning and statistical analysis to solve complex problems.


My 📋 [CV](https://github.com/kirudang/kirudang.github.io/blob/main/CV/CV-Kiel-Dang.pdf) has plenty of information about the professional projects I've worked on, but the purpose of this page is to showcase some of my favourite personal (on-the-side) projects in a more visual way. 

If you have any questions, feel free to drop me an 📧 [email](mailto:dang.v@northeastern.edu) or send me a message on 🌐 [LinkedIn](https://www.linkedin.com/in/kirudang/). 

Thanks for reading,

**Kiel Dang**


