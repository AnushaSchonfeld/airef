# AI Ref

A free, bilingual (English / Hindi) browser game that teaches kids how AI learns.
Players train a friendly robot referee, Ref-Bot, to call a badminton shot IN or OUT.
By showing it examples, testing it, and fixing its mistakes, they discover that:

1. AI learns from examples (training data).
2. It needs diverse, good-quality data, or it becomes biased.
3. Labels must be correct.
4. AI is not perfect, so people must check it.

**Play it:** [trainairef.org](https://trainairef.org)

Made for grades 3 to 5 ESL learners in India, with a focus on access for underserved
learners and on girls' participation. About 15 to 20 minutes, ages 8 to 11, no
install, no accounts, and no personal data collected.

## What is in this repo

| Path | What it is |
| --- | --- |
| `index.html` | The whole game: one self-contained HTML file, vanilla JS, no build step |
| `assets/` | Intro and outro videos (English + Hindi) with poster frames |
| `unplugged/` | "Be the AI Referee": a no-technology classroom version (slides, lesson plan, printable cards) |
| `docs/` | Catalogue thumbnail and project notes |

## Running it locally

Double-click `index.html`. That's it.

## Embedding

```html
<iframe src="https://trainairef.org" allow="autoplay; fullscreen"
        style="width:420px;height:820px;max-width:100%;border:0"></iframe>
```

`allow="autoplay; fullscreen"` is needed for the videos.

## Hosting

Served by GitHub Pages from the `main` branch root, with the custom domain in `CNAME`.
Pushing to `main` deploys.
