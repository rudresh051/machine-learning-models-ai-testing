# Early Testing Strategies in ML Model Engineering phase (Supervised Learning)


## Understand Machine Learning Model Life cycle stages with online/offline modes

![alt text](image-12.png)

##  How Machine Learning models works in nutshell -Learn terminologies used


1. Two modes: Offline mode (data preparation, model training, validation and testing before production) and Online mode (model serving in production).

2. ML Fundamentals: A model learns patterns from historical data using ML algorithms instead of relying entirely on manually coded rules. It uses learned patterns to predict outputs for new, unseen inputs.

3. Training Phase: Feed valid, representative data to the model. ML algorithms identify patterns and learn relationships between inputs and outputs. Example: House price prediction using square footage, bedrooms, plot size and location.

4. Features (X): Input variables provided to the model (e.g., square footage, bedrooms, location).

5. Label (Y): Expected output (e.g., house price).

6. Training Data: Dataset containing features and their corresponding labels, used to train the model.

7. Validation Data: Separate dataset used to evaluate model predictions and tune the model. Inputs are provided without labels during prediction; actual labels are used for comparison.

8. Two common ML problems: Overfitting and Underfitting, which affect the model's ability to generalize to unseen data.