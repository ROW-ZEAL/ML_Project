# ML_Project

# SMS Spam Classifier

This project is aimed at building a machine learning model to classify SMS messages as either spam or ham (non-spam). The model is trained on a dataset of labeled SMS messages, using a Naive Bayes classifier with TF-IDF vectorization.

## Dataset
The dataset used for this project is the SMS Spam Collection available at [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/sms+spam+collection). It contains a collection of more than 5,000 SMS messages that have been tagged as spam or ham.

## Installation
1. Clone this repository to your local machine:
    ```bash
    git clone https://github.com/yourusername/sms-spam-classifier.git
    cd sms-spam-classifier
    ```
2. Install the required dependencies using pip:
    ```bash
    pip install -r requirements.txt
    ```

## Usage
1. Train the model by running the `train.py` script:
    ```bash
    python train.py
    ```
2. After training, you can use the model to classify new SMS messages. Edit the `predict.py` script to input your own message for classification:
    ```bash
    python predict.py
    ```
3. The output will indicate whether the input message is classified as spam or ham.

## Model Evaluation
The model's performance can be evaluated using metrics such as accuracy, precision, recall, and F1-score. These metrics are calculated during training and printed out at the end of the `train.py` script.

## Files
- `train.py`: Python script for training the SMS spam classifier model.
- `predict.py`: Python script for predicting the label of a new SMS message.
- `requirements.txt`: List of dependencies required to run the project.
- `README.md`: This file providing an overview of the project.

## Future Improvements
- Experiment with different machine learning algorithms and hyperparameter tuning techniques.
- Implement more advanced text preprocessing techniques to improve model performance.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
