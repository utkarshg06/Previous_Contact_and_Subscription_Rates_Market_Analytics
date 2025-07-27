# Does Previous Contact Influence Subscription Rates?
# 📈 Causal Impact of Previous Contact in Banking Marketing Campaigns

This repository explores the causal effect of previous customer contact on subscription likelihood during direct marketing campaigns by a Portuguese banking institution. By leveraging both econometric and machine learning methods, the project aims to uncover insights that improve targeting strategies and reduce outreach costs.

---

## 🧠 Motivation

### Banking & Marketing Relevance
- Many banks rely on direct marketing campaigns to acquire new customers.
- Understanding whether **previous contact** influences subscription likelihood allows banks to **optimize marketing strategies** and reduce unnecessary outreach costs.

### Economic & Business Importance
- Direct marketing campaigns can be expensive and inefficient targeting reduces ROI.
- If prior contact significantly impacts customer behavior, focusing on **responsive segments** can greatly improve **return on investment (ROI)**.

### Customer Behavior & Decision-Making
- Not all customers respond positively to repeated outreach; some may become disengaged or even annoyed.
- If **previous contact increases** conversion rates, banks should prioritize **follow-up calls**.
- If contact has **no effect or discourages** engagement, firms must revise their strategy accordingly.

---

## 📚 Literature Review

### Existing Studies in Financial Marketing
- **Moro et al. (2011)** used logistic regression to analyze the impact of direct marketing on term deposit subscriptions.  
  ➤ Found positive effects of engagement but did **not correct for selection bias**.
- **Ding et al. (2019)** cautioned that excessive contact may reduce customer engagement.

### Limitations of Prior Work
- Most rely on **OLS** or **Logistic Regression** models that lack causal inference rigor.
- **Self-selection bias** remains a major concern — customers more likely to subscribe may self-select into contact, confounding true treatment effects.

---

## 💡 Our Contribution

- Applied **multiple causal inference methods**:
  - Propensity Score Matching (PSM)
  - Regression Adjustment
  - Difference-in-Differences (DiD)

- Used **machine learning-based methods**:
  - Meta-Learners
  - Causal Random Forests

- Estimated **heterogeneous treatment effects (HTEs)** to identify customer segments most influenced by contact.
- Provided a **comprehensive, data-driven framework** combining econometrics and ML for optimized customer engagement.

---

## 📊 Dataset Overview

- Data from **direct marketing campaigns** conducted by a Portuguese bank.
- Customers were contacted via phone to promote **term deposit subscriptions**.
- Sourced from **Moro et al. (2011)**.
- Contains **4,521 observations** on:
  - Customer demographics
  - Prior interactions
  - Campaign outcomes

- **Primary objective**: Predict and understand whether a customer subscribes **after being contacted**.

---

## 🔍 Goals of This Project

- Quantify the **causal impact** of previous contact.
- Identify **which customers benefit** from follow-up marketing.
- Offer **targeted recommendations** to maximize conversion and reduce waste.

---
