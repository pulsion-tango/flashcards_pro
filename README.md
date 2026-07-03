# Flashcards Pro

Flashcards Pro is a language-learning flashcard app built around the **Leitner spaced repetition system**. It helps you memorize vocabulary through active recall and scheduled review.

Live app: https://pulsion-tango.github.io/flashcards_pro/

---

## Features

- **Multi-language vocabulary**: English, French, Spanish, German
- **Rich card content**: word, definition, pronunciation, synonyms, usage example, and personal comments (nuance, false friends, context)
- **Leitner spaced repetition (5 boxes)**: cards you know move to boxes with longer intervals (1 / 3 / 7 / 14 / 30 days); cards you struggle with reset to box 1
- **"Due today" review mode**: filter to only the cards that need review right now
- **Text-to-speech pronunciation** for each card, matched to its language
- **Cloud sync via Supabase**: sign up / log in, and your deck follows you across devices
- **Row Level Security**: each user only ever sees their own cards
- **Search, shuffle, edit, and delete** cards on the fly
- **Local JSON export/import** as a backup on top of cloud storage
- **Dark mode**

---

## Tech stack

- Vanilla HTML / CSS / JavaScript (no framework)
- [Supabase](https://supabase.com) for authentication and data storage (PostgreSQL + RLS)
- Deployed as a static site on GitHub Pages

---

## Goal

Help learners any other vocabulary — through active recall and spaced repetition, with enough context (example sentences, nuance notes) to actually understand a term, not just memorize a translation.
