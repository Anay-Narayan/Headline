# Headline

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/License-Apache%202.0-blue?style=for-the-badge" alt="License: Apache 2.0" />
</p>

Headline is a lightweight news dashboard and claim-checking web app built with plain HTML, CSS, and JavaScript. It brings together top stories from multiple news feeds, highlights current events in a clean card layout, and lets users quickly test whether a headline or claim is being reported elsewhere.

Designed with a playful retro aesthetic, Headline includes a “Beaky the seagull” companion, voice narration, and a simple interface for anyone wanting a fast digest of current events.

## Features

- Curated top stories from multiple RSS feeds
- Story cards with headline, summary, source, and original link
- Topic tags for quick browsing
- Claim-checking workflow for user-entered headlines or topics
- Optional AI-assisted verification using Pollinations
- Optional Google News cross-checking
- Browser voice narration for story playback
- Light/dark theme support
- Local visit tracking in the browser
- Responsive single-page design

## Tech Stack

- HTML
- CSS
- JavaScript
- RSS feed parsing
- Browser Speech Synthesis API
- Optional AI and Google News integrations

## How it works

The app fetches a set of curated RSS feeds, filters and ranks the newest stories, and displays the most relevant current headlines in a card-based layout. Each story includes a short summary, the outlet name, and a link to the original article.

Users can also enter a topic or headline in the search field to compare it against the current coverage. The app tries to find related articles and optionally uses AI to provide a quick, plain-language verdict based on the matching sources.

## Local usage

Since this is a static front-end project, you can run it by opening the `index.html` file directly in a browser.

If you want to serve it locally with a simple web server:

```bash
python -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## Project structure

```text
Headline/
├── index.html
├── README.md
└── LICENSE
```

## License

This project is licensed under the Apache License, Version 2.0. See the [LICENSE](LICENSE) file for details.

## Author

Made by Anay Narayan.

## Notes

Headline is intended for educational, informational, and general-purpose use. It is a small, browser-based app and does not replace formal fact-checking or professional journalism.
