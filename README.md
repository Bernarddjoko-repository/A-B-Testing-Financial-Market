![istockphoto-531935178-612x612](https://github.com/user-attachments/assets/c731d294-c9b3-4221-a28b-592b1be0bf93)


## Financial Market A/B Testing 

### 📌 Introduction

### Project Overview

This project explores A/B testing in financial markets to evaluate the effectiveness of an alternative trading strategy (Strategy B) against a baseline strategy (Strategy A). We leverage statistical hypothesis testing, Bayesian inference, and machine learning to analyze market performance and optimize trading decisions.

### Objective

📊 Determine if Strategy B improves profitability compared to Strategy A.

📈 Assess the impact of market conditions on strategy performance.

🔍 Identify key factors influencing profitability using machine learning.

### 📌 Dataset Overview

#### Data Source & Structure

Dataset Size: 1000 trading records.

#### Key Features:

price_before, price_after → Asset prices before and after the trade.

volume_before, volume_after → Trading volume before and after.

market_condition → Categorized as Bullish, Bearish, or Sideways.

return_before, return_after → Trade returns before and after applying the strategy.

strategy_version → Identifies Strategy A (control) and Strategy B (treatment).

profit_difference → return_after - return_before, measuring improvement.


### 📌 Business Problem

🚨 Many trading strategies fail to consistently improve profitability in financial markets.

⚠ We need an evidence-based approach to determine whether Strategy B significantly outperforms Strategy A.

🎯 Understanding the conditions where Strategy B is most effective will allow for better optimization and risk management.


### 📌 Step-by-Step Approach

#### 🧹 Data Preprocessing & Cleaning:

Converted date column, handled missing values, and removed duplicates.

Standardized numeric variables.

#### 📊 Exploratory Data Analysis (EDA):

Compared return_before and return_after distributions.

Identified market trends impacting strategy effectiveness.

#### 📈 A/B Testing:

T-test → Checked for statistical significance between Strategy A and B.

ANOVA → Analyzed market condition influence on profitability.

#### 📊 Bayesian A/B Testing:

Estimated the probability of Strategy B outperforming Strategy A.

#### 🧠 Machine Learning (Clustering & Regression):

Used K-Means clustering to segment profitable trader groups.

Built a linear regression model to identify the most impactful features.

#### 📑 PowerPoint Automation with VBA:

Developed a VBA macro to automate report generation.


### 📌 Challenges & Solutions

#### Market conditions had no statistical significance:

Used Bayesian methods to confirm findings and validate strategy effectiveness.

#### Profitability varied by subgroup:

Applied clustering analysis to identify ideal conditions for Strategy B.

#### Strategy B was not always profitable:

Defined optimal conditions for its use and suggested refinements for improvement.

### 📌 Results

📊 Strategy B significantly outperforms Strategy A (p = 0.0311, Bayesian probability = 99.04%).

❌ Market conditions do not significantly impact profitability.

📈 Return Before (return_before) is the strongest predictor of profitability improvement.

🔍 Strategy B is highly effective in Cluster 0 but ineffective in others.

### 📌 Future Work

🔬 Optimize Strategy B for underperforming clusters.

🤖 Implement deep learning models to refine predictions.

🌍 Incorporate macroeconomic factors (inflation, interest rates) for better insights.

📈 Deploy Strategy B in a real-world trading environment and track live performance.

### 📌 Key Takeaways

✅ Strategy B is statistically proven to be better than Strategy A. <br>
✅ Market conditions do not significantly affect profitability. <br>
✅ Clustering analysis shows that Strategy B works best for specific trader groups. <br>
✅ Bayesian A/B Testing provides a robust confidence measure of effectiveness. <br>
✅ Automating reporting (VBA) improves efficiency in presenting findings. <br>



