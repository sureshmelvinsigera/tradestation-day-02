# Exercise 03 – Large Document Summary
**Slides:** 36–38 | **Time:** 5 min | **Tool:** Microsoft Copilot

---

## 🎯 Objective
Upload a large PDF and use audience-aware prompting to extract the key insights in different formats and for different readers.

---

## 📎 Resources Needed
- **File:** `Large PDF To Summarize.pdf` (from the Slack pinned materials)
- Open a **new chat window** in Copilot before uploading

---

## 💬 Solution Prompts

---

### 🔵 Prompt 1 — Team Slack Summary (Starter)
*Use this first to get your baseline summary*

```
Please summarize the attached paper. I want to send the key takeaways to my 
Product Development team via a Slack message, so ensure that all of the 
practical, applicable learnings are included in your summary.

Format the output as a Slack message with:
- A one-sentence hook to grab attention
- 4–5 bullet points covering the most actionable insights
- A "Why this matters for us" section (2–3 sentences)

Finish with the three most important takeaways.
```

---

### 🔵 Prompt 2 — Three Audiences
*Run this after Prompt 1 to see how output changes with audience*

```
Now summarize the same document three more times, each for a different audience:

1. For a 10-year-old: Use simple language, short sentences, and a fun analogy 
   to explain what this paper is about and why it matters.

2. For a university student: Include the key concepts, methodology, and findings 
   in a way that would help them understand the research contribution.

3. For a Sales Team: Focus only on what this research means for customers, 
   market opportunities, or competitive advantage. Skip the technical detail.

Present each summary under a clear heading.
```

---

### 🔵 Prompt 3 — Format Transformer
*Pick one format and run it*

```
Take the key findings from the paper and transform them into a 
[choose one: Twitter/X Thread | LinkedIn Post | FAQ document].

For a Twitter/X Thread:
- Write 8–10 tweets
- Start with a hook tweet that makes someone want to keep reading
- Each tweet should be a standalone insight
- End with a "key takeaway" tweet

For a LinkedIn Post:
- 150–200 words
- Professional but accessible tone
- Include 3 hashtags
- End with a question to spark engagement

For an FAQ:
- Write 6–8 questions a curious reader might ask
- Answer each in 2–3 sentences
- Keep answers jargon-free
```

---

## ✅ What Good Output Looks Like
- The summary stays faithful to the document — no invented claims
- Each audience version feels genuinely different in tone and vocabulary
- Practical insights are front and center, not buried in academic language
- The format transformer output is ready to copy-paste with minimal editing

---

## ⚠️ Watch Out For
- Copilot sometimes summarizes what the paper is *about* rather than what it *found* — if this happens, add: *"Focus on findings and conclusions, not the research process."*
- If output feels vague, follow up with: *"Can you be more specific? Quote or closely paraphrase the actual findings."*

---

## 🗣 Reflection Questions
1. How did the output change between the three audience versions? What does that tell you about prompting?
2. Which format (Slack, LinkedIn, FAQ, Twitter) would be most useful in your actual role?
3. Where might you need to fact-check or sanity-check the AI's summary?
