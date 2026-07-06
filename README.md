# Alisa Zhao's Backpack

Public-safe, recruiter-facing version of Alisa Zhao's personal portfolio.

## Overview

This portfolio is built around personal object-based storytelling: a backpack, a room, project cards, and exploratory interactions that let visitors discover work through a soft editorial interface instead of a conventional resume page.

The site includes dedicated pages for About, Projects, Experience, and Off the Record, with interactive project overlays, timeline layouts, visual galleries, and a private, narrative-driven design system.

## Links

- Live demo: `https://all-about-alisa.vercel.app/`
- Public GitHub repo: `https://github.com/alsz322/all-about-alisa`

## Tech Stack

- HTML
- CSS
- JavaScript
- Tailwind via CDN / browser runtime on selected pages
- GSAP on the landing page
- Vercel for deployment

## Key Features

- Interactive landing page inspired by a desktop / backpack metaphor
- Recruiter-facing project archive with detail overlays
- Timeline-based education and experience page
- Personal About page with editorial motion and identity storytelling
- Off the Record page with music, map, room, skating, and Animal Crossing-inspired personal sections
- Lightweight scroll and entrance animations using CSS and native JavaScript

## Design Concept

The portfolio uses personal object-based storytelling rather than a standard template. The backpack, room, charms, photos, and project windows act as narrative objects that reveal different parts of the work.

The visual direction combines exploratory interaction, soft editorial pacing, delicate grid backgrounds, 1px borders, restrained color accents, and a personal but professional tone.

## Local Setup

Because this is a static site, you can run it with any local static server.

```bash
python3 -m http.server 5500
```

Then open:

```text
http://localhost:5500/index.html
```

## Environment Variables

This static version does not require environment variables.

If future features require API keys, keep real values in `.env` files only and document empty examples in `.env.example`.

## Privacy Note

This public-safe repository does not include real personal photos, private project images, audio files, video files, resume PDFs, or other private media assets.

The original file paths are preserved in the code so the structure and design logic remain understandable. Production deployments may use private assets from a private repository or deployment-only storage.

## AI-Assistance Note

The concept, design direction, content strategy, personal narrative, project selection, and editorial voice are my own.

The coding implementation was AI-assisted. I directed the product decisions, interaction design, visual system, content structure, and iteration process, then reviewed and edited the implementation.

## Public-Safe Version

This repository is intended as a recruiter-facing / public-safe code sample. It is not a full source dump of every private image or personal artifact used in the live portfolio.
