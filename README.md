# 📊 Statistics & Probability Cheatsheet
### A comprehensive guide to descriptive statistics, probability, and distributions

**Welcome!** This repository contains everything you need to understand statistics and probability from first principles. 

---

## 📚 Quick Navigation

* **New to statistics?** → [Start with Overview](#-course-progression)
* **Want a quick reference?** → [Jump to Formulas Cheatsheet](#-formulas-cheatsheet)
* **Ready to code?** → Open the `notebooks/` folder
* **Want real examples?** → [Check Real-World Applications](#-real-world-applications)

---

## 🎯 What You'll Learn

### 1. Descriptive Statistics (1-2)
**8 core concepts** for understanding existing data:
* Mean, Median, Mode (Central Tendency)
* Range, Variance, Standard Deviation (Spread)
* IQR (Outliers)
* Skewness & Kurtosis (Shape)

### 2. Probability Fundamentals (3)
Understanding **likelihood and uncertainty**:
* Basic probability rules (addition, multiplication, complement)
* Conditional probability $P(A|B)$
* Bayes' theorem
* Real-world applications (medical testing, spam detection)

### 3. Probability Distributions (4)
**Three essential distributions** for modeling data:
* Normal (Gaussian) distribution (The 68-95-99.7 rule)
* Binomial distribution
* Poisson distribution

---

## 📁 Repository Structure

```text
statistics-cheatsheet/
├── README.md (you are here!)
├── notebooks/
│   ├── 01_descriptive_statistics.ipynb
│   │   └── 8 concepts, 4 visualizations, complete examples
│   ├── 02_probability_basics.ipynb
│   │   └── Probability theory, Bayes' theorem, real-world problems
│   └── 03_probability_distributions.ipynb
│       └── Normal, Binomial, Poisson with visualizations
├── data/
│   └── sample_data.csv (example datasets for practice)
├── images/
│   ├── descriptive_stats_viz.png
│   ├── distribution_comparisons.png
│   └── (and more visualizations)
└── docs/

# 📊 Statistics & Probability – Course Progression

A structured, hands-on introduction to **Descriptive Statistics and Probability**, designed to build strong foundations for data analysis, machine learning, and real-world decision-making.

---

## 📘 01 Descriptive Statistics Fundamentals
**Concepts:** 8  
**Problems:** 10+

### Objective
Learn how to describe and summarize existing data using statistical measures.

### Topics Covered
- Variables  
- Measures of Central Tendency  
- Measures of Spread  
- Outliers (IQR Method)  
- Shape of Distribution  

### Notebook
📓 `01_descriptive_statistics.ipynb`

### Key Insight
> **Mean ≠ Median when outliers are present. Always check both.**

---

## 📘 02 Real-World Practice & Applications
**Concepts:** Applied  
**Problems:** 20+

### Objective
Apply descriptive statistics to real-world datasets and business scenarios.

### Scenarios
- Customer purchase analysis  
- Manufacturing quality control  
- Salary fairness and pay equity  

### Notebook
📓 `02_probability_basics.ipynb` (Applied Section)

### Key Insight
> **A complete picture = Mean + Median + Standard Deviation**

---

## 📘 03 Probability Fundamentals  
**Concepts:** 3  
**Problems:** 11

### Objective
Understand uncertainty and likelihood using probability theory.

### Topics Covered
- Basic probability rules  
- Conditional probability  
- Bayes’ Theorem  
- Independence  

### Notebook
📓 `03_probability_distributions.ipynb`

### Key Insight
> **A 95% accurate test does NOT mean a 95% chance you have the condition.**

---

## 📘 04 Probability Distributions  
**Concepts:** 3 Distributions  
**Problems:** 9

### Objective
Learn how to model different types of data using appropriate probability distributions.

### Distributions Covered

#### 🔔 Normal Distribution (Continuous)
- Use Case: Heights, exam scores, measurements  
- Rule: **68–95–99.7**
- Parameters: μ (mean), σ (standard deviation)

#### 🎯 Binomial Distribution (Discrete)
- Use Case: Fixed trials (coin flips, email clicks)  
- Mean: `E(X) = n × p`

#### ⏱️ Poisson Distribution (Discrete)
- Use Case: Events over time (calls, defects)  
- Mean: `E(X) = λ`

### Key Insight
> **Choosing the right distribution helps distinguish what is normal from what is unusual.**

---

## 📘 05 Synthesis & Wrap-Up
**Time:** 3.5 hours  

### Deliverable
- A professional statistics portfolio
- Concept integration and preparation for hypothesis testing

---

## 📚 Formula Cheatsheet

### Descriptive Statistics

Mean: Σx / n
Median: Middle value (50th percentile)
Mode: Most frequent value
Range: Max - Min
Variance: Σ(x - mean)² / n
Standard Dev: √Variance
IQR: Q3 - Q1
CV: (Std Dev / Mean) × 100
Skewness: Measure of asymmetry
Kurtosis: Measure of tail heaviness


### Probability

Basic: P(Event) = Favorable / Total
Addition: P(A ∪ B) = P(A) + P(B) - P(A ∩ B)
Multiplication: P(A ∩ B) = P(A) × P(B|A)
Complement: P(Aᶜ) = 1 - P(A)
Conditional: P(A|B) = P(A ∩ B) / P(B)
Bayes: P(A|B) = P(B|A) × P(A) / P(B)


---

## 📊 Probability Distributions

### Normal Distribution

Parameters: μ (mean), σ (std dev)
68% Rule: μ ± σ
95% Rule: μ ± 2σ
99.7% Rule: μ ± 3σ
Z-score: z = (x - μ) / σ

### Binomial Distribution

Parameters: n (trials), p (success probability)
Mean: E(X) = n × p
Variance: n × p × (1 - p)
Std Dev: √[n × p × (1 - p)]
Probability: P(X = k) = C(n,k) × p^k × (1-p)^(n-k)

### Poisson Distribution

Parameter: λ (mean rate)
Mean: E(X) = λ
Variance: Var(X) = λ
Std Dev: √λ
Probability: P(X = k) = (e^(-λ) × λ^k) / k!
    ├── WEEK1_SUMMARY.md (complete synthesis)
    ├── FORMULAS_REFERENCE.md (all formulas in one place)
    └── REAL_WORLD_APPLICATIONS.md (practical examples)
