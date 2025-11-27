Bug Bounty Landing Page — README

Files added

- `bugbounty.html`: A static landing page inspired by bugbountyhunter-style sites. Contains a hero with search, featured program cards, a sidebar with triage tips, and a small JS search/filter.

How to customize

- Program data: Edit the `programs` array near the bottom of `bugbounty.html` to add or modify program entries. Each entry has `title`, `tags` (array), `scope` and `reward` fields.
- Styles: The page uses local CSS inside the `<head>` of `bugbounty.html`. You can extract it into a shared stylesheet if you prefer.
- Link from main site: `index.html` has a nav link to `bugbounty.html`. Adjust the nav in `index.html` if you want placement changed.

Deploy

- This is a static page — serve it alongside your other files. Example (from project root):

  python3 -m http.server 8000

- Then open `http://localhost:8000/bugbounty.html` in your browser.

Next suggestions

- Add pagination or program detail pages.
- Replace static list with data from a JSON endpoint or a small backend.
- Add filtering by tag buttons and program sorting by reward.
