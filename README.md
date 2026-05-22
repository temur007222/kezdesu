# 💕 Date invitation

A single-page romantic date invitation (in Kazakh).

## Files
- `index.html` — the whole page (HTML + CSS + JS embedded)
- `her-photo.jpg` — her photo

## Email confirmation (FormSubmit.co — no setup)
When she taps **"Әрине, иә 💕"** the page emails a timestamped
confirmation via [FormSubmit](https://formsubmit.co) — no account, no
API keys. The recipient is the `NOTIFY_EMAIL` constant in `index.html`.

**One-time activation:** the first form sent to that address triggers a
FormSubmit "Activate Form" email. Click that link once and every future
submission is delivered automatically.

## Local preview
```bash
python3 -m http.server 8000
# then open http://localhost:8000
```
