# Intelligent-monitoring-of-production-systems
PART OF COURSE IMES,IAM,RWTH.This repository contains the source code, data, and report for our Group 08 project, which analyzes and classifies data from multiple experimental groups using MATLAB and machine learning techniques.

## 📁 Project Structure

```
.
├── Case_Comp.mlx                  # MATLAB live script comparing various cases
├── Data_Comp.mlx                  # MATLAB live script for dataset comparison
├── ProjCode.mlx                   # Main MATLAB code for data preprocessing or analysis
├── Random_forest_classifier.ipynb # Jupyter notebook for Random Forest model
├── IMES_Report_Group-08.pdf       # Final project report
├── MATLAB/                        # Additional MATLAB scripts or utilities
```

## 📊 Description

This project involves:
- Loading and preprocessing data from multiple groups (`G1_Dataset` to `G9_Dataset`)
- Performing statistical comparisons using MATLAB
- Training a **Random Forest Classifier** to classify outcomes
- Testing and evaluating performance on a separate test set

## 🧪 Technologies Used

- MATLAB (.mlx live scripts)
- Python (Jupyter Notebook)
- Scikit-learn (for Random Forest Classifier)
- Pandas, NumPy (data handling in Python)

## 🚀 How to Run

### 1. MATLAB Scripts
Open and run `.mlx` files in MATLAB in the following order (recommended):
- `Data_Comp.mlx`
- `Case_Comp.mlx`
- `ProjCode.mlx`

### 2. Python Notebook
To run the classifier:
```bash
jupyter notebook Random_forest_classifier.ipynb
```

Make sure required Python packages are installed:
```bash
pip install pandas scikit-learn matplotlib
```

## 📄 Report

The full methodology, experiments, and results are available in the [IMES_Report_Group-08.pdf](./IMES_Report_Group-08.pdf).

## 🤝 Contributors

- Group 08 Members, IMES Project
- IAM Lab tutor

## 📃 License

This project is for educational purposes only.
