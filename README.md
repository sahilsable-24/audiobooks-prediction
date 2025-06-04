
# 🎧 Audiobooks Purchase Prediction Using TensorFlow

This project uses a machine learning model built with TensorFlow to predict whether a customer will purchase an audiobook again based on historical behavior. It includes data preprocessing, model training, and evaluation, making it a good beginner-to-intermediate project for those learning machine learning with TensorFlow.

---

## 📁 Project Structure

- `Audiobooks_data.csv` — Raw dataset of audiobook customers.
- `Audiobooks_Preprocessing.ipynb` — Data preprocessing and cleaning.
- `Audiobooks_Machine_Learning.ipynb` — TensorFlow model training and evaluation with detailed comments.

---

## 🧠 Problem Statement

Given a dataset of audiobook customers, the goal is to:
> Predict whether a customer will make another purchase based on previous interactions, reviews, and engagement.

This is treated as a binary classification problem (purchase again: yes or no).

---

## ⚙️ Technologies Used

- Python
- Pandas & NumPy (for data handling)
- TensorFlow (for model building)
- Scikit-learn (for preprocessing and evaluation)
- Jupyter Notebook (for documentation and step-by-step code execution)

---

## 🔄 Workflow

1. **Preprocessing**
   - Remove unneeded columns (like user ID).
   - Normalize feature values.
   - Shuffle and split the dataset into training, validation, and test sets.

2. **Model Architecture**
   - Input layer → Dense (ReLU) → Dense (Sigmoid)
   - Binary cross-entropy loss
   - Adam optimizer

3. **Training**
   - Trained over multiple epochs.
   - Monitored validation loss to avoid overfitting.

4. **Evaluation**
   - Checked performance on unseen test data.
   - Analyzed prediction accuracy.

---

## 📊 Results

The model achieves reasonable accuracy in predicting user behavior, showing the feasibility of using simple feedforward neural networks on structured data.

---

## 🚀 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/sahilsable-24/audiobooks-prediction.git
   cd audiobooks-prediction
   ```

2. Install dependencies:
   ```bash
   pip install numpy pandas scikit-learn tensorflow notebook
   ```

3. Launch the notebooks:
   ```bash
   jupyter notebook
   ```
   Open and run both notebooks in order:
   1. `Audiobooks_Preprocessing.ipynb`
   2. `Audiobooks_Machine_Learning.ipynb`

---

## 📌 Notes

- Dataset is synthetic but reflects real-world behavior patterns.
- This project is inspired by hands-on ML exercises for educational purposes.

---

## 📚 Credits

Created by [Sahil Sable].  
Inspired by data science exercises from TensorFlow tutorials.
