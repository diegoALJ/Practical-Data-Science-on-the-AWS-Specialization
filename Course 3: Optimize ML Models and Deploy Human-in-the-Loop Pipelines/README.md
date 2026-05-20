# Course 3: Optimize ML Models and Deploy Human-in-the-Loop Pipelines

This folder contains the notebooks and learning materials completed as part of **Course 3: Optimize ML Models and Deploy Human-in-the-Loop Pipelines**, from the **Practical Data Science on the AWS Cloud Specialization**, offered by **DeepLearning.AI** and **AWS** through **Coursera**.

This course focuses on improving machine learning models after the initial training and deployment stages. The main topics include hyperparameter tuning, model evaluation, advanced deployment strategies, A/B testing, model monitoring, and human-in-the-loop workflows.

The course continues with the sentiment classification use case and shows how AWS services can be used to optimize model performance, compare deployed models, monitor predictions, and use human feedback to improve future training data.

## Course Overview

The course explores how to move from a trained model to a more reliable and production-oriented machine learning system.

It starts with automatic hyperparameter tuning for a BERT-based text classifier, then introduces deployment strategies such as A/B testing and model monitoring, and finishes with a human-in-the-loop pipeline using Amazon Augmented AI and Amazon SageMaker Ground Truth.

Overall, this course is mainly about improving model quality, reducing operational risk, and using human review when model confidence is low or additional labeled data is needed.

## Main Topics Covered

- Hyperparameter tuning with Amazon SageMaker
- Automatic Model Tuning
- BERT/RoBERTa-based sentiment classification
- PyTorch training jobs in SageMaker
- Model evaluation and candidate comparison
- Advanced model deployment
- A/B testing for deployed models
- Model monitoring and drift detection
- Amazon SageMaker Hosting
- Amazon Augmented AI
- Amazon SageMaker Ground Truth
- Human review workflows
- Private human workforces with Amazon Cognito
- Human task UI creation
- Data labeling for model improvement
- Preparing reviewed data for retraining

## Course Structure

| Week | Topic | Summary |
|---|---|---|
| Week 1 | Advanced Model Training, Tuning, and Evaluation | Applied automated hyperparameter tuning to improve a BERT/RoBERTa-based sentiment classifier. The lab used Amazon SageMaker Hyperparameter Tuning Jobs to configure training parameters, launch tuning experiments, compare candidates, evaluate the best model, and inspect processed outputs. |
| Week 2 | Advanced Model Deployment and Monitoring | Covered more advanced deployment practices, including A/B testing, model performance monitoring, and drift detection from baseline metrics. This part of the course focused on comparing deployed model candidates and monitoring model behavior after deployment. |
| Week 3 | Data Labeling and Human-in-the-Loop Pipelines | Built a human-in-the-loop workflow using Amazon Augmented AI. The lab included creating a private human workforce with Amazon Cognito, designing a human task UI, defining a human review workflow, deploying a custom model, triggering human review when prediction confidence was low, reviewing human labels, and preparing new data for retraining. |

## Repository Organization

```text
course_3_optimize_ml_models_human_in_the_loop/
│
├── README.md
├── week_1/
│   ├── notebook.ipynb
│   └── slides.pdf
├── week_2/
│   └── slides.pdf
└── week_3/
    ├── notebook.ipynb
    └── slides.pdf
```
**Note: The Week 2 notebook is not currently included in this repository.**

## Course Link

https://www.coursera.org/learn/ml-models-human-in-the-loop-pipelines

## Certificate

https://www.coursera.org/account/accomplishments/certificate/TCDDWE2U7VJS

## Attribution

This course is part of the Practical Data Science on the AWS Cloud Specialization, offered by DeepLearning.AI and AWS through Coursera.

Course slides and educational materials are credited to DeepLearning.AI and AWS. These materials are included only for educational and non-commercial purposes, following the license terms provided in the course materials.
