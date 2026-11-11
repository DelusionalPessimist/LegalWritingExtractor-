# Law Hub for iPhone (Prototype)

A clickable, single-file prototype of **Law Hub**, an iPhone app for practicing law school exams. It covers practice exams, a 15-minute issue-spotting drill, rule writing with feedback, a rule bank, and model-answer comparison.

> **Non-working prototype.** Every exam, score, and piece of feedback is invented sample data. Grading is simulated. Nothing is sent anywhere and nothing is saved. Reload the page to reset.

## Running it

No build step or dependencies. Open `index.html` in any modern browser.

- On a desktop, the app renders inside an iPhone frame (393×852) with a short description beside it.
- On a phone-sized screen, it runs full-bleed like a native app.
- Light and dark mode follow your system setting.

## What's inside

The tab bar has five sections:

| Tab | What it does |
| --- | --- |
| **Exams** | Exam bundles by course (Contracts, Torts, Civ Pro). Each holds the question, scoresheet, model answers, and your attempts. Practice an exam, get issue-by-issue feedback, and revise as a new attempt. Add exams by importing files, pasting text, scanning pages, or starting blank. |
| **Drill** | A timed 15-minute issue-spotting drill: spot issues, outline, then review what you caught, partly caught, and missed. |
| **Compare** | *Coming soon.* Preview screens for comparing your answer to model answers and an A+ Teardown that maps an answer sentence by sentence (Issue, Rule, Application, Other side, Conclusion). |
| **Write** | Rule writing in four levels, from a single rule statement up to a full exam answer. Feedback covers what's working, what's not, what's missing, and terminology, with an exam-ready rewrite you can copy or save to the Rule Bank. |
| **Rules** | The Rule Bank: search rules, track their status, practice a rule, and add rules in bulk. |

Also included: a **Progress** screen, **My Patterns** (score trend and error tags), a **Term Glossary**, and an **About** screen.

## Privacy and security

The page sets a strict Content Security Policy: no network requests, no external scripts or fonts, and no form submission. All CSS and JavaScript are inline, and no browser storage is used.

## What the full app would add

- Importing exams, scoresheets, and model answers
- Real AI grading against your own rubric
- Sync across devices

## Status

Prototype v0.4, sample data only. Profile is intentionally left out of this build.
