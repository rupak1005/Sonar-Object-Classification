# Sonar-Object-Classification
A machine learning project to classify sonar signals as rocks or mines using Logistic Regression.




## Overview
The dataset consists of sonar signals, where:
- **R** represents a signal from a rock.
- **M** represents a signal from a mine.

### Objectives
- Preprocess the data.
- Train a Logistic Regression model.
- Evaluate the model's performance.
- Build a predictive system for new sonar signals.

## Installation
1. Clone the repository:
   ```
   git clone https://github.com/your-username/Sonar-Object-Classification.git
   cd Sonar-Object-Classification```

**2.Install dependencies:**
```
  pip install -r requirements.txt
```
**3.Usage**

Run the Python script:
```
python src/sonar_classification.py
```

**Results**

    Training Accuracy: 98%
    Test Accuracy: 95%

**Sample Prediction**

Input Data: (0.0272, 0.0378, 0.0488, ..., 0.0103)

Output: The object is a Mine

**Confusion Matrix**
![image](https://github.com/user-attachments/assets/808e6a47-4fbc-44f5-a2f4-b1b63ee4b969)


**Contributing**

Feel free to fork the repository and submit a pull request with improvements or suggestions!
