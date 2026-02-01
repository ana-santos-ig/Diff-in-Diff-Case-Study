
## Diff-in-Diff Case Study — First Purchase Discount

Take-home case study analyzing the impact of a first-purchase discount on class pack performance using a Difference-in-Differences (DiD) causal inference approach.
## 📌 Overview

This project evaluates the causal impact of a 15% discount on first-time class pack purchases in a marketplace setting.
The analysis compares Test vs Control groups across Pre and Post periods to isolate the incremental effect of the discount on the funnel.

The study follows a structured analytical workflow:

Data validation
Metric construction
Exploratory analysis
Baseline comparability checks
Temporal evolution
Diff-in-Diff causal estimation

## 🎯 Business Question
Did offering a 15% discount to new users increase demand and improve funnel performance compared to a control group without discount?

🔬 Experimental Structure

Groups:
Test (users exposed to discount)
Control (users not exposed)

Time:
Pre period
Post period

Funnel metrics:
Pack Views
Purchases
Conversion Rate


## 📊Types of Analysis Performed

Data quality and experiment integrity checks
Construction of derived metrics (e.g. conversion rate)
Exploratory Data Analysis (EDA)
Baseline comparability tests (Pre-period)
Pre vs Post evolution by group
Diff-in-Diff causal estimation (by metric)

📈 Key Performance Indicators (KPIs)

Pack Views — top-of-funnel demand
Purchases — completed transactions
Conversion Rate — efficiency of the funnel

Segmented analysis by price tier

## 🧠 Methodology

The causal effect is estimated using a Difference-in-Differences approach:
The analysis is performed:
.First at the aggregate level
.Then by price tier to assess heterogeneity

Each metric is analyzed separately (Pack Views, Purchases, Conversion), with explicit construction of:
.Pre and Post averages
.Within-group deltas
.Cross-group DiD effect



# Note
This is a V0 implementation with simplified Diff-in-Diff analysis. 
A V1 version will include robustness checks, statistical inference, and extended validation.
