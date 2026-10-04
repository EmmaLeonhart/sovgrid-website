# sovgrid.ca

Website for **SovGrid**, a company building solar energy for Canadian data
centres, so they can grow without straining the local power grid or relying on
natural gas.

Live at <https://sovgrid.ca> (GitHub Pages).

## Layout

- `docs/` — the website. GitHub Pages serves this folder from the `main`
  branch. Plain HTML and CSS, no build step.
  - `docs/CNAME` — the custom domain (`sovgrid.ca`). Don't delete it.
- `INTENT.md` — the running notes on what the project is for and open
  questions.
- `queue.md`, `todo.md`, `devlog.md` — current work, longer-term ideas, and
  what has been done.
- `sessions/` — transcripts of the Claude sessions that built this.

## Editing the site

Edit `docs/index.html` and push to `main`. GitHub Pages republishes within a
minute or two.

## DNS (Namecheap)

| Type  | Host  | Value                     |
|-------|-------|---------------------------|
| A     | `@`   | `185.199.108.153`         |
| A     | `@`   | `185.199.109.153`         |
| A     | `@`   | `185.199.110.153`         |
| A     | `@`   | `185.199.111.153`         |
| CNAME | `www` | `emmaleonhart.github.io.` |

## Working on it

Run `cleanvibe` in this folder (or double-click `!runClaude.bat` on Windows) to
open a new Claude session here.
