# Data Analytics Checklist

A live, interactive tracker for my personal data analytics learning roadmap built to stay accountable and give anyone (recruiters, mentors, friends) visibility into exactly what I'm working on and when.

**🔗 Live site:** https://gomzy-limbo.github.io/data-analytics-checklist/

---

## What it does

- Breaks my learning roadmap (SQL → Excel → Power BI → Python → Azure/AWS, plus Git, statistics, and job-readiness prep) into sections and subsections
- Each subsection gets own self-imposed deadline when i start the parent section, with a status badge (on track / due soon / overdue / done)
- Tracks progress with checkboxes and a live progress bar per section and overall
- Lets me add custom sections or items as my plan evolves
- Progress is exported as `progress.json` and committed to this repo, so the live link always reflects my real, current status and not a stale snapshot

## Why I built it

Most learning roadmaps live in a notes app or a spreadsheet nobody else ever sees. I wanted something public and specific enough that I couldn't quietly fall behind without noticing and something that would let anyone I'm talking to (a mentor, a recruiter, a friend keeping me honest) see exactly where I actually am, not just what I claim to know.

## Tech

Single-file HTML/CSS/JavaScript, no frameworks or build step. Progress persists via browser `localStorage` for live editing, and is published as a static `progress.json` snapshot for anyone visiting without their own saved state. Hosted on GitHub Pages.

## Status

Actively in use —> see the live link above for my current progress.
