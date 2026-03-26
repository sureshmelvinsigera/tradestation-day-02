# Exercise 08 – Service Innovation from a User Interview
**Slides:** 46, 76–77 | **Time:** 5 min | **Tool:** Microsoft Copilot

---

## 🎯 Objective
Use AI as an expert consultant to analyze a customer interview transcript and generate a structured, actionable innovation roadmap from real qualitative data.

---

## 📎 Resources Needed
- **File:** `Service Innovation - User Interview` (from Slack pinned materials)
- Microsoft Copilot

---

## 💬 Solution Prompt — Starter

```
You are an expert consultant specializing in customer experience, service 
design, and innovation strategy.

I conducted the attached user interview with a customer of our grocery 
delivery service. I want to use their feedback to identify innovation 
opportunities.

Please give me a step-by-step breakdown of how we can work from this 
interview to innovate our service. Structure your response as follows:

Step 1 — Synthesize the Customer's Voice
Summarize the key themes, pain points, and desires expressed in the interview. 
Quote the customer's own words where possible.

Step 2 — Identify the Jobs to Be Done
What is the customer actually trying to accomplish? What outcomes matter most 
to them beyond just "getting groceries delivered"?

Step 3 — Define the Innovation Opportunities
List 5 specific opportunities to improve or expand the service based on 
what you heard. Prioritize by impact and feasibility.

Step 4 — Recommend Quick Wins (0–3 months)
What could we change or test immediately with minimal cost or risk?

Step 5 — Recommend Strategic Initiatives (3–12 months)
What bigger bets should we consider based on this feedback?

Step 6 — Suggest Follow-Up Questions
What would you want to ask this customer next to go deeper?

[ATTACH USER INTERVIEW TRANSCRIPT HERE]
```

---

## 🔁 Follow-Up Prompt — Go Deeper on Step 1

```
Can you expand on Step 1? I want to understand the emotional drivers behind 
this customer's frustration. What is she really telling us beneath the surface?
```

---

## 🔁 Advanced Follow-Up — Build a HMW Statement

```
Based on this interview, write 5 "How Might We" (HMW) statements that our 
product team could use as innovation prompts. 

Format:
"How might we [do something] so that [customer benefit]?"

Focus on the tension between what the customer wants (local, ethical, 
sustainable) and what current delivery services typically offer.
```

---

## 🔁 Adapt to TradeStation Context

Replace the grocery delivery scenario with your own:

```
You are an expert consultant in financial services UX and customer experience.

I conducted the attached user interview with an active retail trader who uses 
our brokerage platform. I want to use their feedback to identify service 
improvement opportunities.

[Same step structure as above]
```

---

## ✅ What Good Output Looks Like
- Step 1 quotes directly from the interview — not paraphrased generalizations
- Jobs to Be Done go beyond surface requests ("faster delivery") to emotional needs ("I want to feel good about my choices")
- Innovation opportunities are specific and tied to evidence from the transcript
- Quick wins are realistic and could actually be actioned this quarter
- Follow-up questions show the AI is thinking like a researcher, not just summarizing

---

## ⚠️ Watch Out For
- The model may add general industry knowledge not in the interview — if so, add: *"Only reference what the customer actually said in this interview. Do not draw on general knowledge about the grocery delivery industry."*
- If the interview is long, Copilot may miss later sections — ask: *"Did you include the second half of the interview in your analysis?"*

---

## 🗣 Reflection Questions
1. Did the AI surface anything from the interview that you had missed or underweighted?
2. How does this compare to how you currently use customer feedback in your work?
3. What would a similar prompt look like for a TradeStation customer interview?
