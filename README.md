# Explainable Boosting Machine (EBM) Breast Cancer Classifier

## Project Overview

This project implements a breast cancer classification model using the Explainable Boosting Machine (EBM) algorithm. EBM is a type of interpretable machine learning model that provides both high accuracy and insights into feature importance. This model is trained on the Breast Cancer dataset, which is used to predict the presence of breast cancer based on various features.

### Key Features:
- **Model Training**: Uses EBM for classification.
- **Model Evaluation**: Evaluates model accuracy on test data.
- **Feature Importance**: Visualizes feature importance to understand key factors influencing predictions.

## Dataset

The model uses the Breast Cancer dataset, which is included with the `scikit-learn` library. This dataset consists of measurements of various features related to breast cancer tumors and is used for binary classification.

## Installation

To run this project, you'll need Python and several libraries. It is recommended to use a virtual environment to manage dependencies. 

### Setup Instructions

1. **Clone the Repository**

    ```bash
    git clone https://github.com/sahilmate/ebm-breast-cancer-classifier.git
    cd ebm-breast-cancer-classifier
    ```

2. **Create and Activate a Virtual Environment**

    ```bash
    python -m venv env
    .\env\Scripts\Activate
    ```

3. **Install Required Libraries**

    ```bash
    pip install -r requirements.txt
    ```

    If `requirements.txt` is not present, manually install the required libraries:

    ```bash
    pip install pandas scikit-learn interpret matplotlib numpy
    ```

## Usage

1. **Run the Jupyter Notebook**

    Open the Jupyter Notebook file included in the repository (`ebm-breast-cancer-classifier.ipynb`) and run the cells to execute the project.

2. **Run the Python Script**

    Alternatively, you can run directly from the command line:

    ```bash
    jupyter nbconvert --to notebook --execute ebm-breast-cancer-classifier.ipynb

    ```

    This will load the dataset, train the EBM model, make predictions, and display the model's accuracy and feature importance plot.

## Output

The script will produce the following outputs:

- **Accuracy**: The accuracy score of the model on the test dataset was : 0.9736842105263158
- **Feature Importance Plot**: A horizontal bar plot showing the importance of each feature in the model.

    ![Feature Importance Plot](https://github.com/sahilmate/ebm-breast-cancer-classifier/blob/master/output.png) 
## Contributing

Contributions to this project are welcome. To contribute:

1. **Fork the Repository**

    Click the "Fork" button on the top right corner of this repository page.

2. **Create a New Branch**

    ```bash
    git checkout -b your-branch-name
    ```

3. **Make Your Changes**

    Edit or add files as necessary.

4. **Commit Your Changes**

    ```bash
    git add .
    git commit -m "Your descriptive commit message"
    ```

5. **Push to Your Fork**

    ```bash
    git push origin your-branch-name
    ```

6. **Create a Pull Request**

    Go to the original repository and click on "New Pull Request." Select your branch and submit the pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- **EBM**: [InterpretML](https://interpret.ml/) for the Explainable Boosting Machine implementation.
- **Dataset**: Scikit-learn's Breast Cancer dataset.

