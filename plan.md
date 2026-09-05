# Simple School Website (single HTML file)

## Context
User wants a simple website for school. It should cover multiple purposes at once (student profile, general project content, a club/event section, and a portfolio of school work), styled in a colorful/fun way. The working directory (`C:\Users\TECHNOSELLERS\Desktop\Practice`) is essentially empty, so this is a fresh, self-contained build — no existing code/patterns to reuse.

## Approach
Build one self-contained `index.html` file (inline `<style>`, no external dependencies, no build step) so it can be opened directly in a browser — simplest possible setup for a school assignment.

Sections, in order, as one scrolling page with a nav bar linking to anchors:
1. **Header/Nav** — site title + nav links (About, Project, Club, Portfolio, Contact)
2. **About Me** — placeholder photo (colored circle/avatar div), name placeholder, short bio, favorite subjects/hobbies as a small list or tag chips
3. **School Project** — a card describing a sample class project/topic (placeholder title + description) so the user can swap in their real assignment content
4. **Club / Event** — a colorful highlighted section for a school club or upcoming event (name, description, meeting time/date placeholders)
5. **Portfolio** — a responsive grid of 3-4 placeholder "project cards" (title, short description, colored thumbnail block) representing school work
6. **Footer** — simple contact/footer note

Styling: colorful & fun — a vibrant accent palette (e.g., a few bright complementary colors), rounded corners, card shadows, a playful Google Font (e.g., "Poppins" or "Baloo 2") loaded via `<link>`, hover effects on cards/nav links. Fully written in plain CSS in a `<style>` block (no frameworks). Layout done with flexbox/grid, responsive via a single media query for smaller screens.

All content uses clearly-labeled placeholder text/names (e.g., "Your Name", "Your School Project Title") so the user can easily find-and-replace with real info.

## File to create
- `C:\Users\TECHNOSELLERS\Desktop\Practice\index.html` — the entire site (HTML + CSS in one file)

## Verification
- Open `index.html` directly in a browser (double-click or `start index.html` in PowerShell) and confirm all sections render, nav anchor links scroll correctly, and layout looks reasonable at both desktop and narrow (mobile-ish) window widths.
