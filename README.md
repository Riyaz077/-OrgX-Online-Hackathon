# 'OrgX' Online-Hackathon
AI-Driven Impulsive Spending Risk Detection System
Detecting Financial Impulse Behaviour in Young Adults

# 📌 Project Overview

This project presents an AI-based behavioural analytics system designed to detect and predict impulsive spending behaviour among young adults using transaction-level data. The system integrates Behavioural Finance principles with machine learning techniques to identify unstable expenditure patterns and generate actionable financial recommendations.

The goal is not only to predict high-risk spending behaviour but also to promote financial literacy through personalized nudging interventions.

# 🎯 Problem Statement

Young adults often exhibit unstable and impulsive spending patterns influenced by emotional triggers and timing factors such as late-night purchases and end-of-month spending spikes. These behaviours can negatively impact long-term financial well-being.

This project aims to detect such behavioural patterns using machine learning and provide proactive intervention strategies.

# 📊 Dataset Information

Dataset Type: Synthetic

Reason: Real transaction-level behavioural datasets are private and confidential due to financial data protection regulations.

How Dataset Was Generated:
The dataset was simulated using realistic financial behaviour assumptions:

Normal distribution for average spending

Higher probability of impulse purchases in entertainment, shopping, travel, and food delivery categories

Increased spending probability during late-night hours (10 PM – 4 AM)

Higher spending intensity towards end-of-month (25th onwards)

# ⚙️ Feature Engineering

**Time-Based Features:**

•	Month

•	Day

•	Hour

•	Day of Week

•	Late-Night Indicator

•	End-of-Month Indicator

•	Weekend Indicator

**Behavioural Features:**

•	Impulse Category Detection

•	Impulse Spending Ratio

•	Average Spending per User

•	Spending Frequency Volatility

**Model-Derived Features:**

•	Predicted Risk Probability

•	Behaviour Cluster Label

•	Composite Impulse Risk Score (0–100)

# 🤖 Models Used

**1️⃣ Random Forest Classifier**

•	Predicts probability of high-risk impulsive spending
•	Handles nonlinear behavioural patterns
•	Contributes 40% weight to final risk score

**2️⃣ K-Means Clustering**

Segments users into behavioural profiles:
•	Conservative Planner
•	Impulsive Night-Owl
•	High-Frequency Shopper
•	Stable Balanced

**3️⃣ Composite Risk Scoring Model**

**Final Risk Score Formula:**

Impulse Risk Score = (Impulse Ratio × 30%) + (Late Night Ratio × 20%) + (Frequency Volatility × 10%) + (Predicted Risk Probability × 40%

