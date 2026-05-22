# 💕 Date invitation

A single-page romantic date invitation (in Kazakh).

## Files
- `index.html` — the whole page (HTML + CSS + JS embedded)
- `her-photo.jpg` — her photo

## EmailJS (optional — to receive a confirmation email)
When she taps **"Әрине, иә 💕"** the page can email a confirmation.
Open `index.html`, find the `EMAILJS CONFIGURATION` block near the top of
the `<script>`, and fill in `SERVICE_ID`, `TEMPLATE_ID`, and `PUBLIC_KEY`
from your https://www.emailjs.com/ dashboard. Until then the page works
fully — it just skips the email.

## Local preview
```bash
python3 -m http.server 8000
# then open http://localhost:8000
```
