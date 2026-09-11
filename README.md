# Student Notes Scribe

A simple, self-contained HTML tool for generating tiered-support blurbs for student notes. Select the supports and strategies used across Tier 1, Tier 2, and Tier 3 (Engagement, Learning, and Wellbeing), plus optional Teacher Aide and Collaborative Teaching support, choose a frequency for each, and generate a ready-to-use written summary.

## Features

- Tiered strategy library covering Engagement, Learning, and Wellbeing domains across Tier 1 (Universal), Tier 2 (Targeted), and Tier 3 (Intensive) supports
- Optional "Learning Partners" section for Teacher Aide Support and Collaborative Teaching Support strategies
- Search/filter to quickly find a strategy
- Frequency selector for each chosen strategy (e.g. "Once a lesson", "Once a week", "As needed")
- One-click blurb generation, with an editable output box and character count warning
- Copy-to-clipboard for the generated blurb
- An "Edit interface" mode to hide strategies you don't use, reorder them, and add your own custom strategy cards
- Preferences (hidden items, custom cards, ordering) are saved locally in your browser, nothing is sent anywhere or stored on a server

## Usage

1. Download `index.html` (or clone this repo).
2. Open the file directly in any modern web browser, no build step, server, or installation required.
3. Enter a student name, select the relevant strategies, and choose a frequency for each.
4. Click **Generate** to produce a blurb, then edit or copy it as needed.

This tool can also be found on [GitHub Pages](https://pages.github.com/), so others can open it directly without downloading the file.

## Privacy

- Rules-based system, no embedded AI, no data is sent to any AI model when generating a blurb
- No student names or data are transmitted anywhere, everything is entered and processed locally on your device
- `localStorage` is utilised to save your interface preferences (hidden strategies, reordering, custom cards) in your own browser
- No out-of-client storage is utilised, nothing is transmitted to or stored on any server
- No network requests, tracking, analytics, or cookies
- Preferences can be cleared at any time using the "Reset" option in the interface

## Author

Designed and engineered by Daniel Nicol, implemented agentically with Claude (Anthropic).

## License

To be confirmed.
