# Hanasō 話そう — Japanese from zero to JLPT N1

A free, installable Japanese course with an AI tutor (Yuki). It takes you from kana through JLPT N5 → N1 in short 15–20 minute steps, aimed at understanding anime, J‑dramas and the news.

**Open the app:** https://jongandy01-lab.github.io/hanaso/

## What's inside
- **The path:** hiragana and katakana, then 50 units across N5–N1. Each unit has word & kanji sets, grammar, listening scenes, Bible-lesson study scenes, conversation practice and a unit test. A mock JLPT exam finishes each level (or lets you test out).
- **Talk:** conversation with your tutor. The English/Japanese mix shifts toward all‑Japanese as you progress. Includes "teach it back" practice.
- **Review:** spaced review of every word and kanji, kana drills with tracing, and a **Library** where you import your own PDFs, EPUBs or text files to study them.
- **Voice:** Japanese text‑to‑speech, plus Japanese speech input on devices that support it.

## Bring your own AI
Hanasō has no server and no shared account. Lessons and conversation use **your own AI provider and API key**, which stay on your device and are sent only to that provider. Choose one in **Progress › Your AI**:

| Provider | Get a key |
|---|---|
| Anthropic (Claude) | https://console.anthropic.com/settings/keys |
| OpenAI (ChatGPT) | https://platform.openai.com/api-keys |
| Google Gemini | https://aistudio.google.com/apikey |
| OpenRouter (many models, one key) | https://openrouter.ai/keys |
| Any OpenAI‑compatible server (e.g. Ollama, LM Studio) | your server's URL |

Then tap **Load models**; the app suggests a capable "lesson model" and a faster "chat model". API use is billed by your provider; at 15–20 minutes a day it is usually a few dollars a month or less. Kana practice and review work without any AI.

## Install on your phone or tablet
- **iPhone / iPad:** open the link in Safari → Share → **Add to Home Screen**.
- **Android:** open in Chrome → menu → **Install app**.

## Your data
Progress, review cards and imported documents are stored only on your device. Use **Progress › Backup** to move them to another device. Nothing you import is uploaded anywhere except the passages you choose to study, which go to your own AI provider.

## Developing
Plain HTML/CSS/JS, no build step. `index.html` is the whole app, `sw.js` makes it work offline, and pushing to `main` updates the live app via GitHub Pages.

## Credits
Stroke-order data for kana tracing comes from [KanjiVG](https://kanjivg.tagaini.net) by Ulrich Apel, licensed under [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/).
