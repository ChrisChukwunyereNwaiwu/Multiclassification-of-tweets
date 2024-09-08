### Multiclassification of Tweets Using NLP. 
This project focuses on classifying tweets into multiple categories using Natural Language Processing (NLP) techniques. The project leverages machine learning algorithms and NLP methods to perform multiclass classification, helping to understand and categorize textual data from Twitter.

## Repository Structure
- `Multiclassification_of_tweets.ipynb`: Notebook containing the machine learning model development.
- `README.md`: This README file.
- `requirements.txt`: File listing required Python libraries.
- `CET.json`: The dataset.

## Libraries Used

### Python Libraries

- `numpy`
- `pandas`
- `scikit-learn`
- `matplotlib`
- `seaborn`
- `plotly`
- `xgboost`
- `nltk`
- `jupyterlab`


## Features
-`Data preprocessing`: Cleaning, tokenization, and vectorization of tweets.
-`Feature extraction`: TF-IDF and other vectorization techniques.
-`Model training`: Logistic Regression, Random Forest, and Support Vector Machines (SVM).
-`Performance evaluation`: Confusion Matrix, Accuracy, Precision, Recall, and F1 Score.

## Dataset
The dataset used consists of tweets, each labeled with specific categories. These labels are used to train and test the classification models.


## Instructions

To reproduce the results of this project, follow these steps:

1. **Clone the repository:**
 ```sh
   git clone https://github.com/ChrisChukwunyereNwaiwu/Multiclassification-of-tweets.git
cd Multiclassification-of-tweets
```
   
2. **Install the required libraries:**

#### For Python libraries, run:

```sh
pip install -r requirements.txt
```

## Usage
Run the Jupyter Notebook `Multiclassification_of_tweets.ipynb` to preprocess the data, train the models, and evaluate their performance.

```sh
jupyter notebook Multiclassification_of_tweets.ipynb
```

## Requirements
All dependencies are listed in the `requirements.txt` file for easy installation.

## Results
The trained models are evaluated based on accuracy and other metrics, showcasing how effectively each model can classify tweets into multiple categories.

## Contributing
You can fix the repository and submit pull requests if you have any improvements or additional features you'd like to propose.
