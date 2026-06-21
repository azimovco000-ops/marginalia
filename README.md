# Marginalia

A digital commonplace book for exploring 60 curated quotes on how to live well. Built with vanilla JavaScript and designed for contemplative scrolling.

## Features

- **5 Philosophical Eras**: Stoicism, Existentialism, Eastern Wisdom, Literature, Psychology
- **Full-viewport scroll** with snap points
- **Hold-to-sit gesture** — hold to focus on a single quote
- **Save quotes** to a persistent collection
- **Filter by era** — narrow the deck to your mood
- **Context on demand** — tap a source to read background
- **Responsive design** — works on desktop, tablet, mobile

## Live

Hosted on Railway: [marginalia.railway.app](https://marginalia.railway.app)

## Local Development

```bash
npm install
npm start
```

Runs on `http://localhost:3000`

## Customization

Edit the `QUOTES` array in `index.html` to add or swap quotes. Each quote needs:

```javascript
{
  text: "...",
  author: "...",
  source: "...",
  cat: "Stoicism" | "Existentialism" | "Eastern & Proverbs" | "Literature" | "Psychology",
  context: "Background context (optional)",
  link: "URL to full text or null"
}
```

## Deploy to Railway

1. Push this repo to GitHub
2. Go to [railway.app](https://railway.app)
3. Create a new project → Import from GitHub
4. Select this repo
5. Railway auto-detects Node and deploys

No secrets or config needed — it just works.
