# Credit Card Fraud Detection

## Project Overview
This project focuses on the detection of fraudulent credit card transactions. By analyzing a dataset of transactions, we built and optimized a logistic regression model to identify patterns indicative of fraud, achieving high accuracy.

## Dataset
The dataset contains 284,807 transactions, with each transaction represented by 30 features. It is sourced from Kaggle and includes both legitimate and fraudulent transactions.

## Project Steps
1. **Data Analysis and Preprocessing**
    - Loaded and explored the dataset.
    - Handled missing values and balanced the dataset using techniques such as oversampling.
    - Scaled features to ensure consistency and improve model performance.
2. **Model Development**
    - Developed and optimized a logistic regression model.
    - Used techniques such as cross-validation to ensure robust performance.
    - Achieved an accuracy of 99.92% in detecting fraudulent transactions.
3. **Data Visualization**
    - Created visualizations to uncover patterns and insights within the data.
    - Used Matplotlib to visualize model performance and key findings.
4. **Documentation**
    - Documented the entire process, including data preprocessing, model evaluation, and findings.
    - Compiled results and insights into a comprehensive report.

## Requirements
- Python 3.x
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/Ayesha-Taranum/Credit-Card-Fraud-Detection.git
    ```
2. Navigate to the project directory:
    ```bash
    cd credit-card-fraud-detection
    ```
3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

## Usage
1. Run the Jupyter notebook to execute the project:
    ```bash
    jupyter notebook
    ```
2. Open `credit_card_fraud_detection.ipynb` and run the cells to see the analysis and model development process.

## Results
- The logistic regression model achieved an accuracy of 99.92%.
- Visualizations and insights are documented in the Jupyter notebook and the final report.

## Contributing
Contributions are welcome! Please fork the repository and create a pull request with your changes.

## License
This project is licensed under the MIT License. See the `LICENSE` file for more details.
