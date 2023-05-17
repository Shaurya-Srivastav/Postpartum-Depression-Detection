# Postpartum Depression Detection

This project aims to predict postpartum depression (PPD) using machine learning techniques. It utilizes a dataset containing various features related to postpartum depression, such as demographic information, medical history, and lifestyle factors.

## Dataset

The dataset used in this project is available in the file `PPDD.csv`. It contains both input features and the target variable (whether an individual has postpartum depression or not). The dataset has been preprocessed and is ready for analysis and model training.

## How It Works

The program follows the following steps to predict postpartum depression:

1. The dataset is loaded and split into input features (X) and the target variable (y).
2. The categorical features in the input data are one-hot encoded to convert them into numerical representations.
3. The dataset is split into training and test sets using the `train_test_split` function from scikit-learn.
4. The input features are standardized using the `StandardScaler` to ensure that all features have the same scale.
5. A machine learning model, in this case, a RandomForestClassifier, is created and trained using the training data.
6. The trained model is used to make predictions on the test set to evaluate its performance.
7. The program prompts the user to provide responses to a set of questions related to the features used for prediction.
8. The user's responses are encoded and scaled using the same preprocessing steps applied to the training data.
9. The model predicts whether the user has postpartum depression based on their responses.
10. The prediction is displayed on the console.

## Dependencies

The following dependencies are required to run the project:

- Python (version >= 3.6)
- pandas
- scikit-learn

You can install the required packages by running the following command:

pip install pandas scikit-learn

## Usage

1. Clone the repository:

   git clone [https://github.com/your-username/postpartum-depression-detection.git](https://github.com/your-username/postpartum-depression-detection.git)|
2. Change into the project directory:

   cd postpartum-depression-detection
3. Run the program:

   python predict_ppd.py

   5. Follow the prompts and provide your responses to the questions asked.

   ## Results

   After you provide your responses, the program will predict whether you have postpartum depression or not based on the trained machine learning model. The prediction will be displayed on the console.

   ## Contributing

   Contributions to this project are welcome. If you have any suggestions, bug reports, or feature requests, please open an issue on the GitHub repository.
