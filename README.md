Statistics & Probability Cheatsheet
A comprehensive guide to descriptive statistics, probability, and distributions

Welcome! This repository contains everything you need to understand statistics and probability from first principles.

📚 Quick Navigation
New to statistics? → Start with Day 1 Overview

Want a quick reference? → Jump to Formulas Cheatsheet

Ready to code? → Open the Jupyter notebooks

Want real examples? → Check Real-World Applications

🎯 What You'll Learn
This repository covers Week 1 of a comprehensive statistics course, including:

1. Descriptive Statistics (Days 1-2)
8 core concepts for understanding existing data:

Mean (average)

Median (middle value)

Mode (most frequent)

Range (spread)

Variance (spread squared)

Standard Deviation (typical deviation)

IQR (interquartile range)

Skewness & Kurtosis (shape)

2. Probability Fundamentals (Day 3)
Understanding likelihood and uncertainty:

Basic probability rules (addition, multiplication, complement)

Conditional probability P(A|B)

Bayes' theorem

Real-world applications (medical testing, spam detection)

3. Probability Distributions (Day 4)
Three essential distributions for modeling data:

Normal (Gaussian) distribution

Binomial distribution

Poisson distribution

The 68-95-99.7 rule

📁 Repository Structure
text
statistics-cheatsheet/
├── README.md (you are here!)
│
├── notebooks/
│   ├── 01_descriptive_statistics.ipynb
│   │   └── 8 concepts, 4 visualizations, complete examples
│   │
│   ├── 02_probability_basics.ipynb
│   │   └── Probability theory, Bayes' theorem, real-world problems
│   │
│   └── 03_probability_distributions.ipynb
│       └── Normal, Binomial, Poisson with visualizations
│
├── data/
│   └── sample_data.csv (example datasets for practice)
│
├── images/
│   ├── descriptive_stats_viz.png
│   ├── distribution_comparisons.png
│   └── (and more visualizations)
│
└── docs/
    ├── WEEK1_SUMMARY.md (complete synthesis)
    ├── FORMULAS_REFERENCE.md (all formulas in one place)
    └── REAL_WORLD_APPLICATIONS.md (practical examples)
🚀 Getting Started
Option 1: View Online (Easiest)
Open any .ipynb file above

GitHub will render it automatically

Read through and follow the examples

Option 2: Run Locally (Interactive)
bash
# Clone the repository
git clone https://github.com/YOUR_USERNAME/statistics-cheatsheet.git
cd statistics-cheatsheet

# Install requirements
pip install pandas numpy matplotlib seaborn scipy jupyter

# Start Jupyter
jupyter notebook

# Open notebooks in browser
Option 3: Quick Reference (Fastest)
Jump to Formulas Cheatsheet below for the essentials.

📊 Course Progression
Day 1: Descriptive Statistics Fundamentals
Time: 5.5 hours | Concepts: 8 | Problems: 10+

Learn to describe existing data using statistical measures.

Topics:

What is data? (Variables, types, distributions)

Central tendency (Mean, Median, Mode)

Spread (Range, Variance, Std Dev)

Outliers (IQR method)

Shape (Skewness, Kurtosis)

Notebook: 01_descriptive_statistics.ipynb

Key Insight: Mean ≠ Median when outliers present. Always check both!

Day 2: Real-World Practice & Applications
Time: 4.5 hours | Concepts: Applied | Problems: 20+

Apply Day 1 concepts to real-world datasets and learn when to use each metric.

Scenarios:

Customer purchase analysis (outlier detection)

Class performance comparison (std dev importance)

Manufacturing quality control (tolerance calculations)

Salary fairness assessment (distribution analysis)

Notebook: 02_probability_basics.ipynb

Key Insight: Don't just look at mean. Full picture = mean + median + std dev!

Day 3: Probability Fundamentals
Time: 5.5 hours | Concepts: 3 | Problems: 11

Understand likelihood and uncertainty through probability theory.

Topics:

Basic probability (definition, rules)

Probability rules (addition, multiplication, complement)

Conditional probability P(A|B)

Bayes' theorem (belief updating)

Independent vs dependent events

Notebook: 03_probability_distributions.ipynb

Key Insight: Bayes' theorem changes beliefs. Why 95% accurate test ≠ 95% probability!

Day 4: Probability Distributions
Time: 5.5 hours | Concepts: 3 distributions | Problems: 9

Learn three essential distributions for modeling different types of data.

Distributions:

Normal (Gaussian)

Type: Continuous

When: Measurements (heights, test scores, weights)

Key: 68-95-99.7 rule

Binomial

Type: Discrete

When: Fixed number of trials (coin flips, clicks, defects)

Key: E(X) = n × p

Poisson

Type: Discrete

When: Events over time/space (arrivals, errors, calls)

Key: E(X) = λ

Notebook: 03_probability_distributions.ipynb

Key Insight: Pick the right distribution = understand what's normal vs unusual!

Day 5: Synthesis & Week 1 Wrap-Up
Time: 3.5 hours | Deliverable: Professional portfolio

Connect all concepts and prepare for Week 2.

📚 Formulas Cheatsheet
Descriptive Statistics
text
Mean:           Σx / n
Median:         Middle value (50th percentile)
Mode:           Most frequent value
Range:          Max - Min
Variance:       Σ(x - mean)² / n
Std Dev:        √Variance
IQR:            Q3 - Q1
CV:             (Std Dev / Mean) × 100
Skewness:       Measure of asymmetry
Kurtosis:       Measure of tail heaviness
Probability
text
Basic:          P(Event) = Favorable Outcomes / Total Outcomes
Addition:       P(A ∪ B) = P(A) + P(B) - P(A ∩ B)
Multiplication: P(A ∩ B) = P(A) × P(B|A)
Complement:     P(Aᶜ) = 1 - P(A)
Conditional:    P(A|B) = P(A ∩ B) / P(B)
Bayes:          P(A|B) = P(B|A) × P(A) / P(B)
Distributions
Normal Distribution:

text
Parameters:     μ (mean), σ (std dev)
68% Rule:       P(μ - σ < X < μ + σ) = 0.68
95% Rule:       P(μ - 2σ < X < μ + 2σ) = 0.95
99.7% Rule:     P(μ - 3σ < X < μ + 3σ) = 0.997
Z-score:        z = (x - μ) / σ
Binomial Distribution:

text
Parameters:     n (trials), p (success probability)
Mean:           E(X) = n × p
Variance:       Var(X) = n × p × (1-p)
Std Dev:        σ = √[n × p × (1-p)]
Probability:    P(X = k) = C(n,k) × p^k × (1-p)^(n-k)
Poisson Distribution:

text
Parameter:      λ (lambda = mean events)
Mean:           E(X) = λ
Variance:       Var(X) = λ
Std Dev:        σ = √λ
Probability:    P(X = k) = (e^-λ × λ^k) / k!
🌍 Real-World Applications
Medical Testing
Problem: A disease test is 95% accurate. You test positive. What's the chance you have it?

Answer: Only ~16%! (Not 95%)

Why? Disease is rare (1%), so false positives dominate. This is Bayes' theorem in action!

Learn: 03_probability_basics.ipynb

Marketing: A/B Testing
Problem: You run an ad campaign. 1000 emails, 3% click rate. Is 35 clicks good or bad?

Answer: Expected 30 ± 5.4 clicks. 35 is normal variation.

Why? Binomial distribution models this exactly!

Learn: 03_probability_distributions.ipynb

Quality Control
Problem: Manufacturing widgets with μ=10cm, σ=0.1cm. Is 10.5cm widget defective?

Answer: Yes! It's 5 standard deviations away (only 0.000029% chance).

Why? Normal distribution tells us what's acceptable!

Learn: 01_descriptive_statistics.ipynb

Customer Support
Problem: Help desk gets 8 calls/hour on average. How likely is >15 calls?

Answer: Very unlikely (~0.5%)

Why? Poisson distribution models rare events!

Learn: 03_probability_distributions.ipynb

🎯 Learning Path Recommendations
Path 1: Quick Learner (4 hours)
Read this README (20 min)

Skim formulas (20 min)

Run 01_descriptive_statistics.ipynb (90 min)

Skim 03_probability_distributions.ipynb (90 min)

Outcome: Understand the basics, see practical examples

Path 2: Thorough Learner (12 hours)
Work through all notebooks in order

Solve all practice problems

Run code examples

Create your own examples

Outcome: Deep understanding, ready for Week 2

Path 3: Mastery (20+ hours)
Complete all notebooks

Solve all problems

Modify examples with your own data

Teach concepts to someone else

Outcome: Expert-level understanding, ready for employment

💾 Sample Data
The data/ folder contains example datasets for practice:

sample_data.csv - Contains various distributions of student metrics

Load and explore: pd.read_csv('data/sample_data.csv')

🤝 Contributing
Found an error? Want to add an example?

Fork the repository

Create a new branch

Make your changes

Submit a pull request

📖 Additional Resources
Books
"Statistical Rethinking" by Richard McElreath

"Naked Statistics" by Charles Wheelan

"Probability & Statistics" (any standard textbook)

Online
Khan Academy: Statistics & Probability

StatQuest (YouTube): Intuitive explanations

3Blue1Brown: Beautiful visualizations

Python Libraries Used
pandas: Data manipulation

numpy: Numerical computing

scipy.stats: Statistical distributions

matplotlib: Visualization

seaborn: Statistical visualizations

🎓 What You'll Be Able To Do
After working through this material, you'll be able to:

✅ Describe data: Mean, median, std dev, outliers
✅ Think probabilistically: Understand likelihood and uncertainty
✅ Choose distributions: Know when to use Normal, Binomial, Poisson
✅ Solve real problems: Medical tests, marketing, quality control
✅ Calculate probabilities: For any distribution
✅ Understand Bayes' theorem: Update beliefs with new evidence
✅ Write Python code: Analyze data professionally
✅ Read research papers: Understand statistical claims
✅ Make data-driven decisions: With confidence intervals and p-values

🎉 Next Steps
Week 1 Complete! 🎓

Next up: Week 2 - Hypothesis Testing

P-values and significance

T-tests and confidence intervals

Chi-square tests

A/B testing in practice

Check back December 16-20 for Week 2 materials!

📝 License
This educational material is provided freely for learning purposes.

👨‍💻 Author
Created as part of a comprehensive statistics and probability course.

Last Updated: December 13, 2025
Status: Week 1 Complete ✅

❓ Questions?
Confused by a concept? Check the notebooks first, then reread the formulas

Want more examples? Modify the code in notebooks with your own data

Ready for more? Week 2 materials coming soon!

🚀 Ready to Learn?
Pick a notebook above and start exploring!

Recommended: Start with 01_descriptive_statistics.ipynb

Happy Learning! 💪📊
