# Austin Help Finder

**WarriorHacks 2.0 submission (Hackathon track).** Theme: solve an issue in your community.

## Problem
People who need help (food, health care, jobs, housing) often can't find which local services exist, or whether they qualify. Information is scattered, English-only, and written in jargon.

## Audience
Low-income families, newcomers and Spanish speakers, seniors, and anyone with limited time or a phone-only connection.

## Features
- Pick a need (food, health, jobs, housing, learning/internet) and get matched services
- Three optional eligibility questions that rank results: "Open to everyone" vs "You likely qualify"
- English/Español toggle and a large-text toggle
- One-tap directions (Google Maps) and website links
- Private: no accounts, no tracking, answers never leave the browser
- Accessible: Atkinson Hyperlegible font, 44px touch targets, keyboard focus rings, dark mode, reduced-motion support

## Tech stack
Plain HTML, CSS, and JavaScript in a single file (`index.html`). No build step, no dependencies, works offline once loaded.
Matching logic: each service has a `req` list; a service shows when `req` is empty or any requirement matches the user's answers.


## Team
Noura Oraif.
