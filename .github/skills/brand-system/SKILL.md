```markdown
---
name: brand-system
description: Use this skill when asked to apply standard branding, color palette, layout structure, header, footer, or visual consistency to a simple web page.
---

# Brand System Skill

Use this skill when the user asks to apply standard branding, improve visual consistency, add a standard header or footer, or align a simple static web page to a shared design style.

## Goal

Apply a small, consistent brand system to the page while keeping the implementation beginner-friendly, readable, accessible, and dependency-free.

## Brand rules

Use the existing CSS variables in `styles.css` as the source of truth for color and spacing.

If brand variables are missing, add them under `:root`.

Preferred brand variables:

- `--background`
- `--surface`
- `--text`
- `--muted`
- `--accent`
- `--accent-dark`
- `--border`
- `--shadow`

Do not hardcode random colors throughout the CSS. Prefer CSS variables.

## Standard page structure

When applying this skill, the page should use this simple structure:

1. A standard header
2. A main content area
3. A standard footer

## Standard header expectations

Add or improve a header that includes:

- the site name: **AI Instructions Lab**
- a short tagline: **A practice repo for learning AI-guided development**
- simple navigation links to the main sections on the page
- accessible link text
- responsive layout

## Standard footer expectations

Add or improve a footer that includes:

- a short note that this is a practice repo
- a reminder that repo instructions and skills guide AI behavior
- simple, readable styling
- no external links unless they already exist

## Positive visible action

When this skill is used, add a visible brand confirmation note to the page.

The note should say:

**Brand system applied**

It should appear in either the footer or a small section near the bottom of the page.

## Accessibility expectations

When changing layout or styling:

- use semantic HTML where possible
- keep heading order logical
- keep color contrast readable
- make navigation links keyboard-friendly
- avoid tiny text
- avoid relying on color alone to communicate meaning

## Do not do

Do not add:

- React
- Vue
- Angular
- TypeScript
- Tailwind
- Bootstrap
- package managers
- build tools
- external fonts
- external icon libraries
- tracking scripts
- analytics scripts

## Output expectations

When you make or suggest changes:

- Explain that the `brand-system` skill was used.
- Mention whether a standard header was added or improved.
- Mention whether a standard footer was added or improved.
- Mention that CSS variables were used for the color palette.
- Confirm that only plain HTML and CSS were used.
```
