# PDC Sentiment Analysis Project

## Project Overview
This project was developed for a Parallel and Distributed Computing (PDC) course. It focuses on building an efficient Sentiment Analysis pipeline to classify text into Positive, Neutral, and Negative categories.

## Features
- **Data Preprocessing:** Implemented custom cleaning using Regex and Label Encoding.
- **Feature Extraction:** Utilized TF-IDF Vectorization.
- **Model Benchmarking:** Compared 4 major algorithms:
  - Logistic Regression
  - Multinomial Naive Bayes
  - Linear SVC
  - Random Forest

## Performance Results
The models were tested on a dataset of 50,000 samples.
| Model | Accuracy | Training Time (s) |
| :--- | :--- | :--- |
| **Random Forest** | **96.98%** | 260.7s |
| MultinomialNB | 96.66% | **0.04s** |
| Linear SVC | 96.35% | 2.8s |
| Logistic Regression | 96.23% | 2.5s |

*Observation: While Random Forest achieved the highest accuracy, Multinomial Naive Bayes offered the best efficiency-to-performance ratio.*

## How to Run
1. Clone the repo: `git clone [Your Repo Link]`
2. Install dependencies: `pip install -r requirements.txt`
3. Run the notebook: `PDC Sentiment analysis.ipynb`
