# Handwritten Digit Recognition

A machine learning project that recognizes handwritten digits (0–9) using a **Random Forest** classifier on scikit-learn's built-in digits dataset.

## Dataset
- `load_digits()` – 1,797 images of 8×8 pixels (64 features per image)
- Labels: digits 0 to 9

## How the Code Works
1. **Load data** – Images (`X`) and labels (`y`) are loaded.
2. **Split** – 80% training, 20% testing.
3. **Model** – `RandomForestClassifier` with 100 trees.
4. **Train** – Model learns from training images.
5. **Predict & Evaluate** – Predicts test images and prints accuracy.
6. **Visualize** – Displays one test image with its predicted digit using matplotlib.

## Run
```bash
pip install -r requirements.txt
python Handwritten_Digit_Recognition.py
```

## Sample Output
```
Model Accuracy: ~97 %
Predicted Digit: 6
Actual Digit: 6
```

## Tech Stack
Python, scikit-learn, matplotlib
