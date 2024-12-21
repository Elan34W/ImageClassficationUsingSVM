# Ship Detection in Satellite Imagery Using SVM

This project focuses on detecting ships in satellite imagery using a custom implementation of Support Vector Machines (SVM). The dataset contains labeled satellite images, and the project explores multi-class classification with classes such as `land`, `partial_ship`, `hard`, and `ship`.

---

## Dataset

The dataset used for this project is from Kaggle:  
[Ships in Satellite Imagery](https://www.kaggle.com/datasets/rhammell/ships-in-satellite-imagery/data?select=scenes)  

It contains 80x80 RGB satellite image chips labeled with the presence or absence of ships.

---

## Features

- **Custom SVM Implementation**: Implements SVM with Radial Basis Function (RBF) kernel.
- **Multi-Class Classification**: Uses a One-vs-All approach for multi-class classification.
- **Random Sampling**: Randomly samples balanced data across labels for training and testing.


---

## Requirements

Ensure you have the following Python libraries installed:

- `pandas`
- `numpy`
- `json`
- `matplotlib`
- `scikit-learn`

Install them using pip:

```bash
pip install pandas numpy matplotlib scikit-learn
```

## Hos To Run
1. Clone the Repository
```bash
git clone 
```
2. Download the Dataset
3. Install the Requirements
4. Run the Code
