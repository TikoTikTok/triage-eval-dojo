# Triage Eval Dojo

Interview trainer for one question: **how do you evaluate an AI agent that does security-critical work, such as vulnerability triage?**

Live page: https://tikotiktok.github.io/triage-eval-dojo/

## What is inside

- **Four comic guides** that carry the material: Pip (static eval with ground truth), Rue (guided eval, red team), Qbit (the unresolved queue), Gate (the release decision).
- **Six modules**: why security evals are different, static evals, guided evals, findings nobody can settle, the harness as attack surface, and an interview arena.
- **Five games**: threshold lab, gatekeeper, sort it, triage the flag, spot the injection.
- **Six quizzes** plus a timed final boss.
- **Charts and flows**: error-cost asymmetry, per-slice recall against a floor, reliability diagram with ECE, pass@k vs pass^k, unresolved rate over time, decision tree, eval lifecycle, harness isolation, unresolved-flag flow.
- **Interview bank**: 24 tiered questions with model answers and traps, 20 flashcards, whiteboard drills, a one-page cheat sheet.

Progress and XP are stored in `localStorage` in your browser only. Nothing is sent anywhere.

## Run locally

It is a single `index.html` with no build step. Open it in a browser, or serve the folder:

```bash
python -m http.server 8000
```

Fonts load from Google Fonts; everything else is inline.

## License

MIT
