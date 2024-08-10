# Support Vector Regressor

This repository contains an implementation of the Support Vector Regressor (SVR) algorithm. SVR is a type of Support Vector Machine (SVM) used for regression tasks. It aims to find a function that deviates from the actual observed values by a value no greater than a specified margin (epsilon), while simultaneously being as flat as possible.

## Dataset

The dataset used for this implementation is designed for regression tasks, with various features to predict a continuous target variable.

## Contents

- **support_vector_regressor.py**: The main script that implements the Support Vector Regressor, including data preprocessing, model training, and prediction.
- **data.csv**: The dataset file used for training and testing the model.
- **requirements.txt**: A list of Python dependencies required to run the code.

## Implementation Details

The implementation follows these steps:

1. **Data Loading**: The dataset is loaded from `data.csv` and split into features and target variables.
2. **Data Preprocessing**: Preprocessing steps such as feature scaling are applied, which are crucial for SVR as it is sensitive to the scale of input data.
3. **Model Training**: The Support Vector Regressor is trained using the preprocessed data. Key hyperparameters such as the kernel, C, and epsilon are tuned for optimal performance.
4. **Prediction**: The trained model is used to predict continuous values on the test dataset.
5. **Evaluation**: The model's performance is evaluated using metrics such as Mean Squared Error (MSE) and R-squared score.

## Usage

To use this code, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/mazimum86/support-vector-regressor.git
    ```
2. Navigate to the repository directory:
    ```bash
    cd support-vector-regressor
    ```
3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```
4. Run the Support Vector Regressor script:
    ```bash
    python support_vector_regressor.py
    ```

## Dependencies

The following Python packages are required to run the code:

- pandas
- scikit-learn
- numpy
- matplotlib

These dependencies are listed in the `requirements.txt` file and can be installed using `pip`.

## Results

The output includes:

- **Predicted Values**: The continuous values predicted by the model on the test dataset.
- **Evaluation Metrics**: Metrics like Mean Squared Error (MSE) and R-squared score that provide insights into the model's performance.
- **Support Vectors**: Information on the support vectors used by the model, which are critical data points that define the regression function.

## Contributing

Contributions are welcome! If you have any ideas for improvements or additional features, feel free to submit a pull request or open an issue.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
