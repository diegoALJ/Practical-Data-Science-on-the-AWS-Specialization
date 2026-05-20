# Course 2: Build, Train, and Deploy ML Pipelines using BERT

This folder contains the notebooks and learning materials completed as part of **Course 2: Build, Train, and Deploy ML Pipelines using BERT**, from the **Practical Data Science on the AWS Cloud Specialization**, offered by **DeepLearning.AI** and **AWS** through **Coursera**.

This course focuses on building a more complete machine learning workflow in AWS. Instead of only training a model, the course shows how to prepare text data, store machine learning features, fine-tune a pre-trained language model, evaluate its performance, and connect the different steps into an end-to-end pipeline using Amazon SageMaker.

The main use case is sentiment classification from customer reviews, using BERT-based NLP models and AWS services designed for scalable machine learning workflows.

## Course Overview

The course builds on the first part of the specialization by moving from individual experiments to a more structured machine learning pipeline.

The workflow starts with raw review text, transforms it into features that can be used by a BERT-based model, stores those features in Amazon SageMaker Feature Store, and then trains a text classifier using a Hugging Face model inside SageMaker. Later, the course introduces model debugging, profiling, evaluation, model registry, and conditional deployment through SageMaker Pipelines.

Overall, this course is mainly about understanding how a machine learning model can be trained and deployed in a more organized, traceable, and production-oriented way.

## Main Topics Covered

- Feature engineering for NLP models
- Amazon SageMaker Processing Jobs
- Amazon SageMaker Feature Store
- Querying and exporting features for model training
- Fine-tuning BERT/RoBERTa-based models
- Hugging Face models in Amazon SageMaker
- PyTorch training jobs in SageMaker
- Model debugging and profiling
- Model evaluation metrics
- SageMaker Pipelines
- Pipeline parameters, steps, caching, and conditions
- Model registration and artifact tracking
- Conditional model deployment based on accuracy
- Real-time endpoint deployment and testing

## Course Structure

| Week | Topic | Summary |
|---|---|---|
| Week 1 | Feature Engineering and Feature Store | Prepared a raw customer review dataset for a BERT-based sentiment classification model. The lab focused on transforming text into model-ready features using a SageMaker Processing Job, storing those features in SageMaker Feature Store, and exporting balanced train, validation, and test datasets. |
| Week 2 | Train, Debug, and Profile a Machine Learning Model | Fine-tuned a pre-trained RoBERTa model for review sentiment classification using PyTorch and Amazon SageMaker Training Jobs. The lab also introduced SageMaker Debugger and Profiler to analyze the training process, inspect model behavior, and generate profiling reports before deploying and testing the model. |
| Week 3 | Deploy End-to-End Machine Learning Pipelines | Built a SageMaker Pipeline to automate the full workflow: data processing, model training, model evaluation, model registration, conditional approval, deployment, and endpoint testing. This lab connected the previous steps into a more production-like pipeline with parameters, artifacts, lineage tracking, and performance-based deployment logic. |

## Repository Organization

```
course_2_build_train_deploy_ml_pipelines_bert/
│
├── README.md
├── week_1/
│   ├── notebook.ipynb
│   └── slides.pdf
├── week_2/
│   ├── notebook.ipynb
│   └── slides.pdf
└── week_3/
    ├── notebook.ipynb
    └── slides.pdf
```

## Course Link

https://www.coursera.org/learn/ml-pipelines-bert

## Certificate

https://www.coursera.org/account/accomplishments/certificate/RZ4UKFCQPSHS

## Attribution

This course is part of the Practical Data Science on the AWS Cloud Specialization, offered by DeepLearning.AI and AWS through Coursera.

Course slides and educational materials are credited to DeepLearning.AI and AWS. These materials are included only for educational and non-commercial purposes, following the license terms provided in the course materials.
