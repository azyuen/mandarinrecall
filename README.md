# Mandarin Recall

A mobile-friendly Mandarin learning app for Aaron. No dependencies or build step.

## Features
- Practice: select English sentence components, say the Mandarin from memory, then reveal characters and pinyin.
- Vocabulary: search and filter the words from lessons 1–2.
- Progress: correct and retry counters stored locally in your browser.

## Publish with GitHub Pages
Go to **Settings → Pages → Build and deployment**. Choose **Deploy from a branch**, select **main** and **/(root)**, then save.

The expected site URL after publishing is https://azyuen.github.io/mandarinrecall/

## Add lessons
Edit the structured `times`, `persons`, `places`, `sports`, `actions` and `vocab` arrays in `index.html`. Keep the sentence templates grammatically valid.

Progress does not yet sync between devices.
