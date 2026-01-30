# Phishing Simulation — Educational Demo

This repository contains a safe, static, client-side phishing-simulation demo intended for training and testing browser/endpoint protections in a controlled environment.

IMPORTANT: This demo is intentionally static-only and does NOT transmit, store, or log credentials. It is safe to publish publicly for educational purposes.

Contents
- `index.html` — static login page (client-side only). On submit the page shows the educational/awareness content; no data leaves the browser.
- `educational.html` — the post-submit educational content (also included inline in the static demo).
- `style.css` — styling.
- `LICENSE` — MIT license.
- `SECURITY.md` — guidance for responsible use.

Usage
1. Clone the repo or serve the files locally (no server necessary).
   - Example: `npx http-server -c-1` or open `index.html` in a browser.
2. The demo will not send data anywhere; submit the form to view the educational page.

Publishing
- This static demo is safe to publish publicly as long as you do not add any server-side logging or secrets later.
- If you convert this demo into a server-backed simulation, make the repository private and remove any sensitive data before publishing.

Legal & Ethics
- Do not use real credentials or real targets without written permission.
- This demo is educational. If you intend to run simulated campaigns against others, obtain written authorization and follow your organization’s policies.

Contact / Help
If you want a sanitized server-backed variant (private repo) or help scrubbing an existing repo history, tell me and I’ll provide step-by-step commands.