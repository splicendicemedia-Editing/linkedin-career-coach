# LinkedIn Career Coach (a Claude skill)

A friendly coach that **asks you questions first**, then helps with your LinkedIn profile, posts, networking and job search. It starts from what *you* want: your ambitions, the work you enjoy, the life you want around it.

It never needs your password, does nothing on your account without your say-so, and never invents facts about you.

## Use it (pick one)

### A. In a normal Claude chat (easiest)
1. Open a new chat in Claude (a Project works well so it remembers).
2. Open `START-PROMPT.md`, copy everything, paste it, send.
3. Answer the tap-style questions. Nothing is posted anywhere unless you copy it yourself.

### B. As a skill in Claude (claude.ai)
1. Zip the `linkedin-career-coach` folder (the folder itself, with `SKILL.md` inside it), or use the ready-made zip you were sent.
2. Settings > Capabilities > Skills > Upload skill.
3. In a chat say: "Coach my LinkedIn."

### C. In Claude Code (with your own browser signed in)
Copy the `linkedin-career-coach` folder into `.claude/skills/` of your project. Start Claude Code and say "Coach my LinkedIn". You choose how much it may do on your account (draft only, ask before every action, or likes only on its own).

## What you get
0. No LinkedIn account yet? It asks first, and walks you through creating one in your own name. You type your own password and verification codes; it never asks for them and never bypasses CAPTCHAs or ID checks.
1. An interview about your ambition, strengths and the job you want.
2. A one-page picture of your next 90 days, with honest unknowns.
3. A profile makeover: headline, About, experience, skills (drafts for you to approve).
4. A simple posting plan sized to the time you have, with drafts in your voice.
5. A job-search plan: target list, outreach scripts, interview stories, tracker.

## Your answers stay yours
The coach saves your answers in a local `my-linkedin/` folder on your own computer. This repository contains **only the skill, no one's data**. The `.gitignore` blocks `my-linkedin/` so you cannot upload it by accident. Do not put your answers or contact lists in a public repository.

## Honest limits
- It cannot promise a job, an offer or followers.
- Automating LinkedIn can break LinkedIn's User Agreement. This skill keeps a human pace and asks first.
- It does not hide AI help and does not try to dodge LinkedIn's detection.

MIT licence. Use it, change it, share it.
