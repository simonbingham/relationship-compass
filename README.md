# Relationship Compass

## Overview

**Relationship Compass** is a lightweight single-page web app that presents curated relationship questions one at a time to prompt meaningful conversation. Questions are embedded in the app and split into two sets so you can choose the tone of your conversation.

## Question Sets

- **Connection** — 50 questions focused on building intimacy, understanding, and closeness.
- **Reflection** — 25 questions aimed at evaluating relationship health and uncertainty.
- **All** — combines both sets (75 questions total).

Use the selector at the top of the page to choose `Connection`, `Reflection`, or `All` before you begin. Button labels show the current counts dynamically.

## Features

- 🌙 **Dark Mode Design** with elegant typography and smooth animations
- 🔄 **No Repeats** — questions are tracked so you won't see duplicates until you've gone through the selected set
- 🔁 **Start Over** — when you finish a set you can reset and run through it again
- 📱 **Responsive** — works on desktop and mobile
- ⚡ **Vanilla and Lightweight** — no JS frameworks; questions are embedded in `index.html`

## How to Use

1. Open `index.html` in your browser (or run a simple local server)
2. Choose a question set from the selector (Connection, Reflection, or All)
3. A random question from the chosen set appears immediately
4. Click **Next Question** to continue through the set
5. After the last question a completion message appears; click **Start Over** to reset

## Files

- `index.html` — the complete app (HTML, CSS, JS, and embedded questions)
- `README.md` — this file

> Note: the original `questions.json` (if present) is no longer required because questions are embedded directly in `index.html`.

## Design & Technical Details

- **Font**: Lora (Google Fonts) for questions
- **Frameworks**: Bootstrap 4 (CSS only)
- **Language**: Plain JavaScript (ES6+)
- **Behavior**: Questions loaded into two arrays (`connectionQuestions`, `reflectionQuestions`) and combined for the `All` option; counts update dynamically

## Tips for Better Conversations

- Choose a quiet, comfortable setting.
- Listen actively and without judgment.
- Allow pauses — thoughtful answers can take time.
- Revisit topics later if needed.

---

Created for couples seeking deeper connection through reflective conversation.
