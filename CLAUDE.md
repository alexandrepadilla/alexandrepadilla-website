# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project

Personal academic website for Alexandre Padilla, Professor of Economics at Metropolitan State University of Denver. Built as plain HTML/CSS with no build tooling or frameworks — open `index.html` directly in a browser.

## Structure

- `index.html` — Home page (profile, bio, contact links)
- `styles.css` — All styles, shared across pages
- `profile.jpg` — Profile photo (must be added manually)
- Additional pages (contact, cv, links, media, publications, research, teaching) share the same header/nav/footer pattern from `index.html`

## Conventions

- All pages link to the same `styles.css`.
- Navigation `<li><a>` items get `class="active"` on the current page.
- The `<span id="year">` in the footer is populated by an inline script.
- No JavaScript framework or build step — keep it that way unless the user explicitly asks for one.
