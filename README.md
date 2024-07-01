# Diabetes Prediction using SVM

## Overview
This project aims to predict diabetes using a Support Vector Machine (SVM) model. The dataset used for training and testing the model includes various health indicators such as glucose level, blood pressure, and BMI.

## Dataset
The dataset for this project can be found on [Kaggle](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database). Ensure you download and place the dataset in the appropriate directory before running the notebook. The dataset is also uploaded in the GitHub repository for easy access.

## Google Colab
You can also run the project in Google Colab using [this link](https://colab.research.google.com/drive/1r5CjzPlNz2LS6h5EKAxKnpCif768UAPI?usp=sharing).

## Prerequisites
Ensure you have the following dependencies installed:

- Python 3.x
- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- Jupyter Notebook

You can install the necessary packages using the following command:
```bash
pip install numpy pandas scikit-learn matplotlib notebook
```

## Results
The Support Vector Machine (SVM) model was evaluated using the Pima Indians Diabetes Database. The results of the model were measured using the following metrics:

- **Accuracy**: The ratio of correctly predicted instances to the total instances.
- **Precision**: The ratio of correctly predicted positive observations to the total predicted positives.
- **Recall**: The ratio of correctly predicted positive observations to all the observations in the actual class.
- **F1-score**: The weighted average of Precision and Recall.

### Model Performance
| Metric     | Score  |
|------------|--------|
| Accuracy   | 0.78   |
| Precision  | 0.75   |
| Recall     | 0.70   |
| F1-score   | 0.72   |

The model's performance indicates a good balance between precision and recall, making it a reliable classifier for predicting diabetes.


## Contributing
We welcome contributions to enhance the performance and functionality of this diabetes prediction project. Here’s how you can contribute:

1. **Fork the Repository**: Click on the "Fork" button at the top right of the repository page to create a copy of the repository on your GitHub account.

2. **Clone the Repository**: Use the following command to clone the repository to your local machine:
    ```bash
    git clone https://github.com/hallowshaw/Diabetes_Prediction_using_SVM.git
    cd Diabetes_Prediction_using_SVM
    ```

3. **Create a New Branch**: Create a new branch to work on your contributions:
    ```bash
    git checkout -b feature-branch
    ```

4. **Make Your Changes**: Implement your changes or improvements in the new branch.

5. **Commit Your Changes**: Commit your changes with a descriptive commit message:
    ```bash
    git commit -m "Add detailed description of changes"
    ```

6. **Push to GitHub**: Push your changes to your forked repository:
    ```bash
    git push origin feature-branch
    ```

7. **Submit a Pull Request**: Go to the original repository on GitHub and submit a pull request. Provide a clear description of your changes and why they should be merged.

8. **Review Process**: Your pull request will be reviewed by the project maintainers. You may be asked to make additional changes before your contribution is merged.

Thank you for your contributions!

