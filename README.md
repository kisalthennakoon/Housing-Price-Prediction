# Housing Price Prediction in Districts

This project predicts housing prices in districts using the California housing prices dataset. The model employs pipeline methods and a random forest model for prediction. It also includes cluster similarity algorithms to categorize districts based on geographical location. The parameters for both k-means clustering and random forest are chosen using randomized search CV methods.

## About the Book
This project is inspired by the book "Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow: Concepts, Tools, and Techniques to Build Intelligent Systems" by Aurélien Géron. Many of the logics and codes used in this project are derived from the book's project examples.

## Features
- Predicts housing prices in districts.
- Uses pipeline methods for data processing.
- Employs random forest model for prediction.
- Includes cluster similarity algorithms for district categorization.

## Data Analysis
The project performs data analysis by choosing the training set using stratification based on median income features. This ensures a representative training dataset for accurate model training.

## Dataset
The project uses the California housing prices dataset, which contains a rich set of features and data that can be learned for housing price prediction.

## Model
- Uses pipeline methods for data preprocessing, feature scaling, and model training.
- Chooses the random forest model for prediction, with parameters optimized using randomized search CV methods.
- Includes cluster similarity algorithms, such as k-means clustering, for district categorization based on geographical features.

## Usage
1. Clone the repository: `git clone https://github.com/yourusername/housing-prediction.git`
2. Install dependencies: `pip install -r requirements.txt`
3. Run the Jupyter Notebook to explore the project and make predictions.

## Credits
- Aurélien Géron for the book "Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow: Concepts, Tools, and Techniques to Build Intelligent Systems."
