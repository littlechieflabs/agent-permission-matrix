# Agent Permission Matrix Builder

A small, local-first browser tool for documenting what an AI agent may do autonomously, what requires approval, and what must remain prohibited.

## Privacy

The tool runs as static HTML and JavaScript. Matrix entries remain in the browser; there is no account, backend, analytics SDK, cookie, or network submission. JSON and CSV exports are created locally by the browser.

## Use

Open `permission-matrix.html` in a browser, start with the examples, add or edit actions, and export the resulting matrix. Review prompts are deterministic reminders, not legal, security, or compliance advice.

## Included

- `permission-matrix.html` — the standalone utility

Live demo: https://willowy-jelly-cca33a.netlify.app/permission-matrix.html

This tool is part of BoundaryKit, a local-first operational control pack for teams deploying tool-using AI agents.
