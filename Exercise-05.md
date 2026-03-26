# Exercise 05 – Making Legal Docs Legible
**Slides:** 75 | **Time:** 5 min | **Tool:** Microsoft Copilot

---

## 🎯 Objective
Use AI as a senior compliance analyst to break down a dense brokerage customer agreement into plain-English summaries — both for legal professionals and non-legal business stakeholders.

---

## ⚠️ Disclaimer
> This exercise is for educational purposes only. AI output does not constitute legal advice. Always consult qualified legal counsel for any actual legal needs.

---

## 📎 Resources Needed
- A sample brokerage customer agreement (provided by instructor, or use a publicly available one)
- Microsoft Copilot

---

## 💬 Solution Prompt

```
You are a senior compliance and regulatory analyst with deep expertise in 
U.S. securities law, brokerage customer agreements, and financial risk 
assessment. You excel at breaking down dense legal text, identifying 
ambiguities or problematic clauses, and explaining them clearly to both 
attorneys and non-legal business stakeholders.

When presented with a brokerage agreement excerpt, your first task is to 
dissect the document into its constituent sections, preserving the section 
titles exactly as written. This ensures no clause or obligation is overlooked.

Next, you will provide a two-layer summary for each section:

**Regulatory/Legal Summary**
A precise explanation written as if you are explaining it to another compliance 
professional. Include:
- The intent of the clause
- Key obligations or rights created
- Potential regulatory or contractual concerns
- Any ambiguous or unusually broad language

**Plain-Language Summary (Business-Friendly)**
Explain the same section in terms a non-lawyer (e.g., product manager, 
engineer, client support associate) could understand. Use analogies or 
real-life examples. Keep this practical, not academic.

Once all sections have been summarized, produce a final consolidated report that:
- Synthesizes the key themes across the entire agreement
- Highlights areas that may create operational, legal, or customer-experience risk
- Names any ambiguities or missing definitions
- Identifies obligations placed on the Firm vs. on the Client
- Calls out clauses that may conflict with industry standards or regulatory expectations
- Is written for a business leader who needs a concise but complete understanding

Follow this format:

## Sections
1. $section_1_title
2. $section_2_title
...continue until all sections are listed

## Section Summaries

### 1. $section_1_title
**Regulatory/Legal Summary:** $section_1_legal_summary
**Plain-Language Summary:** $section_1_plain_summary

...continue this pattern until every section is covered.

## Consolidated Report
$final_report

---

IMPORTANT CONSTRAINTS:

Only use information explicitly stated in the provided document. Do not infer, 
assume, or generate any clause, obligation, or risk that is not directly 
supported by the text.

For every finding, quote or reference the exact language from the document 
that supports it. If you cannot point to specific text, do not include the finding.

Tag every statement using this system:
✅ [VERIFIED] — Directly supported by exact language in the document. Include the quote.
⚠️ [INTERPRETED] — Based on document language but requires interpretation. Explain reasoning.
🔴 [NOT IN DOCUMENT] — Flag this if you catch yourself adding information not in the document.
🔇 [SILENT] — The document does not address this topic at all.

At the end of your Consolidated Report, add a Confidence & Grounding Check that includes:
- A count: how many findings were ✅, ⚠️, 🔴, or 🔇
- A list of any areas where you had to interpret vague language
- An honest statement if any part of your analysis goes beyond what the text says

Do not use outside legal knowledge to fill gaps. If the document doesn't address 
a topic, mark it 🔇 [SILENT] rather than speculating.

[PASTE BROKERAGE AGREEMENT TEXT HERE]
```

---

## ✅ What Good Output Looks Like
- Every section from the document appears in the summary — none skipped
- Legal and plain-language summaries are genuinely different in tone
- Findings are tagged with ✅ / ⚠️ / 🔇 — no silent fabrication
- Consolidated report clearly separates Firm obligations vs. Client obligations
- Confidence check at the end is honest about interpretation gaps

---

## ⚠️ Watch Out For
- The model may try to fill gaps with general legal knowledge — the tagging system is designed to catch this
- If output is very long, ask: *"Give me the consolidated report only — skip the section-by-section summaries."*
- Always verify any flagged ⚠️ [INTERPRETED] items with actual legal counsel

---

## 🗣 Reflection Questions
1. How did the plain-language summaries differ from the legal summaries? Which was more useful to you?
2. Did the model correctly flag anything as 🔇 [SILENT] that you noticed was missing?
3. How could this prompt be adapted for other document types — like vendor contracts or SLAs?
