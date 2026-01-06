DS_Stack

This repository is a hands-on, end-to-end Data Science practice stack designed to simulate the full lifecycle of real-world analytics and machine learning projects — from raw data ingestion through cleaning, visualization, and model building. The intent is to create a structured learning lab that can also evolve into a foundation for production-ready workflows.

Objectives

The Repository focuses on building repeatable and modular data science Tutorials, practising data cleaning and feature engineering, developing visual insights, and training machine learning models in a structured way. It also serves as a reference stack that can be extended over time and demonstrates practical ML skills through clear organization.

Repository Structure

The DS_Stack repository contains several key folders:
The Data folder holds raw datasets and source files.
The Data_Pre-Processing folder contains scripts and notebooks for cleaning data, transforming features, and preparing inputs for modelling.
The Data_Visualization folder is used for exploratory data analysis, charts, and insights.
The ML-Models folder contains machine learning, including all supervised, unsupervised training notebooks and evaluation workflows.
A .gitignore file is included to prevent the unnecessary commit of files or large artefacts.

What’s Inside

The repo walks through core data science concepts in practice. Data handling focuses on managing missing values, removing duplicates, detecting anomalies, encoding categories, and scaling features. Visualization work includes distributions, correlation heatmaps, outlier views, and feature-versus-target analysis to support better decision-making. Machine learning content includes building baseline models, evaluating metrics such as accuracy and F1-score, and testing different algorithms and tuning strategies.

Getting Started

To use this repository, clone it to your local machine and explore each folder in order. You can optionally create a virtual environment and later install dependencies once a consolidated requirements file is added. For now, individual notebooks may have their own library needs.

How to Navigate

Start with the Data folder to understand the datasets. Move next into Data_Pre-Processing to see how raw data is transformed. Use the Data_Visualization folder to understand key patterns and insights, and finally explore ML-Models to see how everything feeds into machine learning workflows. The flow mirrors the same sequence used in most enterprise data projects.

Roadmap

Planned enhancements include adding a requirements file, modularizing scripts into functions and classes, enabling experiment tracking with MLflow, automating pipelines with Airflow or Prefect, deploying a sample model with FastAPI and Docker, integrating CI/CD and testing, and adding data versioning using tools like DVC. These upgrades position the project for more production-style usage over time.

Why This Project Matters

This repository demonstrates the ability to think end-to-end about machine learning systems, manage real datasets in an organized way, and move beyond quick notebooks toward maintainable, scalable workflows. It showcases both foundational technical skills and an understanding of how modern data stacks operate in real organizations.

Contributions

Suggestions, enhancements, and experiments are welcome. Forks, pull requests, and collaboration ideas are encouraged to help continuously improve and expand the stack.
