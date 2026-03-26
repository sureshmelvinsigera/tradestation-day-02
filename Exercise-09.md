# Exercise 09 – Exploratory Data Analysis with AI
**Slides:** 59–65 | **Time:** 10 min | **Tool:** Microsoft Copilot (Free)

---

## 🎯 Objective
Upload a real dataset and guide Copilot through an exploratory data analysis (EDA) — from first look to policy-level insights — without writing a single line of code yourself.

---

## 📎 Resources Needed
- **File:** `productivity_n_hourly_compensation.csv` (from Slack pinned materials)
- Open a **new chat window** in Copilot before uploading
- Use the **free version** of Copilot for this exercise

---

## ⚠️ Critical Reminder Before You Start
> AI can and will fabricate data to complete your request. It often hints at this, but it's easy to miss. **Always document that you used AI when presenting data, and sanity-check key numbers against the source file.**

---

## 💬 Solution Prompts — Run in Sequence

---

### Step 1 — First Look

```
I've attached a CSV dataset. Before we do any analysis, please:

1. Tell me what this dataset contains — what are the columns, what do they 
   represent, and what time period does it cover?
2. Tell me how many rows and columns it has
3. Flag any obvious data quality issues (missing values, unusual entries, 
   potential duplicates)
4. Suggest 5 interesting questions we could explore with this data

Do not start any analysis yet — just describe what you see.
```

---

### Step 2 — Exploratory Data Analysis

```
Now let's do exploratory data analysis on this dataset.

Please run the following:
1. Basic descriptive statistics for all numeric columns 
   (mean, median, min, max, standard deviation)
2. Identify the year with the highest and lowest values for each key metric
3. Calculate the percentage change from the earliest to the most recent year 
   for each metric
4. Identify any trends — are these metrics generally going up, down, or flat?
5. Flag any outliers or anomalies worth investigating

Show your working where possible, and flag anything that seems unusual.
```

---

### Step 3 — Top Insights

```
Based on your analysis, what are the top 5 most interesting or important 
insights from this dataset?

For each insight:
- State the finding clearly in one sentence
- Provide the specific data point(s) that support it
- Explain why this finding is significant or surprising
- Rate your confidence: HIGH / MEDIUM / LOW, and explain why

Do not include any insight you cannot directly support with numbers from 
the data.
```

---

### Step 4 — Policymaker Recommendations

```
Imagine you are presenting this data to a team of economic policymakers 
who are deciding how to address workforce productivity and compensation.

Based only on what the data shows, suggest 3 specific policy actions 
they might consider.

For each recommendation:
- State the policy action
- Cite the specific data finding that motivates it
- Identify one risk or limitation of this recommendation
- Note any data gaps that would need to be filled before acting

Remember: only recommend based on what the data actually shows.
```

---

## 🔁 Bonus — Visualization Prompt

```
Create a visualization that best shows the relationship between productivity 
and hourly compensation over time.

Use a line chart with:
- Year on the x-axis
- Both productivity and compensation as separate lines
- A clear title and axis labels
- A brief annotation pointing to any notable divergence between the two lines

After generating the chart, write 2–3 sentences interpreting what it shows.
```

---

## ✅ What Good Output Looks Like
- Step 1 correctly identifies column names and data types without hallucinating
- Statistics in Step 2 are calculable from the actual CSV
- Insights in Step 3 are specific and cite actual numbers (not vague trends)
- Policymaker recommendations are grounded in data, not general knowledge
- Any limitations or confidence gaps are honestly flagged

---

## ⚠️ Watch Out For
- **The model may generate numbers that don't exist in the file.** If something looks surprising, ask: *"Can you show me exactly where in the data that number comes from?"*
- If Copilot says it "analyzed" data but only described it — push back: *"Can you actually calculate the descriptive statistics rather than just describing the columns?"*

---

## 🗣 Reflection Questions
1. Were any of the top 5 insights surprising to you?
2. Did the model flag any of its own limitations or confidence gaps?
3. Where in your own role could you apply this EDA workflow to data you already have access to?
