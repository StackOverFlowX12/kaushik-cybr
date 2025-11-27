Social Redirect Page — Walkthrough

What I added

- `social.html`: A standalone redirect hub containing SVG icons that link to each social profile in a new tab.
- Updated `index.html` contact area to include small inline SVG icons for social links and an "Open all socials" button that opens `social.html`.

Profiles included

- Medium: https://medium.com/@ZeroDayForge
- YouTube: https://www.youtube.com/@StackOverflowX12
- Discord: https://discord.com/users/Stack0ver_Flow
- Twitter: https://twitter.com/ZeroDayForge
- Instagram: https://www.instagram.com/stackoverflowx10n
- GitHub: https://github.com/StackOverFlowX12
- Reddit: https://www.reddit.com/user/hustleinferno29
- LinkedIn: https://www.linkedin.com/in/stackoverflow12xn

How it works

- `social.html` is a static page with visually-focused icon cards. Each card is an anchor (`<a>`) with `target="_blank" rel="noopener noreferrer"` to open external profiles safely.
- `index.html` contains a small icon row in the contact card for quick access and a button link to `social.html` for a more prominent listing.

Editing or adding links

- To change a URL, open `social.html` and update the `href` attribute for the appropriate anchor.
- To add a new platform, copy any existing `.card` block inside the `.grid` and update the `href`, accessible text, and icon SVG.

Accessibility notes

- Each icon anchor has an `aria-label` and `title` for screen reader / tooltip support.
- Icons are inline SVGs — you can replace them with more detailed SVGs if desired.

Deploying or hosting

- This is a static page; simply host `social.html` alongside `index.html` (same directory). The links will work wherever the static site is served (GitHub Pages, Netlify, plain web server).

If you'd like

- I can add hover tooltips, analytics tracking (e.g., Google Analytics) for outbound clicks, or convert the form to submit comments to a backend.
- I can replace inline SVGs with a lightweight icon font if you prefer (requires adding the font files).

