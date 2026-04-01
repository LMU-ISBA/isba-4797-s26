# Final Presentation Content Requirements Redesign — Implementation Plan

> **For agentic workers:** REQUIRED SUB-SKILL: Use superpowers:subagent-driven-development (recommended) or superpowers:executing-plans to implement this plan task-by-task. Steps use checkbox (`- [ ]`) syntax for tracking.

**Goal:** Revise the Content Requirements, Time Allowed, and Visual Aids sections of `project/final-presentation.md` to produce engaging, story-driven presentations that build transferable business skills.

**Architecture:** Single-file edit to `project/final-presentation.md`. All changes are in-place replacements or insertions to specific line ranges. The document structure before and after the Content Requirements section stays untouched.

**Tech Stack:** Markdown only. No build, no dependencies.

**Spec:** `docs/superpowers/specs/2026-04-01-final-presentation-content-requirements-design.md`

---

## File Map

- Modify: `project/final-presentation.md`
  - Lines 90-100: Time Allowed section (revise)
  - Lines 112-185: Content Requirements section (replace entirely)
  - Lines 189-203: Visual Aids section (add Slide Titles subsection)
  - Lines 207-210: Resources section (unchanged, but verify)

No new files created. No files deleted.

---

### Task 1: Add Delivery Policy and replace Content Requirements section

This is the largest edit. It replaces everything from line 112 (`## Content Requirements`) through line 185 (`### Q&A (5 min)`) with the new section structure.

**Files:**
- Modify: `project/final-presentation.md:112-185`

- [ ] **Step 1: Replace the Content Requirements header through Q&A**

Replace lines 112-185 (from `## Content Requirements` through `### Q&A (5 min)`) with the following:

```markdown
## Delivery Policy

You must present from knowledge, not from a script. Reading from a phone, tablet, index card, or any other aid during your presentation will result in a one letter grade deduction on your final presentation grade.

Glancing at your slides to stay on track is fine. Reading verbatim from anything is not. Know your material well enough to talk about it naturally — the way you would explain your project to someone at a networking event.

---

## Content Requirements

### Introduction (2-3 min)

**Open with a hook.** Start with something that makes the audience pay attention before you introduce yourself: a surprising fact, a question, a short story, or a bold claim. The first 30 seconds determine whether the room is with you or checking their phones.

Introduce yourself when it is your turn to speak.

**Elevator pitch** — in one sentence, cover:
- Who are you helping?
- What problem are you solving?
- How are you solving it?

**ISBA subfields** — Display your 3 ISBA subfields as visual tags on your title slide or elevator pitch slide (e.g., badges, icons, or a small footer). Do not narrate them here — you will demonstrate them naturally during your solution and demo. Choose from:

1. Project & Product Management
2. Business Analytics
3. Data Science
4. AI / Machine Learning
5. Data Engineering
6. Software Development
7. Cloud Computing & DevOps
8. Cybersecurity
9. UI/UX Design
10. Database Management

### Problem & Stakes (2-3 min)

Make the audience feel the problem before you solve it. This is the "before" picture.

**Who is affected?**
- B2B: Name the business, their industry, and what they do. Who specifically inside that organization feels this pain?
- B2C: Describe the real people you are serving — not just demographics, but what their day looks like when this problem hits.

**What is broken and why does it matter?**
- What is the problem and why does it exist?
- What does it cost — in time, money, frustration, or missed opportunity?
- How do they deal with it today? (This is often the most compelling part — the workaround is usually worse than the problem itself.)

**Translate technical complexity for a general audience.** If your problem involves something technical, explain it the way you would to a smart friend who does not work in tech. Do not lose the substance. Lose the jargon.

### Solution & Demo (5-7 min)

This is the "after" picture. Show the audience what changes because your project exists.

**Briefly mention any significant alternatives you explored but did not implement.** One or two sentences, enough to show you made a deliberate choice, not that you picked the first thing that worked.

**Demo your solution live.** The demo must be interactive — click through it, run it, show it working. Limit screenshots to what you genuinely cannot show live. If something can move, make it move.

**Weave in your ISBA subfields as you go.** When you reach a part of the demo that draws on one of your subfields, call it out naturally:

> "This is where the data science side of the project comes in — we trained a classification model on 18 months of intake data."

Do not pause the demo to list subfields. Let the audience see your range of skills through the work itself.

**Connect the solution back to the problem.** End this section by making the before/after contrast explicit. What was true before your project, and what is true now? If you can quantify the impact (time saved, errors reduced, revenue enabled), do it.

**Keep technical explanations accessible.** You can go deep on technical decisions, but always bring it back to language a non-technical audience member can follow. The skill is translating complexity, not avoiding it.

### Key Decisions (2-3 min)

Every project hits moments where you have to choose a direction. Highlight 1-2 key decisions, pivots, or tradeoffs you made during the project.

For each one, cover:
- **What you were facing** — the situation or constraint that forced a decision
- **What options you considered** — show that you thought through alternatives
- **Why you chose the path you did** — and what you gained or gave up

This is where the audience learns how you think, not just what you built. A stakeholder or future employer listening to this section should come away thinking you can make good decisions when things are not clear.

These do not have to be dramatic pivots. A deliberate choice to use one tool over another, a scope decision that shaped the final product, or a moment where user feedback changed your direction all count, as long as you can explain the reasoning behind it.

### Reflection (1-2 min)

**What I Know Now That I Didn't Before**

One slide. One honest answer to the question: what do you know now that you did not know when you started this project?

This should be something specific that only you could say after doing this work. Not "communication is important" or "time management was hard." Something your future self, or a junior starting a similar project next semester, would actually find useful.

**Examples of strong reflections:**
- "I assumed users would interact with the dashboard the way I designed it. Watching real users ignore the feature I spent the most time on taught me to test with people before building."
- "I did not realize how much of data science is data cleaning. The model took two weeks. Getting the data ready took two months."

**Examples of weak reflections:**
- "I learned that teamwork is essential."
- "Planning ahead is really important."

The difference: strong reflections are earned. You can tell the person lived through something. Weak reflections could be said by anyone about any project.

### Closing Slide

Your last slide is what the audience sees during Q&A and what lingers after you stop talking. Make it count. Do not end with a "Thank You" or "Questions?" slide.

End with one of the following:

- **Key Takeaways:** The 2-3 things you want the audience to walk away remembering.
- **Next Steps:** What specifically happens next with this project? Be concrete.
- **Discussion Point:** An open-ended question that gets the room talking.
- **Call to Action:** Something you want the audience to actually do.
- **Quote or Insight:** A quote that captures what this project is really about.

**Resources:**
- [Should I Begin or End with My Recommendation?](https://www.storytellingwithdata.com/blog/should-i-begin-or-end-with-my-recommendation) — Storytelling with Data (5 min read)
- [The Secret Structure of Great Talks](https://www.ted.com/talks/nancy_duarte_the_secret_structure_of_great_talks) — Nancy Duarte, TED Talk (18 min watch)
- [How to Give a Killer Presentation](https://hbr.org/2013/06/how-to-give-a-killer-presentation) — Chris Anderson / HBR

### Q&A (5 min)
```

- [ ] **Step 2: Verify the edit**

Open `project/final-presentation.md` and confirm:
- "Delivery Policy" section appears between the `---` after Attendance Policy and before "Content Requirements"
- Content Requirements contains these subsections in order: Introduction, Problem & Stakes, Solution & Demo, Key Decisions, Reflection, Closing Slide, Q&A
- No leftover content from the old sections (no "Target Customer/User/Client", no "CRISP-DM", no "1 Significant Challenge Solved", no "Next Steps / Future Improvements")

- [ ] **Step 3: Commit**

```bash
git add project/final-presentation.md
git commit -m "Replace content requirements with storytelling-driven structure"
```

---

### Task 2: Revise Time Allowed section

Replace the Time Allowed section (lines 90-100) with the new version that includes suggested timing by section and the non-verbal warning policy.

**Files:**
- Modify: `project/final-presentation.md:90-100`

- [ ] **Step 1: Replace the Time Allowed section**

Replace lines 90-100 (from `## Time Allowed` through the blank line before `---`) with:

```markdown
## Time Allowed

Time limits are tiered based on team size:

| Team Size | Presentation | Q&A | Total |
|-----------|-------------|-----|-------|
| 1-2 members | 10 minutes | 5 minutes | 15 minutes |
| 3-5 members | 15 minutes | 5 minutes | 20 minutes |

**Suggested timing by section:**

| Section | 1-2 Members | 3-5 Members |
|---------|-------------|-------------|
| Introduction | 1-2 min | 2-3 min |
| Problem & Stakes | 1-2 min | 2-3 min |
| Solution & Demo | 4-5 min | 5-7 min |
| Key Decisions | 1-2 min | 2-3 min |
| Reflection | 1 min | 1-2 min |

You will receive a non-verbal 1-minute warning (a raised hand or card). Presentations have a hard stop at the time limit. Your advisor will transition the room to Q&A. Practice with a timer so this never surprises you.
```

- [ ] **Step 2: Verify the edit**

Confirm the Time Allowed section now has both the original tier table and the new "Suggested timing by section" table, followed by the non-verbal warning language.

- [ ] **Step 3: Commit**

```bash
git add project/final-presentation.md
git commit -m "Add section timing guide and non-verbal warning policy"
```

---

### Task 3: Add Slide Titles subsection to Visual Aids

Insert the new Slide Titles subsection into the Visual Aids section, after the existing content (after line 203 "Use transitions for text...") and before the `---` separator.

**Files:**
- Modify: `project/final-presentation.md` (Visual Aids section)

- [ ] **Step 1: Insert Slide Titles subsection**

After the line "Use transitions for text, especially bullet points. Do not show all text at once." and before the `---` that follows, insert:

```markdown

### Slide Titles

Every slide title should communicate a takeaway, prompt an action, or share an insight. Do not use generic label titles.

| Generic Label | Takeaway / Action / Insight |
|---|---|
| Background | Manual data entry costs the department 20 hours per week |
| Problem Statement | The current process breaks down when volume exceeds 500 records |
| Solution | Automate the intake pipeline to eliminate manual errors |
| Demo | Watch the dashboard update in real time as new data flows in |
| Next Steps | Three features away from a production-ready launch |
| Lessons Learned | Test with real users before you build, not after |

A good test: if your slide title could appear on any project's presentation, it is too generic. Rewrite it until it could only belong to yours.

**Resource:** [Transforming Slide Titles](https://www.storytellingwithdata.com/blog/2020/3/5/transforming-slide-titles) — Storytelling with Data
```

- [ ] **Step 2: Remove the old slide titles line**

The existing line "Write slide titles that tell the audience something, not just label the slide." (in the Visual Aids bullet list) is now redundant. Remove it — the new Slide Titles subsection covers this in more detail.

- [ ] **Step 3: Verify the edit**

Confirm the Visual Aids section now has: the bullet list (without the old slide titles line), the 1-5-5-5 Rule, the transitions line, and the new Slide Titles subsection with the comparison table.

- [ ] **Step 4: Commit**

```bash
git add project/final-presentation.md
git commit -m "Add slide titles subsection with comparison table to visual aids"
```

---

### Task 4: Run humanizer and final review

The full document must be run through `/humanizer` before finalizing.

**Files:**
- Modify: `project/final-presentation.md` (full document)

- [ ] **Step 1: Run `/humanizer` on the full document**

Read the entire `project/final-presentation.md` file and scan for AI writing patterns per the humanizer skill. Fix any issues found. The spec content was already humanized, but the surrounding unchanged sections and any integration seams should be checked.

- [ ] **Step 2: Verify the full document reads naturally**

Read the complete file top to bottom. Check for:
- Consistent tone between old (unchanged) sections and new sections
- No orphaned references to removed content (e.g., "Next Steps / Future Improvements" referenced elsewhere)
- All internal references are consistent (e.g., section names in the timing table match actual section headers)
- All external links are present and correctly formatted

- [ ] **Step 3: Commit**

```bash
git add project/final-presentation.md
git commit -m "Apply humanizer pass to final presentation document"
```

---

## Verification Checklist

After all tasks are complete, confirm:

- [ ] Delivery Policy section exists before Content Requirements with letter grade penalty
- [ ] Introduction has hook, self-intro, elevator pitch, and visual subfield tags (not narrated)
- [ ] Problem & Stakes section replaces old Target User + Problem sections
- [ ] Solution & Demo includes subfield weaving guidance and before/after contrast
- [ ] Key Decisions section exists (replaces methodology requirement) with 1-2 decisions
- [ ] Reflection uses "What I Know Now That I Didn't Before" with strong/weak examples
- [ ] Closing Slide has updated resources (SWD, Duarte TED, HBR)
- [ ] Q&A section preserved
- [ ] Time Allowed has two timing tier tables and non-verbal warning language
- [ ] Slide Titles subsection in Visual Aids with comparison table and SWD resource
- [ ] No references to CRISP-DM, SDLC, "methodology", "1 Significant Challenge", or "Next Steps / Future Improvements"
- [ ] Full document has been run through `/humanizer`
