# Naïve Bayes Classifier  

This project contains a **Jupyter Notebook implementation** of the **Naïve Bayes algorithm**, a foundational machine learning technique based on **Bayes’ Theorem**. Naïve Bayes is called "naïve" because it assumes that all features are **independent of each other given the class label** — an assumption that is often unrealistic, but still works surprisingly well in practice.  

It is especially popular in **text classification problems** such as spam detection, sentiment analysis, and document categorization. Despite being simple, it can achieve strong results on real-world data, making it a go-to baseline algorithm for classification tasks.  

---

## 🔑 Key Features  
- Fully implemented in a runnable **Jupyter Notebook**.  
- Demonstrates the core math behind Naïve Bayes as well as usage with **scikit-learn**.  
- Supports different variants of Naïve Bayes:  
  - **Gaussian** (continuous features)  
  - **Multinomial** (text counts, e.g. spam filtering)  
  - **Bernoulli** (binary features, e.g. word present/absent).  
- Step-by-step code walkthrough with examples and predictions.  

---

## ⚙️ How It Works  
Naïve Bayes applies **Bayes’ Theorem**:  

\[
P(C|X) = \frac{P(X|C) \cdot P(C)}{P(X)}
\]

- \( P(C|X) \): Posterior probability of class \( C \) given input \( X \)  
- \( P(C) \): Prior probability of class  
- \( P(X|C) \): Likelihood of input given class  
- \( P(X) \): Evidence (normalizing factor)  

By calculating these probabilities for each class, the model predicts the most likely class label for new data.  

---

## 🌍 Why It Matters in Data Science  
Naïve Bayes has had a **major influence on the field of data science** because:  
- It is one of the **first algorithms taught** to data scientists, providing a foundation in probability-based modeling.  
- It excels in **text mining and Natural Language Processing (NLP)**, which are core areas in data science (spam filtering, sentiment analysis, document tagging).  
- Its simplicity makes it a **baseline model** to compare against more advanced techniques like logistic regression, SVMs, and neural networks.  
- In big data scenarios, Naïve Bayes is valued for its **scalability and efficiency**, often serving as a first-pass filter before applying more complex models.  
- It highlights the balance in data science between **theoretical assumptions (independence)** and **practical performance** on real-world datasets.  

---

## 📂 Project Structure  
```plaintext
├── naive_bayes_notebook.ipynb   # Main notebook (runnable)
└── README.md                    # Project documentation
