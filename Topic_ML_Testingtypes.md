# **Machine Learning Testing Types**

| #  | Testing type                       | One-line explanation                                                                                           |
| -- | ---------------------------------- | -------------------------------------------------------------------------------------------------------------- |
| 1  | Data Validation Testing            | Verifies that input datasets have the correct format, schema, quality, and expected values.                    |
| 2  | Data Quality Testing               | Checks for missing values, duplicates, inconsistencies, outliers, and incorrect data.                          |
| 3  | Functional Testing                 | Verifies whether the ML model produces the expected outputs for given inputs.                                  |
| 4  | Model Accuracy Testing             | Measures how accurately the model predicts outcomes using evaluation metrics.                                  |
| 5  | Model Performance Testing          | Evaluates model execution speed, response time, resource consumption, and throughput.                          |
| 6  | Generalization Testing             | Checks whether the model performs well on unseen data, not just training data.                                 |
| 7  | Overfitting & Underfitting Testing | Identifies whether a model memorizes training data or fails to learn underlying patterns.                      |
| 8  | Bias & Fairness Testing            | Checks whether model predictions unfairly favour or disadvantage particular groups.                            |
| 9  | Explainability Testing             | Verifies whether model predictions can be interpreted and explained.                                           |
| 10 | Robustness Testing                 | Checks whether the model handles noisy, unexpected, or slightly modified inputs reliably.                      |
| 11 | Invariance Testing                 | Verifies that irrelevant input changes do not cause unexpected changes in predictions.                         |
| 12 | Consistency Testing                | Checks whether similar inputs produce consistent and logically reasonable outputs.                             |
| 13 | Repeatability Testing              | Verifies whether repeated executions with the same inputs produce consistent results.                          |
| 14 | Privacy Testing                    | Ensures the model does not expose sensitive or confidential training data.                                     |
| 15 | Security Testing                   | Evaluates vulnerabilities such as adversarial inputs, data leakage, and unauthorized access.                   |
| 16 | API Testing                        | Validates model endpoints, request/response structures, status codes, and prediction outputs.                  |
| 17 | Integration Testing                | Verifies that the ML model works correctly with databases, APIs, applications, and other services.             |
| 18 | Latency Testing                    | Measures how long the model takes to generate predictions or responses.                                        |
| 19 | Data Drift Testing                 | Detects changes in the distribution of input data over time.                                                   |
| 20 | Concept Drift Testing              | Detects changes in the relationship between input features and expected outputs.                               |
| 21 | Shadow Testing                     | Compares a new model against an existing production model using the same live traffic without affecting users. |
| 22 | A/B Testing                        | Compares two model versions by exposing different groups of users to each version.                             |
| 23 | Regression Testing                 | Ensures that model updates or code changes do not break previously working functionality or performance.       |
| 24 | Production Monitoring              | Continuously monitors model accuracy, latency, drift, errors, and other production metrics.                    |
| 25 | Sociotechnical Impact Testing      | Evaluates potential negative effects of model behaviour on users and society.                                  |

## **How to group these testing types**

For easier learning, you can organize them into six categories:

| Category                     | Testing focus                                                  |
| ---------------------------- | -------------------------------------------------------------- |
| Data Testing                 | Data validation, data quality                                  |
| Model Testing                | Functional, accuracy, generalization, overfitting, robustness  |
| Responsible AI Testing       | Bias, fairness, explainability, privacy, sociotechnical impact |
| System Testing               | API, integration, performance, latency, security               |
| Change & Reliability Testing | Regression, invariance, consistency, repeatability             |
| Production Testing           | Data drift, concept drift, shadow, A/B testing, monitoring     |
