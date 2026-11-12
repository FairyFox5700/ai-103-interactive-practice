# AI-103 Interactive Practice

A self-contained browser-based study trainer for the Microsoft AI-103 exam.

## Features

- 213 practice questions across all five exam domains
- 174 selectable multiple-choice questions
- 39 exhibit/review questions with answer reveal and self-scoring
- Detailed answer explanations and exam takeaways
- Search, domain filters, flags, and question map
- Incorrect, unanswered, and visual-review study modes
- Progress saved locally in the browser
- Responsive light and dark themes
- Keyboard navigation
- No build step or external runtime dependencies

## Run locally

Open `index.html` directly in a modern browser.

Alternatively, serve the repository directory with any static web server:

```bash
python -m http.server 8765
```

Then open `http://127.0.0.1:8765`.

## Privacy

All study data and progress remain in the browser. The app makes no external network requests except when you deliberately open an official Microsoft documentation link.
