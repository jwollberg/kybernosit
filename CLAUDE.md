# Kybernos IT — Site Guide

Read the master workspace guide first: [`..\CLAUDE.md`](../CLAUDE.md). It covers the
shared build recipe (Astro + GitHub Pages), the publish steps, and the domain-freeing
plan. This file only covers what's specific to Kybernos IT.

- **Domain:** kybernosit.com — *confirm current host with Josh; may point straight at
  GitHub Pages (not on Google Sites like the other two).*
- **What it is:** an IT services company. **Assumed** focus: managed IT / support /
  consulting for small businesses. **Confirm the exact services with Josh.**
- **Name note:** "Kybernos" is Greek for *helmsman / governor* (the root of both
  "cyber-" and "govern"). Good theme: a steady, expert hand at the helm of your
  technology — guidance, control, reliability.

## Positioning & voice

Professional, trustworthy, competent, modern. Reassuring to non-technical business
owners. Clean and techy but still human. Voice: clear, confident, jargon-free.

## Likely pages / sections

- **Hero** — what you do + who it's for, "Book a consult / Get a quote" button.
- **Services** — e.g. managed IT, helpdesk/support, cybersecurity, cloud & networking,
  backups. *(Confirm the real list.)*
- **Why us** — reliability, fast response, local, plain-English support.
- **How it works** — simple 3-step process.
- *(Later)* Testimonials.
- **Contact** — request a consult (form + email/phone).

## Selected design & locked decisions

- **Design: Option C — "Harbor"** (warm, friendly; serif headings, harbour/helm motif).
  Permanent Kybernos design. Working mockup: `design-options/option-c-harbor.html`.
- **Brand kit (applied):** lives in `brand-kit/` at the repo root; the files the site
  serves (favicon + logo) are copied into `public/brand-kit/`. Palette: **accent steel
  blue `#2F5D8A`**, paper `#FBFAF7` (backgrounds), ink `#262B33` (text). Fonts:
  **Marcellus** for headings/wordmark (single weight — never bold it) + **Jost** for
  body text. Wordmark is all-caps Marcellus with 0.22em letter-spacing; descriptor is
  Jost Medium, 0.42em. The Harbor layout was kept and recolored to this palette.
- **Remote-only.** All support is delivered **remotely — no on-site visits.** Keep
  "local / on-site / pop by" language off the site; emphasize remote support & monitoring,
  "help from anywhere."
- **No phone on the site.** Contact = **consult-request form + email** (info@kybernosit.com —
  the same address the form delivers to via FormSubmit).
- **Services (trimmed by Josh):** just **Managed IT** and **Helpdesk Support** (dropped
  Cybersecurity, Cloud & Networking, Backup & Recovery). Plus a "book a free consult" card.
- **Voice guardrail:** solo operator — read *neither* way. Neutral brand "we"; **never imply a
  team** ("our team/engineers", "meet the team") and **never say solo**.

**Status:** design locked; building "Harbor" into the real Astro + Tailwind site.
