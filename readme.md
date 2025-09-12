# 📊 Loan Default Risk Analysis

## 📝 Tasks

### Part A – Theory (Short Questions)

1. 📈 Explain **Mean, Median, Mode** in the context of customer income.  
2. 📊 Differentiate between **Standard Deviation** and **Variance** using loan amounts.  
3. 🔢 What is a **Random Variable**? Give one example from the dataset.  
4. 🎲 Explain **Conditional Probability** in terms of loan defaults.  
5. 🧠 Define **Bayes Theorem** and mention how banks can apply it.  
6. 📚 Differentiate between **Empirical Probability** and **Theoretical Probability** with examples.  
7. 🔁 What is a **Poisson Distribution**? Give a business example.  
8. 🧮 Write a short note on **Eigenvalues and Eigenvectors** in data analysis.  

---

### Part B – Practical (Python Programming)

#### 🧮 Step 1: Central Tendency & Dispersion
- 🔍 Find **mean, median, and mode** of `Income`.
- 📏 Calculate **range, variance, and standard deviation** of `Loan_Amount`.

#### 🎲 Step 2: Probability & Events
- ✅ Compute **probability of loan default**.
- 📊 Create a **contingency table** between `Default_Status` and `Credit_Score` (categorized).
- 🔄 Compute **conditional probability**:  
  `P(Default | Credit_Score < 600)`

#### 📉 Step 3: Distributions & Visualization
- 🧮 Plot a **Histogram** of `Credit_Score` with a Gaussian curve.
- 🔄 Check **Skewness** and **Kurtosis** of `Loan_Amount`.
- 📈 Draw a **Q-Q Plot** for `Income`.

#### 📐 Step 4: Linear Algebra Application
Take the first 5 customers’ `[Income, Loan_Amount]` as **vectors**:
- 🟰 Perform **dot product** between two customer vectors.
- 📏 Find **Norm 2** of a customer’s financial vector.
- 📐 Calculate the **angle** between two customers’ vectors.

---

## 🛠️ Tools & Technologies

- 🐍 Python 3.x
- 📦 Libraries: `pandas`, `numpy`, `matplotlib`, `scipy`, `seaborn`
- 📁 Dataset: `loan_applications.csv`

---

## ✅ Learning Outcomes

- 📚 Understand core statistical and probability concepts.
- 🧑‍💻 Apply them using real-world loan application data.
- 📉 Visualize and interpret distributions and relationships.
- 📐 Explore basic **Linear Algebra** in a financial context.
