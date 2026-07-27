<div align="center">

<img src="./assets/ai_seekho_banner.png" alt="AI SEEKHO - UMT Inter AI Club" width="600"/>

<br/>

![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=28&pause=1000&color=1E4FB8&center=true&vCenter=true&width=600&lines=Learn+AI.+Build+with+AI.;Prompt+Engineering+%F0%9F%A7%A0;Cursor+%2B+Claude+%2B+Copilot+%F0%9F%9A%80;8+Weeks+%7C+16+Sessions+%7C+7+Guest+Speakers)

<br/>

![Program](https://img.shields.io/badge/Program-AI%20SEEKHO-1E4FB8?style=for-the-badge&logo=googlebard&logoColor=white)
![Club](https://img.shields.io/badge/Club-Inter%20AI%20Club%20UMT-black?style=for-the-badge)
![Office](https://img.shields.io/badge/Presented%20by-UMT%20%7C%20OPA-4285F4?style=for-the-badge)
![Weeks](https://img.shields.io/badge/Duration-8%20Weeks-success?style=for-the-badge)
![Sessions](https://img.shields.io/badge/Sessions-16-orange?style=for-the-badge)
![Speakers](https://img.shields.io/badge/Guest%20Speakers-7-red?style=for-the-badge)

</div>

<br/>

# 📅 Session 1 · Week 1
## The AI-First Developer Mindset and Environment Setup

<div align="center">

| 👤 Student | 🎓 Roll Number | 👨‍🏫 Instructor |
|:---:|:---:|:---:|
| **Abdul Hadi** | **F2025376179** | **Sir Umar** |

</div>

<br/>

![divider](https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif)

## 📌 Table of Contents

- [Session Overview](#-session-overview)
- [The Big Shift: Why the Market Changed](#-the-big-shift-why-the-market-changed)
- [🧠 Deep Dive: Prompt Engineering](#-deep-dive-prompt-engineering)
- [🛠️ AI Tool Landscape](#️-ai-tool-landscape-compared)
- [⚙️ Environment Setup Checklist](#️-environment-setup-checklist)
- [📚 Case Study](#-case-study-context-is-everything)
- [✅ Practical Task Completed](#-practical-task-completed)
- [🔗 References](#-references)

---

## 🧭 Session Overview

| | |
|---|---|
| **Type** | Core teaching session |
| **Goal** | Get everyone on the same tools, and set the mental model for the next 8 weeks |
| **Format** | Live setup walkthrough — everyone follows along in real time |

Before diving into building anything, this session was about answering one question: *why* are we even learning this way? Once that clicked, the rest — tools, prompting, setup — followed naturally.

---

## 💡 The Big Shift: Why the Market Changed

- **2021 Junior Dev Day:** boilerplate code, simple bug fixes, endless Stack Overflow tabs, waiting on senior review.
- **2026 Entry-Level Expectation:** know how to *direct* AI tools to do that boilerplate work instantly, and instead focus on judgment, architecture, and debugging *AI-generated* code.
- **The gap didn't disappear** — it got filled by AI. Which means this program isn't optimizing for "can you type code fast." It's optimizing for **AI fluency + engineering judgment**.

> 🔑 **Key takeaway:** The tools changed the job. So the training has to change too.

---

## 🧠 Deep Dive: Prompt Engineering

This was the heart of today's session. Prompt engineering isn't a "trick" — it's a **skill with real components**, and each one changes the quality of what you get back from an AI tool.

### 1️⃣ Role Prompting
Telling the AI **what kind of expert** to respond as changes its entire frame of reference.

```
❌ "How do I structure this API?"
✅ "You are a senior backend engineer specializing in REST API design.
    Review this endpoint structure and suggest improvements."
```
**Why it matters:** Role prompting narrows the AI's "mental model," so it pulls from more relevant patterns and skips generic answers.

### 2️⃣ Giving Real Context
The single biggest lever for output quality. Never *describe* a bug — **paste the real thing.**

```
❌ "My app crashes when I click submit, it says something about undefined."
✅ [Pastes actual stack trace]
   [Pastes the exact 3 lines of relevant code]
   "Why is this throwing, and how do I fix it?"
```
**Why it matters:** AI models are pattern matchers over the literal text you give them. Vague descriptions = vague, often wrong, answers.

### 3️⃣ Few-Shot Prompting
Show **one solid example** of the format/style you want before asking for more.

```
Example:
Input: "apple" → Output: {"fruit": "apple", "color": "red"}
Now do the same for: "banana", "grape", "blueberry"
```
**Why it matters:** One good example removes ambiguity that a paragraph of instructions can't.

### 4️⃣ Iterative Refinement
Don't accept the first draft. Ask the AI to **critique its own output** before you commit to it.

```
"Review the code you just wrote. Are there edge cases you missed?
 Is there a cleaner way to handle the error states?"
```
**Why it matters:** This single step catches a huge percentage of subtle bugs and lazy first-pass solutions — the AI is often a better critic of itself than a first-time writer.

### 🧩 The Prompt Engineering Formula (my own summary)

```
GOOD PROMPT = Role + Real Context + Example (if needed) + Ask for Self-Critique
```

---

## 🛠️ AI Tool Landscape, Compared

| Tool | Best For | Weakness |
|---|---|---|
| **GitHub Copilot** | Inline autocomplete, boilerplate | Weak at multi-file, big-picture changes |
| **Cursor IDE** | Chat + multi-file editing, reads whole codebase | Needs a decent prompt to shine |
| **Claude / ChatGPT** | Reasoning through problems, explaining errors, architecture discussions | Doesn't run code or touch your repo directly |
| **Windsurf** | Agentic — runs terminal commands, iterates on its own | Needs supervision, can go off-track unsupervised |

> 🧭 **My takeaway:** Copilot = fast typist. Cursor = pair programmer. Claude/ChatGPT = the senior dev you talk architecture with. Windsurf = the intern you *still* have to check on.

---

## ⚙️ Environment Setup Checklist

- [x] Installed **Node.js LTS**, verified with:
  ```bash
  node -v
  npm -v
  ```
- [x] Installed and configured **Cursor IDE**
- [x] Generated an **SSH key**:
  ```bash
  ssh-keygen -t ed25519 -C "your_email@example.com"
  ```
  → Added public key to **GitHub → Settings → SSH and GPG Keys**
- [x] Created my **first repository** (AI_Sikho 👋)
- [x] Cloned it locally, made my **first commit**, and pushed it
- [x] Set up `.gitignore` basics:
  ```gitignore
  node_modules/
  .env
  build/
  dist/
  ```

### 👤 GitHub Profile Setup
- [x] Added a short **bio + skills section** to my profile README
- [x] Pinned **2–3 repositories** so my profile doesn't look empty

---

## 📚 Case Study: Context Is Everything

We compared two real prompts asking for the *exact same fix*:

**Prompt A (bad):**
> "fix this"
*(no error message, no code attached)*

**Prompt B (good):**
> *[Full stack trace pasted]*
> *[The 3 relevant lines of code pasted]*
> "This is throwing a TypeError — why, and how do I fix it cleanly?"

**Result:** Prompt A got a generic, mostly useless guess. Prompt B got a precise, correct fix in one shot — because the AI wasn't guessing anymore, it was *reasoning* over real evidence.

> 🧾 **Lesson learned:** The AI is only as good as the context you feed it. "Fix this" is not a prompt — it's a wish.

---

## ✅ Practical Task Completed

By the end of Session 1, I had:
1. ✅ Cursor IDE installed and configured
2. ✅ SSH authentication working with GitHub
3. ✅ First commit pushed to this repo — using an **AI-assisted change**

---

## 🔗 References

**Primary**
- [Cursor Docs](https://cursor.com/docs)
- [GitHub SSH Setup Docs](https://docs.github.com)
- [Claude Prompt Engineering Guide](https://docs.claude.com/en/docs/build-with-claude/prompt-engineering/overview)

**Secondary**
- [OpenAI Prompt Engineering Guide](https://platform.openai.com/docs/guides/prompt-engineering)

**Tertiary (optional)**
- Any recent Cursor setup walkthrough on YouTube (for installation troubleshooting)

---

<p align="center">
  <i>📈 Session 1 of 16 — AI SEEKHO by UMT Inter AI Club</i>
</p>
