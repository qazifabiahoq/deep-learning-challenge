# Alphabet Soup Deep Learning Model Performance Report

---

## Project Description

This project focuses on developing a deep learning model to predict the success of funding applicants for Alphabet Soup. The objective was to build a model that achieves an accuracy greater than 75% by analyzing various applicant features.

---

## Who Will Benefit and Why

Organizations like Alphabet Soup, which allocate funding based on applicant evaluations, will benefit from this project. Automating and improving prediction accuracy can help streamline decision-making, reduce manual review efforts, and allocate resources more effectively.

---

## Dataset

The dataset includes applicant information with a target variable indicating funding success (`IS_SUCCESSFUL`). It contains multiple features related to the applicants, while irrelevant columns such as `EIN` and `NAME` were removed during preprocessing.

---

## How It Was Done

* **Data Preprocessing:**
  Identified target and features, removed unnecessary columns, encoded categorical data, split into training and test sets, and scaled features using StandardScaler.

* **Model Development:**
  Built several neural networks using TensorFlow and Keras, varying the number of hidden layers and neurons. ReLU activation was used for hidden layers and sigmoid for the output layer. Models were trained and evaluated on accuracy.

* **Optimization Attempts:**
  Tried different binning strategies for rare data occurrences, tested multiple network architectures, and increased training epochs to improve performance.

---

## Key Findings

1. **How accurate were the models?**
   The first model achieved 72.7% accuracy, and the second model scored 72.4%, both slightly below the 75% target.

2. **Did increasing model complexity improve results?**
   Adding hidden layers and neurons provided some insights but did not significantly boost accuracy beyond the initial scores.

3. **What optimizations were explored?**
   Adjusting binning, varying architectures, activation functions, and increasing epochs were tested but showed limited impact on surpassing the accuracy goal.

4. **What skills were demonstrated?**
   The project showcased effective use of TensorFlow and Keras for deep learning model design, training, and evaluation.

---

## Conclusion

The deep learning models developed provided valuable predictive insights into funding success for Alphabet Soup, achieving up to 72.7% accuracy. While the 75% accuracy target was not met, the approach demonstrated solid application of neural network techniques and data preprocessing best practices.

---

## Recommendations

Further improvements could come from fine-tuning hyperparameters, experimenting with more complex architectures, and applying regularization techniques to reduce overfitting and enhance model generalization.

---

# File Structure

* `AlphabetSoupCharity.ipynb`
* `AlphabetSoupCharity.h5`
* `AlphabetSoupCharity_Optimization.ipynb`
* `AlphabetSoupCharity_Optimization.h5`

All files are located in the main project directory. The detailed report is available at the bottom of `AlphabetSoupCharity_Optimization.ipynb`.
