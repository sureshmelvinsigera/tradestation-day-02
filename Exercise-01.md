# 🎤 Applied GenAI – Day 2 Presenter Guide
### TradeStation × General Assembly | Q1 2026
**⏰ Session:** 1:00 PM – 2:25 PM (85 min) | **📍 Platform:** Zoom | **🛠 Tool:** Microsoft Copilot

---

## ✅ Pre-Session Checklist (Do This Before 1:00 PM)

- [ ] Slide deck open and on Slide 1
- [ ] Copilot logged in and tested on your machine
- [ ] Both files confirmed in Slack pinned materials: `Large PDF To Summarize.pdf` + `productivity_n_hourly_compensation.csv`
- [ ] Exercise README files open in a second window (your answer key)
- [ ] Feedback survey links ready to paste (Slides 70–72)
- [ ] Zoom chat open — you'll use it for polls and sharing links

---

## ⏱ Master Time Map

| # | Section | Slides | Clock | Duration |
|---|---|---|---|---|
| 1 | Warm-up & Day 1 Review | 1–3 | 1:00 – 1:10 | 10 min |
| 2 | Today's Agenda & Objectives | 4–5 | 1:10 – 1:13 | 3 min |
| 3 | Effective Business Writing | 6–15 | 1:13 – 1:28 | 15 min |
| 4 | 🟢 Exercise: Monzo Blog Post | 16–19 | 1:28 – 1:38 | 10 min |
| 5 | Improving Clarity + Writing Assistant | 20–26 | 1:38 – 1:48 | 10 min |
| 6 | Summarizing Content | 27–38 | 1:48 – 2:00 | 12 min |
| 7 | Fostering Innovation | 39–49 | 2:00 – 2:10 | 10 min |
| 8 | Data Analysis & Workflow Automation | 50–65 | 2:10 – 2:20 | 10 min |
| 9 | Wrap-up & Exit Ticket | 66–72 | 2:20 – 2:25 | 5 min |

> 🔴 **Running behind?** Compress Slides 50–58 (Python background) to 2 min. The EDA demo is the priority, not the theory.

---

---

## 📍 SECTION 1 — Warm-up & Day 1 Review
### Slides 1–3 | 1:00 – 1:10 | 10 min

---

### Slide 1 — Title Slide | 1:00 – 1:02

- This is your landing slide. Use it to settle the room while people join.
- Check Zoom names are **First Last** format for attendance.
- Keep the energy warm and welcoming — people log into training sessions tired.

> 💬 **SAY:** **"Welcome back everyone — good to see you all again. Before we get started, make sure your Zoom name shows your first and last name so we can mark you present."**

> 💬 **SAY:** **"While everyone's joining — go ahead and grab a coffee or tea if you need one. We've got a full session today and I want you sharp."**

---

### Slide 2 — Warm-up Instructions | 1:02 – 1:06

- Walk through the four warm-up items out loud, one by one.
- Drop both file names in Zoom chat so students can find them easily.
- The Copilot login is non-negotiable — call it out directly.

> 💬 **SAY:** **"First thing — head into Slack and find the pinned materials. You need two files for today: 'Large PDF To Summarize' and 'productivity_n_hourly_compensation.' Download both right now — you'll need them during exercises later and you won't want to be scrambling."**

> 💬 **SAY:** **"Second — log into Copilot if you haven't already. You will use it for every single breakout today. If you're having trouble accessing it, let me know in the chat now."**

> 💬 **SAY:** **"And while you're getting set up — drop in the chat where you're joining from today. Always nice to see where the room is coming from."**

---

### Slide 3 — Day 1 Review | 1:06 – 1:10

- Don't lecture through this — ask questions and let them recall. Retrieval builds retention.
- Three pillars to revisit: The Filter (R.I.P.E.), The Method (Lifecycle), The Techniques.
- Guardrails at the bottom of the slide — name all three. They'll come up again today.

> 💬 **SAY:** **"Before we jump into new material, let's make sure Day 1 is still fresh. Who can tell me what R.I.P.E. stands for? Drop it in the chat."**

- Wait 15–20 seconds. Read out a correct answer. Then confirm:

> 💬 **SAY:** **"Exactly — Repeatable, Information-Heavy, Pattern-Based, and Evaluable. That filter is your decision-making tool for the whole course. If a task checks those four boxes, it's a strong candidate for AI."**

> 💬 **SAY:** **"The Lifecycle gives us the method: Define the goal, Create and test, Refine by iterating, then Deploy. And the techniques — Persona, Few-shot, Chain-of-thought, Negative Prompting — are how we get better outputs at every stage."**

> 💬 **SAY:** **"And the guardrails at the bottom — hallucinations, context limits, automation complacency — we're going to see all three of these come up again today. Keep them in mind."**

---

---

## 📍 SECTION 2 — Today's Agenda & Objectives
### Slides 4–5 | 1:10 – 1:13 | 3 min

---

### Slide 4 — Agenda | 1:10 – 1:11

- Point to the progress timeline at the bottom. Show them where today's session sits in the full course arc.
- They're at the fourth stop: GenAI-Enhanced Communication, Strategies Planning, and Innovation.

> 💬 **SAY:** **"Today we're in the deep end — Communications, Strategies, Planning, and Innovation. This is where the theory from Day 1 becomes practical tools you can actually use at your desk."**

> 💬 **SAY:** **"Before we go anywhere — make sure your Zoom name is your first and last name. We're marking attendance based on that."**

---

### Slide 5 — Learning Objectives | 1:11 – 1:13

- Read each objective aloud and briefly explain what it means in practice.
- Make it tangible — connect each objective to something they already do.

> 💬 **SAY:** **"Objective one: enhance business writing. That means less time staring at a blank page and more time refining something that already exists."**

> 💬 **SAY:** **"Objective two: summarize content effectively. If you've ever had to read a 50-page report and pull out the five things that actually matter — AI can do that first pass for you."**

> 💬 **SAY:** **"Objective three: use AI to foster innovation. This one surprises people. We're not just talking about efficiency — we're talking about using AI to generate ideas and spot opportunities you might have missed."**

> 💬 **SAY:** **"By the end of today, you should be able to walk back to your desk and immediately apply at least one of these three things to your real work. That's the bar I'm setting for us."**

---

---

## 📍 SECTION 3 — Effective Business Writing
### Slides 6–15 | 1:13 – 1:28 | 15 min

---

### Slide 6 — Section Title | 1:13 – 1:14

- This is a transition slide. Use it to set up the section with energy.

> 💬 **SAY:** **"Let's start with something everyone in this room does every single day — writing. Emails, reports, Slack messages, proposals. And for most people, it takes longer than it should."**

---

### Slide 7 — Bill Birchard Quote | 1:14 – 1:15

- Read the quote aloud slowly. Pause after. Let it land.

> 💬 **SAY:** **"Strong writing skills are essential for anyone in business. You need them to effectively communicate with colleagues, employees, and bosses — and to sell any ideas, products, or services you're offering."**

- Then follow up:

> 💬 **SAY:** **"That's not an AI quote. That's a business writing expert. The point is — strong writing has always mattered. AI just changed how fast you can get to a strong first draft."**

- Ask the room: *"Quick show of hands — or drop a Y in chat — who feels like writing takes more of your time than it should?"*

---

### Slide 8 — LLM Use Cases Part 1 | 1:15 – 1:18

- Walk through each of the four use cases. Don't just read the bullets — explain what they mean practically.

> 💬 **SAY:** **"Content Generation — this is what most people think of first. You give AI an outline or a few bullet points, and it turns them into a full draft. You go from notes to narrative in seconds."**

> 💬 **SAY:** **"Text Processing is huge for knowledge workers. Condensing a 30-page report into a two-paragraph summary. Rewriting something that's too formal or too casual. Running sentiment analysis on customer feedback. Extracting key data and removing sensitive fields — all of this."**

> 💬 **SAY:** **"Multilingual capabilities mean you can communicate across language barriers without needing a translator on staff. This matters more and more as teams become global."**

> 💬 **SAY:** **"And Informed Decision-Making — this is AI answering your questions based on a document you've given it, with citations. Not making things up from its training data — actually grounding answers in your specific document."**

---

### Slide 9 — LLM Use Cases Part 2 | 1:18 – 1:20

- Continue the walkthrough. Keep the same pace.

> 💬 **SAY:** **"Interactive Communication — think simulated coaching dialogues for career conversations, or automated customer support that actually sounds human."**

> 💬 **SAY:** **"Creative Assistance — marketing copy, blog ideas, ad variants. If you're in a role that produces content regularly, this one is a serious time-saver."**

> 💬 **SAY:** **"Content Moderation keeps your external communications on-brand and professional without someone manually reviewing every post."**

> 💬 **SAY:** **"And Efficiency Tools — generating survey options, classifying and tagging content. The kind of repetitive cognitive work that eats an afternoon."**

> 💬 **SAY:** **"Here's the thing — these aren't theoretical examples. Every single one of these use cases maps to something you already do today at TradeStation. The question is just which ones you start with."**

---

### Slide 10 — Transition | 1:20 – 1:21

- Short transition. One line, then move.

> 💬 **SAY:** **"We could spend an hour on the full list. But let's zoom in on three specific examples so you can see exactly what these prompts look like in practice."**

---

### Slide 11 — Use Case: Creating First Drafts (Prompt) | 1:21 – 1:22

- Read the prompt aloud. Point to the key elements as you read.

> 💬 **SAY:** **"Look at this prompt. It's asking for a persuasive email — but notice what else it specifies: use my writing style, professional tone, keep it short and casual, offer an out, and make it persuasive. That's five instructions in one prompt."**

> 💬 **SAY:** **"The more specific your instructions, the less work you have to do on the other end. Vague prompt — vague output. Specific prompt — usable output."**

---

### Slide 12 — Use Case: Creating First Drafts (Output) | 1:22 – 1:23

- Point to the color-coded sections in the email response.

> 💬 **SAY:** **"Look at what came back. The green sections are the personalization gaps — the parts where the AI flagged that you need to fill in your specific context. The yellow section is the 'out' that was explicitly requested."**

> 💬 **SAY:** **"Notice what AI didn't do — it didn't write the final email. It wrote the first draft. Your job is to personalize those brackets. You focus on the purpose; let AI handle the drafting."**

---

### Slide 13 — Use Case: Scaling Up Content | 1:23 – 1:25

- Show the Facebook ad. Read the prompt.

> 💬 **SAY:** **"Here's a real example of content at scale. Instead of writing 10 ad variations yourself — which would take most people an hour — you give the model the original ad and ask for 10 alternatives. Then you evaluate. That's AI as a first-draft machine at scale."**

> 💬 **SAY:** **"And look at the instruction at the bottom: 'Take a deep breath and work step by step.' That's chain-of-thought prompting — we covered this on Day 1. You're telling the model to slow down and reason through the task rather than just blurting an answer."**

---

### Slide 14 — Use Case: Speaker Notes | 1:25 – 1:27

- Point to the Copilot interface shown on the right side of the slide.

> 💬 **SAY:** **"Here's a use case that's incredibly simple but saves a huge amount of time. You take a screenshot of a slide, upload it to Copilot, and ask it to generate structured speaker notes. That's it."**

> 💬 **SAY:** **"If you're building decks regularly, this one use case alone can save you an hour every time you prepare a presentation. And the format it follows is consistent — purpose, talking points, teaching tips — every single time."**

> 💬 **SAY:** **"We have a Pro Tip coming up later in the deck — you can save a custom instruction so you only need to type one word and attach a screenshot. The model already knows the format you want."**

---

### Slide 15 — Think About It | 1:27 – 1:28

- Quick engagement pulse. Give them 30 seconds then move.

> 💬 **SAY:** **"Before we jump into our first exercise — drop one answer in the chat: which of these use cases is most relevant to your role right now? Just one. I want to see what's landing."**

- Read 2–3 responses aloud. React briefly. Then transition.

> 💬 **SAY:** **"Great — hold on to that. We'll come back to it in the reflection. Now let's practice."**

---

---

## 📍 SECTION 4 — Exercise: Monzo Blog Post
### Slides 16–19 | 1:28 – 1:38 | 10 min 🟢

**⏱ Hard stop at 1:36 — debrief is more valuable than a perfect blog post.**

---

### Slide 16 — Section Title | 1:28 – 1:29

> 💬 **SAY:** **"Our first real exercise. We're going from a dry, corporate press release to a captivating blog post — and we're going to use Copilot to do most of the heavy lifting."**

---

### Slide 17 — The Brief | 1:29 – 1:31

- Explain who Monzo is before they try to write in their voice.

> 💬 **SAY:** **"Monzo is a UK-based digital bank — a neobank, which means no physical branches, everything is done through an app. But what makes Monzo famous isn't their technology. It's their communication. They write the way a real human talks. Plain English, no jargon, completely transparent with their customers."**

> 💬 **SAY:** **"Your mission is to take this incredibly dry press release about a new partnership with Experian — and transform it into a Monzo-style blog post that their customers would actually want to read."**

- Drop both links in Zoom chat NOW:

> 💬 **SAY:** **"I'm dropping two links in the chat right now. You need both. The press release is your content. The tone of voice guide is your brief. Put both of them into your Copilot prompt — don't skip the tone guide, that's what makes the difference."**

---

### Slide 18 — Exercise Instructions | 1:31 – 1:38

- Walk through the three instructions quickly, then let them work.

> 💬 **SAY:** **"Step one: craft a prompt that includes both the press release and the tone of voice guidelines. Step two: use prompting techniques we've covered — ask Copilot to break the process into steps, or give it an outline to follow. Step three: once you have a draft, refine it. Either iterate with Copilot or edit the prompt and run it again."**

> 💬 **SAY:** **"Bonus task if you finish early — ask Copilot to describe a concept image to accompany the blog post. You've got 7 minutes. Go."**

- Set a visible timer. Circulate in chat. Watch for interesting outputs to call out in debrief.

---

### Slide 19 — Debrief Discussion | 1:36 – 1:38

- Hard cut at 1:36. Call time and move to debrief.

> 💬 **SAY:** **"Pens down — let's see what you got. Who wants to share their output? Use the screenshot button in Zoom chat or just describe what Copilot gave you."**

- Take 1–2 responses. Then land the key insight:

> 💬 **SAY:** **"The goal here wasn't a perfect blog post. The goal was to see how much Copilot can do when you give it the right context — and to notice how much faster you got to a first draft than you would have writing it from scratch."**

- Run the three debrief questions quickly:

> 💬 **SAY:** **"Quick reflection — in the chat: did the brand voice hold? What strategy worked best? And what would you change about your prompt next time?"**

---

---

## 📍 SECTION 5 — Improving Clarity + Writing Assistant
### Slides 20–26 | 1:38 – 1:48 | 10 min

---

### Slide 20 — Section Title | 1:38 – 1:39

> 💬 **SAY:** **"Now let's talk about taking something that already exists and making it sharper. Not rewriting from scratch — improving what's already there."**

---

### Slide 21 — AI is Surprisingly Good at Improving Writing | 1:39 – 1:42

- Point to both sides of the before/after example on screen.

> 💬 **SAY:** **"Look at the left side. This is functional writing. It gets the job done. But it's flat, it's passive, and it doesn't pull you in."**

> 💬 **SAY:** **"Now look at the right side. Same information. But now it has energy. It moves. The language is active. It tells a story."**

> 💬 **SAY:** **"AI didn't change the meaning here — it improved the delivery. That is what improving clarity looks like in practice. And notice — the human still decides which version to use. The model gave options. You chose."**

---

### Slide 22 — Pro Tip: Regenerate Button | 1:42 – 1:43

- Quick but important tip. Land it clearly.

> 💬 **SAY:** **"Here's a practical habit that will immediately make your AI outputs better: use the Regenerate button. Every time you get a response, you can generate a second or third version and pick the best one. You're not locked into the first thing it gives you."**

> 💬 **SAY:** **"And rate the responses — thumbs up or down. That's called RLHF — Reinforcement Learning from Human Feedback. When you rate a response, you're contributing to how the model improves over time. It takes two seconds and it actually matters."**

---

### Slide 23 — Section Title: Writing Assistant | 1:43 – 1:44

> 💬 **SAY:** **"Now we're going to build something reusable. Not just a one-off prompt — an AI writing coach that you can come back to every time you need feedback on a document."**

---

### Slide 24 — Exercise Instructions | 1:44 – 1:45

- Walk through the three steps quickly before showing the prompts.

> 💬 **SAY:** **"The task is simple: choose a business document you'd like help with — could be an email, a report, a proposal, anything. Then choose one of the three coaching prompts on the next slide, run it in Copilot with your document, and then refine the prompt based on what you get. Your final refined prompt gets saved to your Copilot prompt library."**

---

### Slide 25 — Three Possible Prompts | 1:45 – 1:48

- Briefly describe each coach before they choose.

> 💬 **SAY:** **"Prompt one is Claire — a clarity editor. She's brilliant at spotting jargon and technical language that would confuse a non-specialist. Use her when you're writing something that crosses team boundaries or goes to senior stakeholders."**

> 💬 **SAY:** **"Prompt two is a communication consultant focused on active versus passive voice. Passive voice kills energy in writing. This coach will find every place you said 'it was decided' when you should have said 'we decided' — and explain why it matters."**

> 💬 **SAY:** **"Prompt three is the storytelling guru. She helps you find real-world analogies and examples that make your ideas land for a wider audience. Use this one when you're writing something that needs to persuade, not just inform."**

> 💬 **SAY:** **"Here's the key design pattern to notice across all three prompts: the AI introduces itself, explains what it's going to do — and then it WAITS. It doesn't pretend you've already shared the document. It doesn't fabricate feedback. It holds its position until you give it something real to work with. That's exactly the behavior you want from an assistant."**

- Give them 3 minutes to pick a prompt, run it, and save a refined version.

---

### Slide 26 — Reflection | 1:48 – 1:50

- Individual reflection. No need to collect — just prompt the thinking.

> 💬 **SAY:** **"Take 90 seconds. Three questions to sit with. Which documents in your regular work will you start enhancing? How has your view of AI in writing shifted since this morning? And what kind of writing coach would you design specifically for your own role — not one of the three we showed you, but one that's built for the way you actually work."**

> 💬 **SAY:** **"And if you only take one thing from this section — just one — let it be this: use AI to write your first draft. Then make it yours. Stop starting from a blank page."**

---

---

## 📍 SECTION 6 — Summarizing Content
### Slides 27–38 | 1:48 – 2:00 | 12 min

---

### Slide 27 — Section Title | 1:50 – 1:51

> 💬 **SAY:** **"Now let's talk about one of the highest-leverage things you can do with AI in a knowledge-work environment — summarizing large amounts of content quickly and accurately."**

---

### Slide 28 — Context Windows: Size Matters | 1:51 – 1:54

- Point to the chart. Call out the top models.

> 💬 **SAY:** **"This chart shows the context window sizes of the leading AI models as of late 2025. Meta Llama 4, GPT-4.1, Google Gemini, and Claude Sonnet 4 are all up at around one million tokens. That's an enormous amount of text."**

> 💬 **SAY:** **"The context window is the model's working memory. Think of it like this: if you give a model a 200-page document and its context window is too small, it will start forgetting the beginning by the time it reaches the end — like trying to hold a full conversation while someone keeps whispering new information in your ear."**

> 💬 **SAY:** **"The larger the context window, the more of your document the model can actually hold in mind at once — and the more accurate and complete your summary will be."**

---

### Slide 29 — Think About It: Context Windows | 1:54 – 1:55

- Quick engagement beat before moving to real cases.

> 💬 **SAY:** **"Here's a question to think about — and drop your answer in the chat: what problems might a very large context window create?"**

- Wait 20 seconds. Read answers. Good ones to call out: attention dilution, slower processing, higher API cost, privacy risk if sensitive data is accidentally included.

> 💬 **SAY:** **"All of those are real. Bigger isn't always better — it depends on the task and the risk profile of your data."**

---

### Slide 30 — Real Life Examples (Title) | 1:55 – 1:56

> 💬 **SAY:** **"Let's look at how this is being used in the real world — both the wins and the cautionary tales."**

---

### Slide 31 — Real Cases: Meeting Summaries | 1:56 – 1:57

- Walk through the three-step workflow shown on the slide.

> 💬 **SAY:** **"Here's a workflow many teams are already running. Step one: transcribe the meeting — Google Meet, Zoom, Teams all have this built in. Step two: the transcript lands in your email or Drive. Step three: you paste it into Copilot with a prompt asking for a summary and action items."**

> 💬 **SAY:** **"The collaborative approach is the key insight here. AI writes the first pass. A human verifies the action items. Neither alone is as reliable as both working together. The model can miss nuance, misattribute a comment, or confuse a question for a commitment. Your eye is the quality check."**

---

### Slide 32 — Meeting Summaries: Take Caution | 1:57 – 1:58

- Slow down here. This slide matters.

> 💬 **SAY:** **"This is a real story and it happened fast. Samsung engineers were using ChatGPT to help with their work — and within weeks, proprietary information about their semiconductor operations had been pasted into the model and was now potentially part of its training data."**

> 💬 **SAY:** **"Never paste proprietary, confidential, or personally identifiable information into a public AI tool. Not meeting transcripts with client names. Not financial projections. Not internal strategy documents. Always check your company's AI policy before you upload anything."**

> 💬 **SAY:** **"If you're not sure whether something is sensitive — assume it is, and check first."**

---

### Slide 33 — Real Cases: AI for Legal Teams | 1:58 – 1:59

- Ironclad story — this one is a win.

> 💬 **SAY:** **"On the positive side — Ironclad built an AI contract review tool called AI Assist using GPT-4. It automatically flags irregularities in contracts, suggests standard clauses, and reduces review time from 40 minutes to 2 minutes. That's a 95 percent time saving."**

> 💬 **SAY:** **"But here's the part that matters: Ironclad was explicit that the goal was to augment legal professionals, not replace them. Human oversight remained critical at every step. AI Assist doesn't sign off on contracts — lawyers do."**

> 💬 **SAY:** **"AI is not replacing legal professionals here. It's giving them a junior analyst that never gets tired. But the human still makes every final call."**

---

### Slide 34 — Disclaimer | 1:59 – 2:00

- Read this briefly and move on — it's important but not a discussion point.

> 💬 **SAY:** **"Quick note before we practice with legal documents — everything in this section is for educational purposes only. AI output is not legal advice, it doesn't create an attorney-client relationship, and it should never be used as a substitute for qualified legal counsel. We're using this as a learning example, not a production workflow."**

---

### Slide 35 — What It All Means | 2:00 – 2:01

> 💬 **SAY:** **"So what's the takeaway? Generative AI is not a replacement for legal professionals. But it is a powerful tool that can make legal documents more accessible to more people — and free up highly qualified people to focus on the work that actually requires their expertise."**

---

### Slides 36 — Section Title: Large Document Summary | 2:01 – 2:01

> 💬 **SAY:** **"Let's put this into practice. Open a new chat window in Copilot — not your existing one, a fresh one — and get your Large PDF ready."**

---

### Slide 37 — Solo Exercise: Large Document Summary | 2:01 – 2:06

- Set up the exercise clearly before letting them loose.

> 💬 **SAY:** **"Upload the Large PDF To Summarize file — you should have downloaded it earlier. This is a research paper titled 'The Dawn of LLMs: Preliminary Explorations with GPT-4 Vision.'"**

> 💬 **SAY:** **"Your starting prompt is on the slide: summarize this paper for my Product Development team via a Slack message. Include all the practical, applicable learnings. Finish with the three most important takeaways. That's your baseline."**

> 💬 **SAY:** **"Once you have that — try one of the extensions. Summarize it for three completely different audiences: a ten-year-old, a university student, and your sales team. Or convert it into a Twitter thread, an FAQ, or a LinkedIn post. You have 5 minutes."**

- Let them work. After time:

> 💬 **SAY:** **"The same document, three completely different outputs. That's the power of audience-aware prompting. You're not changing the content — you're changing who it's for, and the model adjusts everything: vocabulary, structure, tone, length."**

> 💬 **SAY:** **"Who found something surprising or unexpected in their summary? Drop it in the chat or share your screen."**

---

### Slide 38 — Reflection: Summarizing Content | 2:06 – 2:07

- 60-second reflection pause before the next section.

> 💬 **SAY:** **"Three questions to hold onto as we move forward: How do you see yourself using AI summarization in your actual work? What challenges do you anticipate — accuracy, trust, privacy? And is there a specific part of your role where this would have immediate impact?"**

---

---

## 📍 SECTION 7 — Fostering Innovation
### Slides 39–49 | 2:00 – 2:10 | 10 min

---

### Slide 39 — Section Title | 2:07 – 2:08

> 💬 **SAY:** **"Now we're going to shift gears. We've talked about writing and summarizing — both of which make existing work faster. Now let's talk about using AI to generate things that didn't exist before. Innovation."**

---

### Slide 40 — Three Areas of Innovation | 2:08 – 2:09

- Show the three boxes: Product, Service, Process.

> 💬 **SAY:** **"There are three areas where organizations typically innovate: their products, their services, and their internal processes. AI has a role to play in all three — but most teams start with just one."**

> 💬 **SAY:** **"Every role in this room touches at least one of these three areas. Your job for the next few minutes is to figure out which one AI can accelerate first for you."**

---

### Slide 41 — Three Areas (Product Highlighted) | 2:09 – 2:10

- Brief transition. Just name it and move to the evidence.

> 💬 **SAY:** **"Let's start with Product innovation — because this is where the research gets interesting."**

---

### Slide 42 — Product Innovation: Acing the Test | 2:10 – 2:12

- This is the study that surprises people. Let the data land.

> 💬 **SAY:** **"A controlled study put AI up against business students in an idea generation contest. Human judges rated the ideas on quality and purchase intent — and here's what they found: of the 40 best ideas in the entire competition, 35 came from GPT-4. Not 35 percent. 35 out of 40."**

> 💬 **SAY:** **"And outside judges showed higher purchase intent for the AI-generated ideas than the human ones."**

> 💬 **SAY:** **"This doesn't mean AI replaces creative thinking. It means AI raises the floor. It gives you more raw material to react to, critique, and build on. Your judgment, your context, your taste — that's still the differentiator. But you're starting from a much richer starting point."**

---

### Slide 43 — Section Title: Let's Practice | 2:12 – 2:12

> 💬 **SAY:** **"Let's put that to the test. Five minutes — you're generating product ideas."**

---

### Slide 44 — Solo Challenge: Product Innovation | 2:12 – 2:17

- Set up quickly then let them run.

> 💬 **SAY:** **"Here's your prompt — it's on the slide. You're asking Copilot to generate 15 distinct product ideas for your industry. For each idea, it scores 1 to 10 on feasibility, competition, and success potential. Then it ranks all 15 and creates photorealistic concept images of the top 4."**

> 💬 **SAY:** **"The key is to adapt this to your own industry. If you work in financial services, make it relevant to traders or investors. If you're in a support role, think about tools that would serve your customers. Make it real."**

> 💬 **SAY:** **"And if image generation gives you a 'Load failed' error — hit Regenerate. It's occasionally buggy. That is real-world AI."**

- After 5 minutes:

> 💬 **SAY:** **"Who got something interesting? Use the screenshot button in Zoom chat or share your screen. I want to see what came up."**

---

### Slide 45 — Three Areas (Service Highlighted) | 2:17 – 2:18

> 💬 **SAY:** **"Now let's look at Service innovation — using AI to improve the experience you deliver to customers."**

---

### Slide 46 — Service Innovation: Delivery | 2:18 – 2:19

- Brief overview — don't dwell. The practice comes in a separate exercise.

> 💬 **SAY:** **"Here's an example: a grocery delivery company ran a customer interview and used AI as a consultant to analyze what they heard. The prompt is simple — you are an expert consultant, here is the interview transcript, give me a step-by-step plan for how to innovate based on this."**

> 💬 **SAY:** **"What you get back is a structured innovation roadmap built directly from customer language. Not market research reports. Not surveys. A real conversation — turned into a strategic brief."**

---

### Slide 47 — Three Areas (Process Highlighted) | 2:19 – 2:20

> 💬 **SAY:** **"And finally — Process innovation. This is often where people find the fastest, most immediate wins."**

---

### Slide 48 — Process Innovation: Make It Make Sense | 2:20 – 2:21

- Show the NHS patient care pathway diagram.

> 💬 **SAY:** **"Look at this process map. This is the workflow for a patient with a kidney condition in the UK's National Health Service. Count the steps. Count the handoffs. Count the delays."**

> 💬 **SAY:** **"Complex, multi-step processes with delays and human handoff points are exactly where AI spots inefficiencies you've stopped seeing — because you're too close to the work to notice them anymore."**

> 💬 **SAY:** **"You can upload a process map, describe a workflow in words, or share a transcript of how your team operates — and ask AI to identify the bottlenecks, redundancies, and automation opportunities. It will find things you've normalized."**

---

### Slide 49 — Key Takeaways | 2:21 – 2:22

- Land all three before moving on. These are the thesis of the Innovation section.

> 💬 **SAY:** **"Three things to take from this section. One: focus on purpose, not drafting. AI is a great starting point — but it should never speak for you."**

> 💬 **SAY:** **"Two: keep the human in the loop. Make the tone and voice your own. Let AI do the drafting, then you own the output."**

> 💬 **SAY:** **"Three: think Product, Service, Process. Pick one. Start there. That's your entry point into AI-driven innovation."**

---

---

## 📍 SECTION 8 — Data Analysis & Workflow Automation
### Slides 50–65 | 2:10 – 2:20 | 10 min

---

### Slide 50 — Section Title | 2:22 – 2:23

> 💬 **SAY:** **"Last major section. We're going into data — and I know that word makes some people nervous. I want to tell you upfront: you do not need to be a data analyst for this section. You just need to know how to ask good questions."**

---

### Slide 51 — Learning Objectives | 2:23 – 2:24

> 💬 **SAY:** **"Three things we're covering: using AI to perform data analysis and discovery, identifying trends and insights, and generating visualizations. All of it through natural language prompts — no code required from you."**

---

### Slide 52 — How Copilot Uses Python | 2:24 – 2:25

> 💬 **SAY:** **"Here's what's actually happening behind the scenes when you ask Copilot a data question. It writes Python — a programming language — to answer you. You type a question in plain English, it translates that into code, runs the code, and gives you back the result."**

> 💬 **SAY:** **"Copilot writes the Python for you. You don't need to code. But knowing what it's doing helps you ask better questions, spot when something looks wrong, and know when to trust — or challenge — the output."**

---

### Slide 53 — Python in Action | 2:25 – 2:26

- Point to the code visible in the interface screenshot.

> 💬 **SAY:** **"This is what it looks like. You ask 'What's the average hourly compensation?' — and behind the scenes, Copilot writes a few lines of Python, loads your data file, calculates the average, and gives you the number. You never see the code unless you ask for it."**

> 💬 **SAY:** **"The practical implication: when Copilot shows you a number or a calculation, it actually ran the math. It didn't guess. That's important — and it's also why we'll talk about verification in a few slides."**

---

### Slide 54 — What Is Python? | 2:26 – 2:27

> 💬 **SAY:** **"Python is a programming language that's easy to read, built for real-world problem solving, and is the most widely used language in data science and AI. Think of it as a toolbox — full of pre-built shortcuts for common data tasks."**

> 💬 **SAY:** **"You don't need to learn Python to use Copilot. But knowing it exists — and knowing Copilot is using it — helps you understand why the outputs are as reliable as they are."**

---

### Slide 55 — Why Should You Care? | 2:27 – 2:28

> 💬 **SAY:** **"The left side of this slide is about what Python does for you through Copilot: load and clean data, calculate statistics, spot patterns like outliers or duplicates. The right side is about what understanding this gives you: the ability to ask more specific questions, catch when something seems off, and trust the outputs more."**

> 💬 **SAY:** **"You don't have to write Python. But if you understand how Copilot uses it, you become a smarter user — and a better skeptic."**

---

### Slide 56 — Python Libraries | 2:28 – 2:29

> 💬 **SAY:** **"Python libraries are pre-written code modules that Copilot can draw on. Instead of building everything from scratch, developers — and AI — use these like a toolbox. NumPy for numbers, Pandas for data tables, Flask for web apps."**

> 💬 **SAY:** **"The key point here is that this is a mature, well-tested ecosystem. When Copilot uses Pandas to analyze your spreadsheet, it's using the same tools that data scientists at major companies use every day."**

---

### Slide 57 — Use Cases for Python Libraries | 2:29 – 2:30

> 💬 **SAY:** **"This slide shows you the range of what's possible: text analysis, image processing, computer vision, machine learning, data visualization, data analysis. The point isn't to memorize this — it's to understand that when you ask Copilot to do something data-related, there's almost certainly a library built for exactly that."**

---

### Slide 58 — Libraries You Can Ask Copilot to Use | 2:30 – 2:31

> 💬 **SAY:** **"You can actually tell Copilot which library to use — and you don't need to be an expert to do it. If you want interactive charts, ask it to use Plotly. If you want a map visualization, ask for Folium. If you want machine learning, ask for scikit-learn."**

> 💬 **SAY:** **"You're not writing the code — you're directing the work. That's a meaningful shift in what non-technical people can do with data."**

---

### Slide 59 — What Is EDA? | 2:31 – 2:32

> 💬 **SAY:** **"EDA stands for Exploratory Data Analysis. And I want to demystify this immediately — EDA is just getting to know a dataset. What's in it, how big is it, are there patterns, are there problems."**

> 💬 **SAY:** **"You don't need to be a data scientist to do EDA with AI. You just need to be curious and willing to ask questions. The model does the analysis. You ask the questions."**

---

### Slide 60 — Guided Walkthrough: EDA | 2:32 – 2:37

- This is a live demo. Set it up carefully.

> 💬 **SAY:** **"Open a new Copilot chat window — fresh, not your existing one. Upload the productivity_n_hourly_compensation CSV file. Then ask it: 'Can we do exploratory data analysis on this dataset?' Just that. See what happens."**

- Walk through the steps on the slide as a class:

> 💬 **SAY:** **"Start with that opening question. Then prompt for further exploration. Then ask for the top five insights. And finally — ask for suggestions on what actions policymakers could take based on those insights."**

> 💬 **SAY:** **"Notice how we're layering the questions. We're not asking for everything at once. We're building a conversation — each question informed by the last answer. That's how you get depth from a data analysis session."**

---

### Slide 61 — Remember: There Are Risks | 2:37 – 2:38

- Pause here. Lower the energy slightly. This is a serious slide.

> 💬 **SAY:** **"Before we go further — this slide is here for a reason. I need you to hear this."**

---

### Slide 62 — Hallucinations + Data Analysis | 2:38 – 2:39

> 💬 **SAY:** **"AI hallucination in a writing task means you get a slightly awkward sentence. AI hallucination in a data analysis task means you get a fabricated number that looks completely real — and you might present it to a senior leader as fact."**

> 💬 **SAY:** **"This has serious implications. Copilot — and every other LLM — can and will generate plausible-looking data that simply does not exist in your file. It's not malicious. It's how these models work. But the consequences are real."**

---

### Slide 63 — Hallucinations + Data (Detail) | 2:39 – 2:40

- Three rules. Say them clearly. Slowly.

> 💬 **SAY:** **"Three rules when using AI for data analysis. One: Copilot may generate fake data that it needs to complete your request — it fills gaps it can't answer with plausible-sounding fabrications."**

> 💬 **SAY:** **"Two: Copilot will often hint that it's doing this — a small qualifier, a caveat buried in the response. But it's easy to miss, especially if you're scanning quickly."**

> 💬 **SAY:** **"Three — and this is the most important: document that you used AI whenever you're working with data. Especially if you're not a data professional. Always sanity-check key numbers against your source file before you share anything."**

---

### Slide 64 — Think About It: Worst Case Scenarios | 2:40 – 2:41

- Quick engagement. One minute.

> 💬 **SAY:** **"Quick thought exercise — drop one answer in the chat: what's the worst thing that could realistically happen if someone at your company used Copilot for data analysis without proper verification?"**

- Read 2 answers. React. Then move on.

---

### Slide 65 — Visualization Quote | 2:41 – 2:42

- Close the data section on an inspiring note.

> 💬 **SAY:** **"I want to leave you with this thought from Ben Schneiderman, a Stanford computer science professor: 'Visualization gives you answers to questions you didn't know you had.'"**

> 💬 **SAY:** **"That's the real promise of AI-assisted data analysis. Not just answering the questions you came in with — but surfacing the questions you didn't know to ask."**

---

---

## 📍 SECTION 9 — Wrap-up & Exit Ticket
### Slides 66–72 | 2:20 – 2:25 | 5 min

---

### Slide 66 — Section Title | 2:42 – 2:43

> 💬 **SAY:** **"We're in the final stretch. Let me bring it all together."**

---

### Slide 67 — Let's Reflect | 2:43 – 2:44

> 💬 **SAY:** **"Before I give you the closing principles — take 30 seconds. What's the one thing from today that you're actually going to try this week? Just one thing. Hold it in your head."**

---

### Slide 68 — Four Closing Principles | 2:44 – 2:47

- These are the thesis statements of the entire course. Say each one with weight.

> 💬 **SAY:** **"Principle one: AI is your partner, not your replacement. Use it to augment your work — but retain your judgment. The model accelerates the work. You own the outcome."**

> 💬 **SAY:** **"Principle two: Ethics matter. Bias, transparency, and privacy are not the AI's responsibility — they're yours. Human oversight is not optional. It's the whole point."**

> 💬 **SAY:** **"Principle three: Small steps equal big impact. Don't try to automate your entire job this week. Start with one task. One prompt. One experiment. See what you learn. That compounds."**

> 💬 **SAY:** **"Principle four: Better prompts equal better results. That is a real, learnable, improvable skill. And like every skill — the only way to get better is to practice. Every day."**

---

### Slide 69 — Next Steps | 2:47 – 2:49

> 💬 **SAY:** **"Three things I want you to do after this call. First — try it this week. Pick one use case from today that's relevant to your role and actually run it through Copilot. Don't wait for the perfect moment."**

> 💬 **SAY:** **"Second — spread the word. If today was useful, tell a colleague. Share what you learned. The more your team understands this, the more you can all do together."**

> 💬 **SAY:** **"Third — stay curious. We covered a lot today, but we barely scratched the surface. GA has deeper programs if you want to go further. The question isn't whether AI will affect your work — it already is. The question is whether you're going to be someone who shapes that, or someone who reacts to it."**

---

### Slides 70–72 — Exit Ticket | 2:49 – 2:52

- Drop the correct survey link in Zoom chat. Double-check which cohort you're in — there are three different links across Slides 70/71/72.

> 💬 **SAY:** **"I'm dropping the feedback survey link in the chat right now. Please take two minutes to complete it before you close Zoom. Your feedback directly shapes how this program evolves — and it takes less time than your average Slack thread."**

> 💬 **SAY:** **"It's been a pleasure today. You asked great questions, you pushed the exercises, and you're walking away with real tools. Thank you for your time and attention — now go use this stuff."**

---

---

## 🔴 Must-Say Lines — Use at Any Point

If you lose your place, feel energy dropping, or need to re-anchor — come back to one of these:

> **"AI is a great starting point — but it should never speak for you."**

> **"The R.I.P.E. filter tells you where to start. Your judgment tells you where to stop."**

> **"Never paste proprietary or confidential information into a public AI tool."**

> **"The human is always in the loop. AI accelerates the work — it doesn't own the outcome."**

> **"Better prompts equal better results. That is a skill. And like all skills, it gets better with practice."**

> **"You focus on the purpose. Let AI handle the drafting."**

> **"Same document, three completely different outputs. That is audience-aware prompting."**

> **"This doesn't mean AI replaces creative thinking. It means AI raises the floor."**

---

## ⚠️ Timing Traps & Recovery Moves

| Risk | What To Do |
|---|---|
| Monzo exercise runs long | Hard cut at 1:36 — debrief beats polish every time |
| Samsung / hallucination discussion spirals | *"Great point — let's hold that for Q&A"* and move on |
| Python background (Slides 52–58) runs long | Compress to 2 min — EDA demo is the priority |
| Students stuck on Copilot login | Keep moving — they can follow on a neighbour's screen |
| Copilot image generation fails | *"Hit Regenerate — that's real-world AI right there"* |
| Running 5+ min behind at any point | Skip Slides 34–35 and 54–58, go straight to exercises |

---

## 📋 Quick Reference Card

```
1:00  Warm-up + attendance check
1:06  Day 1 review (ask, don't lecture)
1:13  Business writing section
1:20  Walk use cases: 8 examples across 2 slides
1:28  🟢 EXERCISE: Monzo blog (hard stop 1:36)
1:38  Improving clarity + before/after
1:43  🟢 EXERCISE: Writing assistant (save to prompt library)
1:50  Context windows + real cases
1:57  ⚠️  Samsung warning — slow down, say it clearly
2:01  🟢 SOLO: Large document summary
2:07  Innovation: Product → Service → Process
2:12  🟢 SOLO: Product innovation (5 min)
2:22  Data analysis section
2:32  🟢 EDA walkthrough (live demo)
2:39  ⚠️  Hallucinations warning — say the 3 rules
2:44  Wrap-up: 4 closing principles
2:49  🔴 EXIT TICKET — drop survey link in chat NOW
2:52  Done
```

---

*Last updated: Day 2, Q1 2026 — TradeStation × General Assembly*
