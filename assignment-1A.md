# AI SEEKHO — Assignment 1A
**AI Club UMT | Session 1**

---

## Part 1 — Agentic IDE Research

### 1. Cursor
Cursor is an AI-first code editor built by Anysphere, forked from VS Code. It gives you an "agent mode" that can read your whole codebase, make multi-file edits, and run terminal commands with your approval. It indexes your repo locally so it understands context across files instead of just the open tab, and it supports MCP servers so you can plug in external tools. Pricing runs on a free tier plus paid plans (Pro/Business) with usage-based limits on premium model calls. Its biggest differentiator is how deeply it's built *as an editor first* — it feels like VS Code with AI baked into the core, not bolted on.

**My take:** Great for people who already live in VS Code-style editors and want AI that feels native rather than like a sidebar plugin. Weak spot is cost creeping up fast if you lean on premium models heavily.

### 2. Claude Code
Claude Code is Anthropic's agentic coding tool, usable from the terminal, IDE extensions, or desktop/mobile apps. It's built to delegate real engineering work — refactors, debugging, multi-step tasks — with strong terminal access and the ability to plan before executing. It supports MCP natively, so it can connect to GitHub, Slack, databases, etc. It's priced through Anthropic's API/subscription plans rather than a separate IDE license.

**My take:** Its strength is reasoning through messy, multi-step problems and explaining its plan before touching code, which builds trust. Limitation: it's tool-based rather than a full IDE replacement, so some devs pair it with an editor.

### 3. Antigravity (Google)
Antigravity is Google's agentic development environment, designed around Gemini models with deep integration into Google's ecosystem (Cloud, Workspace, etc.). It focuses on autonomous multi-file task execution and long-running agent sessions. Its key differentiator is native Google Cloud/infra integration, useful if your stack already lives there.

**My take:** Best suited for teams already committed to Google's cloud ecosystem; less compelling if you're multi-cloud or model-agnostic.

### 4. Codex (OpenAI)
Codex is OpenAI's coding agent, available via ChatGPT, CLI, and IDE extensions. It can work in sandboxed cloud environments to write, test, and fix code autonomously, and integrates with GitHub for PR-style workflows. Pricing is bundled into ChatGPT Plus/Pro/Team plans or billed via API usage. Its differentiator is the sandboxed cloud execution model — it can run and verify code changes in an isolated environment before handing them back.

**My take:** Strong for "fire and forget" tasks where you want a verified working patch back. Less ideal when you want to closely steer every step interactively.

### 5. Windsurf (Codeium)
Windsurf is Codeium's agentic IDE, built around a "Cascade" agent that keeps a live understanding of your whole project as you edit. It offers multi-file edits, terminal access, and a generous free tier compared to competitors. Its differentiator is the flow-based UX — it's designed to feel less like "chatting with AI" and more like the AI is quietly pair-programming alongside you in real time.

**My take:** Good entry point for students/beginners because of the free tier and smooth UX; still catching up to Cursor/Claude Code on very large, complex codebases.

---

## Part 2 — Prompt Engineering: Real-Life Scenarios

### Scenario 1: The Budget Trip
**Role:** Act as an experienced budget travel planner familiar with Pakistan.
**Context:** I have PKR 15,000 total, 3 free days, and I'm traveling with 2 friends (3 people total). We can't ask parents for extra money, so everything — transport, stay, food — must fit inside this budget for all three of us combined.
**Main:** Suggest one realistic destination (mountains, city, or coast) reachable within budget, then build a day-by-day itinerary covering transport options, budget-friendly stays, and cheap-but-good food spots.
**Conclusion:** Give me the answer as a day-wise table with a running cost total, in simple casual language, so I can share it directly with my friends.

### Scenario 2: The Difficult Message
**Role:** Act as a calm, assertive communication coach who's good at tenant-landlord conflicts.
**Context:** My water heater has been broken for 2 weeks. I've already asked my landlord twice verbally with no action, winter is coming, and I plan to renew my lease so I don't want to damage the relationship.
**Main:** Write a firm but respectful message (I'll send it via WhatsApp or email) that clearly states the issue, references the previous requests, and asks for a fix by a specific date, without sounding aggressive.
**Conclusion:** Give me one WhatsApp version (short, direct) and one email version (slightly more formal), each under 120 words.

### Scenario 3: The Impossible Schedule
**Role:** Act as a productivity coach who designs realistic schedules for burnt-out students.
**Context:** I'm a 6th-semester student with 5 courses, a part-time job (15 hrs/week), a side project due in 3 weeks, and I want to start gym 4x/week. I've failed at every schedule I've tried so far, usually because I ignore my actual energy levels.
**Main:** Design a weekly timetable that blocks time for classes, job, project, and gym, but is built around realistic energy dips (e.g., low energy after work, best focus in mornings), not just empty hour slots.
**Conclusion:** Present it as a simple weekly table (Mon–Sun, morning/afternoon/evening), with short notes on why each slot is placed there.

### Scenario 4: The Broke Student Meal Plan
**Role:** Act as a nutritionist who specializes in cheap, practical student meals.
**Context:** I have PKR 8,000/month for food, I cook in a shared hostel kitchen with only a stove and a small fridge (no oven, limited storage), and I want to stop relying on instant noodles and fast food since my energy and focus have dropped.
**Main:** Build a 7-day meal plan (breakfast, lunch, dinner) using only stove-cooked, fridge-friendly ingredients available in Pakistan, staying within the monthly budget, and include a matching grocery list with rough prices.
**Conclusion:** Format as a day-by-day table for the meals, followed by a simple grocery list with estimated PKR costs, kept practical and not overly fancy.

### Scenario 5: The Scholarship Interview
**Role:** Act as a scholarship interview panelist conducting a mock interview.
**Context:** I have a real scholarship interview in 5 days. The panel is known for asking about weaknesses, a 5-year plan, and why I deserve it over other applicants. I tend to freeze up and ramble under pressure.
**Main:** Run a mock interview by asking me these types of questions one at a time, wait for my answer, then give me specific feedback on clarity, confidence, and length before asking the next question.
**Conclusion:** Keep feedback short and actionable (2-3 points max per answer), in an encouraging but honest tone, like a mentor prepping me for the real thing.

---
*AI SEEKHO — AI Club UMT*
