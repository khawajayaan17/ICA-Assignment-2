# 1_attempt.md — Core Thinking (Before AI Assistance)

**Snapshot Record:**

* **Commit Message:** `attempt-before-AI`

* **Commit Hash:** git add assignments/week1/1_attempt.md

  git commit -m "attempt-before-AI"

## 1. Everyday Vague Claims

1. **Claim 1:** "Grocery prices are rising so quickly that everyday staples are completely unaffordable now."

2. **Claim 2:** "Vegetables are way more expensive this year compared to basic packaged pantry items."

## 2. Answerable Questions & Required Variables

### For Claim 1:

* **Answerable Question:** "What was the month-over-month percentage change in the average price of staple food items (e.g., milk, eggs, bread) over the past 12 months?"

* **Required Variable(s):** `item_name`, `price`, `date`

### For Claim 2:

* **Answerable Question:** "How does the annual price inflation rate of fresh produce items compare to the price inflation rate of packaged pantry items in the dataset?"

* **Required Variable(s):** `item_category`, `price`, `date`

## 3. Pre-Code Predictions for `teaching_prices_clean.csv`

Before inspecting or running any code against the dataset, my initial predictions are:

* **Predicted Dataset Shape (Rows, Columns):** 1,200 rows, 5 columns

* **Predicted Number of Distinct Items:** 15 items

* **Predicted Number of Distinct Dates:** 24 dates (months)