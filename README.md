
# Support Vector Machine (SVM) Classification Project

## Project Description
This project demonstrates the application of Support Vector Machine (SVM) for classification purposes. The dataset used is `Social_Network_Ads.csv`, which includes user information such as age and estimated salary, along with a target variable indicating the purchase behavior of users. The project implements an SVM classifier with a linear kernel to distinguish between different user purchase behaviors based on their profile data.

## Installation and Setup
To run this project, you need Python installed on your system along with the following libraries:
- pandas
- numpy
- matplotlib
- scikit-learn

You can install these libraries using pip:
```bash
pip install pandas numpy matplotlib scikit-learn
```

## Code Structure
The project is structured as follows:
- **Data Loading**: The dataset `Social_Network_Ads.csv` is loaded into a pandas DataFrame.
- **Data Preprocessing**: The features are extracted, and data is scaled using `StandardScaler` from scikit-learn.
- **Model Training**: An SVM classifier with a linear kernel is trained using the training subset of the dataset.
- **Model Evaluation**: The trained model is evaluated on the test set, and the performance is assessed using a confusion matrix and accuracy score.
- **Visualization**: Training and test set results are visualized to show the decision boundary created by the SVM classifier.

## Usage
To run the project, execute each cell in the Jupyter notebook. Ensure that the dataset `Social_Network_Ads.csv` is located in the same directory as the notebook.

## Results and Visualization
The project provides visualizations of the SVM decision boundaries for both the training and test sets. These visualizations help in understanding how the SVM classifier segregates different classes based on the dataset.

## Additional Notes
- The dataset used in this project is essential for understanding the context and the effectiveness of the SVM classifier.
- The project is a basic demonstration and can be extended further for more complex classification tasks.

## Acknowledgments
This project is part of the learning endeavors in machine learning and data science.
