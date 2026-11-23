# Eureka — Reimagined

A clickable prototype that turns ALLEN's Eureka app from a content feed into a guided study plan.

## What it is / why I built it

Eureka (by ALLEN) gives Class 10 board students a library of story-style episodes, but drops them into a feed with no sense of what to study first, how concepts connect, or whether they're on pace. Progress starts at a cold 0%.

This prototype makes the fix tappable: a short placement questionnaire, a "today's plan" home ordered around the student's weakest subject, and a concept map where every concept is linked by prerequisite — the structure the app needs to always know what to recommend next. It's a companion to my [ALLEN AI Doubt Solver](https://github.com/devvbuilds-png/Allen-prototype) prototype.

> Independent concept prototype. Not affiliated with or endorsed by ALLEN.

## Features

- **6-question setup** — board (CBSE / ICSE / State), exam timing, and per-subject confidence.
- **Today's plan home** — a focus chapter with episode count and time, a "start episode" CTA, this week's plan, and a "Why this order?" explanation.
- **Concept map** — syllabus → subject → concept graph; tap a node to see what it connects to.
- **Progress screen** — plan completion tied to the board date, per-subject progress and the next milestone badge.
- Phone-frame UI with bottom navigation and a restart button.

## Tech

A single self-contained `index.html` (HTML, CSS and vanilla JS, no dependencies). Content is mock data.

## Run locally

Open `index.html` in a browser.

## Status

Clickable concept prototype.
