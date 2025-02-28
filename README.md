# Mine vs Rock Classification using Logistic Regression

## Overview
This project implements a **Logistic Regression** model to classify sonar signals as either **Mines** or **Rocks**. The dataset used contains sonar readings bounced off various surfaces, and the model predicts whether the object is a rock or a mine.

## Dataset
The dataset used is the **Sonar dataset**, which consists of 208 instances and 60 features representing frequency-based sonar signals. The labels are:
- `M` for Mine
- `R` for Rock

## Installation
Clone the repository and install the required dependencies:
```bash
git clone https://github.com/N-Jishnu/Mine-vs-Rock-Logistic-Regression.git
cd Mine-vs-Rock-Logistic-Regression
pip install -r requirements.txt
```

## Dependencies
- Python 3.x
- NumPy
- Pandas
- Scikit-learn
- Matplotlib (for visualization)

## Usage
Run the main script to train and test the Logistic Regression model:
```bash
python mine_vs_rock.py
```

## Features
- **Preprocessing:** Data normalization and train-test splitting.
- **Model Training:** Logistic Regression implementation using Scikit-learn.
- **Evaluation:** Accuracy, Confusion Matrix, and Classification Report.
- **Visualization:** Data distribution and performance metrics plots.

## Results
The model achieves a reasonable accuracy in distinguishing between mines and rocks. Performance metrics such as accuracy, precision, recall, and F1-score are calculated and displayed after execution.

## Contributing
Feel free to fork this repository, raise issues, or submit pull requests for improvements.

## License
This project is licensed under the MIT License.

## Author
[N-Jishnu](https://github.com/N-Jishnu)
