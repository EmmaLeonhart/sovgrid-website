# What this project is for

_Maintained by Claude: a running read of what the user is trying to do. It is
analysis, not a transcript, and it changes as understanding improves._

Work mode started: Sun Oct 4 12:16 PST 2026 (from `date`), when the user said
"Set everything up to the maximum extent you possibly can."

## Current understanding

This repo is the public website for **SovGrid**, a company Emma is starting
with a friend. In her words (dictated, 2026-10-04): "a company that's purpose
is to build do solar energy for Canadian data centers to help help provide
environmentally friendly green energy to resolve power grid issues and get them
off of draining the local power grid or using natural gas".

The site is hosted on GitHub Pages at the domain `sovgrid.ca`, which she bought
on 2026-10-04 at Namecheap. "We're going to be using GitHub pages. This is the
website of it."

Founders, as Emma typed them (2026-10-04): "Arkhos Winter and Emma Leonhart".
Both are named on the site as co-founders; no roles or titles given yet.

## What supports it

- Chat, 2026-10-04 (sessions/2026-10-04_c9fb0e97.md).
- Folder name `sovgrid.ca`, chosen by the user (`auto_named: false`).
- Emma set up the Namecheap DNS records (4 GitHub A records on `@`, CNAME
  `www` → `emmaleonhart.github.io.`) during the session.

## Constraints from the user

- **The repo is public.** "this is a public repo using GitHub pages. We don't
  have classified company documents on here or anything. It's a public repo."
  This includes `sessions/` transcripts; she chose that knowingly (offered a
  separate site repo, chose this one). This overrides the cleanvibe default of
  private.
- **Do as much of the setup as possible without her.** "Set everything up to
  the maximum extent you possibly can ... set it up to already do everything."
- She wants plain, copy-paste-ready instructions for anything she must do by
  hand: "Please just give me the things I need. Give me copy-paste boxes".

## How the site is built

- Static site in `docs/`, served by GitHub Pages from `main` / `/docs`, so the
  rest of the repo (sessions, data_lake) is not rendered as site pages.
- `docs/CNAME` holds `sovgrid.ca`.

## Open questions

- Contact address for the site (e.g. an email at sovgrid.ca). NEEDS-DECISION
  (Emma). No email is set up on the domain yet as far as known.
- What the site should do beyond a landing page (pitch to data-centre
  operators? investors?). Asked, not yet answered. Assumption for now: a
  clear one-page landing site describing the company's purpose, with no
  invented figures, clients or claims.

## Confidence

High on purpose and hosting (stated directly). Low on anything about the
company beyond its one-sentence purpose.
