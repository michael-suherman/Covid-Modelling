# 🦠 Covid-19 Modeling in Indonesia

## 📌 Project Overview

While many countries shared COVID-19 data transparently, the Indonesian government initially suppressed case numbers to maintain economic confidence. When I realized that the reported data was inaccurate, I became curious about how such manipulation might affect statistical modeling. This project was my attempt to explore the issue through a combination of **mathematics**, **statistics**, and **programming**.

---

## 🎯 Goal

To analyze and model COVID-19 cases and deaths in Indonesia using statistical techniques and simulations, and to explore how missing or inaccurate data affects analysis.

---

## 📚 Background

At the time of this project (2020), I was:

- Taking an **Advanced Statistics** course for my A-levels  
- Self-studying **Python** and **C++** for nearly two years  
- Interested in how data science could be used to understand real-world events

This project was my way of combining classroom theory with real-world data to investigate a national issue.

---

## 🔧 What I Did

- 📈 **Fitted** COVID-19 case and death data to probability distributions
- 📊 Performed a **Chi-square goodness-of-fit test** on the normal distribution
- 📉 Computed **confidence intervals** for the time from symptoms to death
- 🔍 Analyzed data using **standard deviation bands** (1σ, 2σ, 3σ)
- 🧪 Simulated disease progression using the **SIRD model**
- 🐍 Used **Python**, along with libraries like:
  - `pandas` for data handling
  - `matplotlib` for graphing
  - `scipy` and `numpy` for statistical analysis

---

## 📁 Repository Structure

/data → CSV files of COVID-19 case numbers and deaths
/plots → Output graphs (case curve, SIRD model, etc.)
/notebooks → Jupyter notebooks with all modeling steps
/statistics → Chi-square tests, confidence interval calcs, etc.
/sird_model → Python scripts to simulate the SIRD progression

yaml
Copy
Edit

---

## 📊 Key Findings

- The official case curve showed statistical irregularities compared to expected distributions.
- Confidence intervals for time from symptoms to death revealed inconsistencies that suggested underreporting.
- The SIRD model predicted far higher case loads than were being publicly reported at the time.

---

## 🙋 What I Learned

- Applying real-world data to abstract statistical concepts
- Using Python libraries to automate data analysis
- The challenges of modeling incomplete or biased data
- How data transparency (or lack thereof) impacts public health modeling

---

## 🧠 Reflection (5 Years Later)

This was my first serious attempt at combining coding and math for a real-world problem — and it shaped the way I think about data science and modeling today. If I were to redo this project now, I would:

- Use machine learning techniques to fit data with more flexibility
- Explore Bayesian inference to model uncertainty from hidden variables
- Implement interactive visualizations with Plotly or Dash

---

## 📜 Disclaimer

This project was done as a high school exploration and should not be used for policy decisions or medical inference. Data sources were accurate to the best of my knowledge at the time.




