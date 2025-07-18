# 🧠 Customer Review Analysis Using IBM Granite via Replicate API
This project analyzes Indonesian product reviews from Tokopedia under the **Computers & Technology** category using **IBM Granite LLM** via Replicate API.

---

## 📌 Project Overview
- **Objective:** Extract insights such as sentiment, emotion, keywords, and product aspects from user reviews.
- **Dataset:** [PREDICT-ID on Mendeley Data](https://data.mendeley.com/datasets/574v66hf2v/1)
- **Language:** Bahasa Indonesia
- **Focus Category:** Computers & Technology

---

## 🔍 Analysis Process
1. **Data Filtering & Cleaning**
   - Select only `computers&technology` reviews.
   - Clean the text using regex (remove URL, mention, symbols, etc).

2. **LLM Analysis (IBM Granite 3.1-8B Instruct via Replicate API)**
   - Tasks: summarization, sentiment, emotion, complaint, suggestions.
   - Example prompts and results stored in CSV.

3. **Visualization**
   - Pie chart of sentiment distribution.
   - Emotion analysis.
   - Complaint analysis

---

## 📊 Insights & Findings
- Most reviews were positive.
- Dominant emotions: **senang**, **puas**, and **kecewa**.
- Complaints often related to **shipping delay** and **performance**.
- Suggestions focused on improving customer service & packing quality.

---

## ✅ Conclusion & Recommendation
- Most products satisfy users, but shipping/logistics remain a weak point.
- Actionable steps:
  - Improve delivery system.
  - Clarify specs in product descriptions.
  - Monitor feedback on product quality more closely.

---

## 🤖 AI Support
- **LLM used:** `ibm-granite/granite-3.1-8b-instruct`
- **Platform:** Replicate API
- Used for:
  - Text summarization
  - Sentiment classification
  - Emotion detection
  - Complaint detection
  - Seller detection
