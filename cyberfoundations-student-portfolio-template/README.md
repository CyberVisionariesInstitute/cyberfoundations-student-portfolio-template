# CyberVisionaries Institute (CVI) — Cyber Foundations Student Portfolio

**New here? Read [START-HERE.md](START-HERE.md) first — it walks you through your very first commit, step by step.**

This repository documents your hands-on learning through the **CyberVisionaries Institute Cyber Foundations (Tier I)** program.

This is your working portfolio — **not the curriculum repository.** All instructional materials (lesson content, lab instructions) live in [`cyberfoundations-labs`](https://github.com/CyberVisionariesInstitute/cyberfoundations-labs). Everything you build and write goes here.

New to GitHub in general (not just this repo)? See the [CVI GitHub Handbook](https://github.com/CyberVisionariesInstitute/cvi-github-handbook) for accounts, key terms, and how templates work.

## 1. Repository Purpose

This repository is:

1. A structured lab documentation workspace
2. A technical reflection journal
3. A growing cybersecurity portfolio
4. Evidence of hands-on capability you can show an employer

Everything committed here should reflect professional standards — this is the first thing a hiring manager might look at.

## 2. Repository Structure

- `labs/` — weekly lab documentation and outputs
- `notes/` — weekly key concepts in your own words
- `reflections/` — weekly reflection responses
- `projects/` — mini-projects and the Week 12 capstone
- `assets/` — screenshots, diagrams, and supporting images

Each folder has a specific purpose. Don't mix content types across directories.

**Weeks 1 and 2 are already set up for you.** `notes/week-01/`, `reflections/week-01/`, and the full `labs/week-02/`, `notes/week-02/`, `reflections/week-02/` set are already in this repo, ready to fill in — you don't need to create those. From Week 3 on, you create the next `week-0X` folder yourself inside `labs/`, `notes/`, and `reflections/` — same naming convention (`week-03`, `week-04`, and so on), same three file names. No one hands you a `week-03` template — matching a convention consistently on your own is part of what's being evaluated.

## 3. Embedding Screenshots (Relative Paths Only)

When documenting labs, you'll often include screenshots of terminal output, certificate details, or command results.

**Step 1 — Store screenshots properly.** All screenshots go in `assets/screenshots/week-0X/` (adjust the week number). Don't store screenshots in the root directory.

**Step 2 — Embed using a relative path.** From a file in `labs/week-0X/`, reference an image like this:

```markdown
![Description](../../assets/screenshots/week-0X/filename.png)
```

**Do NOT use:**
- Absolute file paths from your computer (e.g. `C:\Users\YourName\Desktop\image.png`)
- Drag-and-drop links that reference your local machine
- Public URL links unless explicitly instructed

If your image doesn't render, your path is incorrect — fix it before submitting.

## 4. Weekly Workflow

1. Review lesson content in Circle
2. Complete the lab in the Lab Portal — for lab weeks, submitting there writes your work directly into this repo's `labs/week-0X/` folder. You can also open that file here and add to it yourself.
3. Summarize key concepts in your own words in `notes/`
4. Submit your reflection in `reflections/`
5. Commit with a clear, professional message

## 5. Document Standards

Every entry should demonstrate:

1. Clear technical reasoning
2. Structured thinking
3. Concise explanations
4. Professional tone

Avoid vague summaries, copying definitions without understanding them, and single-word commit messages.

## About CVI

CyberVisionaries Institute builds sustainable, demonstrable technical capability in cybersecurity through structured training and mentorship. This portfolio reflects that progression.
