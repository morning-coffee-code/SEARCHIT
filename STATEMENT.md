# Project Statement

## Problem

People often want a quick, digestible explanation of an unfamiliar topic — a person, place, concept, or event — without navigating away to a cluttered encyclopedia page full of citations, sidebars, and links. Searching Wikipedia directly can be slow on mobile, visually noisy, and interrupts the flow of whatever the person was originally doing.

## Solution

**SearchIT** is a lightweight, single-page web app that provides a focused, elegant way to explore any topic. It takes a search term, finds the closest matching Wikipedia article, and presents just the essential information — title, image, and summary — in a clean, readable card, with an option to jump to the full article if more depth is wanted.

## Goals

- **Simplicity** — one input box, one action, one clear result state at a time (idle, loading, error, or result)
- **Speed** — minimal UI with no unnecessary steps between query and answer
- **Clarity** — an editorial, encyclopedia-inspired visual style (serif headings, warm parchment palette, gold accents) that makes reading feel pleasant rather than clinical
- **Accessibility of discovery** — pre-set "quick search" suggestions to invite exploration for users who don't have a specific topic in mind
- **Zero setup** — a fully self-contained HTML file with no backend, build tools, or dependencies required to run

## Non-Goals

- This is not a replacement for Wikipedia itself — it does not aim to reproduce full articles, editing capability, citations, or talk pages.
- It does not store search history, user accounts, or personal data.
- It is not intended to fact-check or curate content; it simply surfaces Wikipedia's own summary as-is.

## Target Audience

Curious learners, students, and casual readers who want a fast, low-friction way to get a quick, well-presented answer to "what is this?" or "who was that?" — with the option to go deeper on Wikipedia when the topic warrants it.

## Success Criteria

- A user can go from typing a topic to reading a relevant summary in under a few seconds.
- The app clearly communicates its state at all times (loading, error, or result) so the user is never left wondering what's happening.
- The interface works cleanly across both desktop and mobile screen sizes.
