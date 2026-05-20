# Course 1: Analyze Datasets and Train ML Models using AutoML

This folder contains the notebooks and learning materials completed as part of **Course 1: Analyze Datasets and Train ML Models using AutoML**, from the **Practical Data Science on the AWS Cloud Specialization**, offered by **DeepLearning.AI** and **AWS** through **Coursera**.

This course focuses on the first stages of a practical machine learning workflow in the AWS cloud. The main topics include data ingestion, data exploration, bias detection, feature engineering, automated machine learning, and model training using Amazon SageMaker and related AWS services.

The course uses a customer product reviews dataset as the main use case, with the goal of preparing, analyzing, and modeling text data for sentiment classification.

## Course Overview

The course introduces how to work with datasets in the cloud and prepare them for machine learning workflows. It covers how to ingest and query data using AWS services, analyze class imbalance and bias, train models using automated machine learning, and compare AutoML-based approaches with built-in machine learning algorithms.

The practical labs are focused on natural language processing and multi-class text classification, using customer reviews labeled by sentiment.

## Main Topics Covered

- Data ingestion and transformation using Amazon S3
- Dataset querying with AWS Glue and Amazon Athena
- Exploratory data analysis using AWS Data Wrangler
- Statistical bias detection with Amazon SageMaker Clarify
- Dataset balancing by product category and sentiment
- Automated machine learning with Amazon SageMaker Autopilot
- BERT-based text classification workflows
- Feature engineering and model candidate comparison
- Model deployment and endpoint testing
- Text classification using Amazon SageMaker BlazingText

## Weekly Content

| Week | Topic | Summary |
|---|---|---|
| Week 1 | Explore the Use Case and Analyze the Dataset | Ingested, transformed, queried, and visualized a customer product reviews dataset for multi-class sentiment classification. The lab used Amazon S3, AWS Glue, Amazon Athena, and AWS Data Wrangler to explore review distribution, sentiment labels, product categories, and review text characteristics. |
| Week 2 | Data Bias and Feature Importance | Analyzed potential statistical bias before model training using Amazon SageMaker Clarify. The lab focused on class imbalance, bias reports, and dataset balancing by product category and sentiment to prepare the data for more reliable model training. |
| Week 3 | Automated Machine Learning with SageMaker Autopilot | Used Amazon SageMaker Autopilot to train and compare model candidates for sentiment classification. The lab covered AutoML job configuration, generated notebooks, feature engineering, model training, tuning, candidate comparison, deployment, and model testing. |
| Week 4 | Built-in Algorithms with BlazingText | Trained a text classifier using the Amazon SageMaker BlazingText built-in algorithm. The lab covered dataset preparation, train-validation splitting, S3 upload, model training, deployment as a real-time inference endpoint, and prediction testing. |

## Repository Organization

```
course_1_analyze_datasets_train_ml_models_automl/
│
├── README.md
├── week_1/
│   ├── notebook.ipynb
│   └── slides.pdf
├── week_2/
│   ├── notebook.ipynb
│   └── slides.pdf
├── week_3/
│   ├── notebook.ipynb
│   └── slides.pdf
└── week_4/
    ├── notebook.ipynb
    └── slides.pdf
```

##  Course Link

https://www.coursera.org/learn/automl-datasets-ml-models

##  Certificate

https://www.coursera.org/account/accomplishments/certificate/GT73PGWYJ5TF

##  Attribution

This course is part of the Practical Data Science on the AWS Cloud Specialization, offered by DeepLearning.AI and AWS through Coursera.

Course slides and educational materials are credited to DeepLearning.AI and AWS. These materials are included only for educational and non-commercial purposes, following the license terms provided in the course materials.
