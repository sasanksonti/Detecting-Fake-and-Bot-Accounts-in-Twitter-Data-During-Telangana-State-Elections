# Analyzing Numerical Patterns in Twitter Data: Unveiling Fake and Bot Accounts During Telangana State Elections

## Project Overview
This project aims to detect fake and bot accounts on Twitter during the Telangana State Elections using advanced machine learning and deep learning techniques. The focus is on enhancing the robustness of Online Social Networks (OSNs) against the dissemination of misleading information.

## Features
- Implementation of various machine learning models for fake account detection
- Utilization of deep learning, specifically Artificial Neural Networks (ANN), to improve accuracy
- Comparative analysis of different models to identify the most effective approach

## Models Used
- Logistic Regression
- AdaBoost
- Voting Classifier
- Artificial Neural Network (ANN)
- Random Forest Classifier
- Gradient Boost Classifier
- Multilayer Perceptron
- XGBoosting
- Hyperparameter tuning using Grid Search

## Installation
To run this project, ensure you have Python installed on your system. You can then install the required packages using the provided `requirements.txt` file.

```bash
pip install -r requirements.txt
```

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/fake-account-detection.git
   cd fake-account-detection
   ```
2. Preprocess the data:
   ```bash
   python preprocess.py
   ```
3. Train the models:
   ```bash
   python train.py
   ```
4. Evaluate the models:
   ```bash
   python evaluate.py
   ```

## Project Structure
- `data/`: Contains the dataset used for analysis
- `preprocess.py`: Script for data preprocessing
- `train.py`: Script to train the models
- `evaluate.py`: Script to evaluate the models
- `models/`: Directory to save trained models
- `notebooks/`: Jupyter notebooks for exploratory data analysis
- `requirements.txt`: List of required packages

## Results
The project demonstrates the effectiveness of using ANN and other machine learning models to detect fake and bot accounts with high accuracy and minimal loss. Comparative analysis shows the superiority of deep learning techniques in this domain.

## Contributing
Contributions are welcome! Please fork the repository and create a pull request with your changes.

## License
This project is licensed under the MIT License.

## Contact
For any questions or suggestions, please reach out to [sasank.sonti@gmail.com](mailto:sasank.sonti@gmail.com).
