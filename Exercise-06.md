# Exercise 06 – Generating Speaker Notes from Slides
**Slides:** 14, 74 | **Time:** 3–5 min | **Tool:** Microsoft Copilot

---

## 🎯 Objective
Use a screenshot of any presentation slide to automatically generate structured, professional speaker notes — saving significant prep time for anyone who builds decks regularly.

---

## 📎 Resources Needed
- A screenshot of any slide (from your own deck, or take a screenshot of one of today's slides)
- Microsoft Copilot (use the image upload feature)

---

## 💬 Solution Prompt

```
You are an expert presentation coach and instructional designer.

I'm going to share a screenshot of a PowerPoint slide. Based on what you see 
on the slide — the title, content, visuals, and layout — generate speaker 
notes I can use when presenting this slide.

Important constraints:
- Only reference what is visually present on the slide.
- Do not invent data, statistics, or claims that aren't shown.
- If something on the slide is ambiguous, flag it with:
  ⚠️ "Unclear from slide — you may want to add context here."
- If the slide contains a chart or graph, describe what the visual shows and 
  suggest how to walk the audience through it.

Format the speaker notes exactly like this:

INTRODUCTION:
Two sentences to set up the slide — what are we about to talk about and 
why it matters.

PURPOSE:
One sentence on what this slide is meant to accomplish.

TALKING POINTS:
3–5 key points to say out loud, written in natural conversational language 
(not bullet-point reading). Each point should be 1–2 sentences.

TRANSITION:
One sentence that bridges to the next slide.

TEACHING TIPS (optional):
Any suggestions for audience engagement — questions to ask, demos to show, 
or moments to pause.

Keep the tone professional but conversational — like an experienced instructor 
who's comfortable with the material, not reading from a script.

[ATTACH SLIDE SCREENSHOT HERE]
```

---

## 🔁 Pro Tip — Save as Custom Instructions
If you build decks regularly, save this format in your Copilot custom instructions so you only need to type `"speaker notes"` and upload a screenshot.

Example custom instruction:
```
If I say "speaker notes" as my prompt, what I really mean is:
"Can you create speaker notes for each slide? (each image I have attached 
is a separate slide)"

Format for speaker notes:
PURPOSE:
$single_sentence_slide_purpose

TALKING POINTS:
• $tp_1
• $tp_2
• $tp_3

TEACHING TIPS:
• $teaching_tip_1
```

---

## ✅ What Good Output Looks Like
- INTRODUCTION sets context without restating the slide title verbatim
- TALKING POINTS sound like something a human would actually say out loud
- Any vague visuals are flagged with ⚠️ rather than guessed at
- TRANSITION feels natural, not abrupt
- Total output is 150–250 words — enough to guide but not a script

---

## ⚠️ Watch Out For
- The model may over-describe visuals (reading charts out loud) — if so, add: *"Don't read the data out loud — tell me how to interpret it for the audience."*
- If the slide has no text (just an image), the model may hallucinate content — always verify output against the actual slide

---

## 🗣 Reflection Questions
1. How accurate were the talking points compared to what you would actually say?
2. Would you use this for every slide, or just the complex ones?
3. How would you adjust the format to better match your presentation style?
