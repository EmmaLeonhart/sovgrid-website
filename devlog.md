# Devlog

## 2026-10-04

- Work mode started at 12:16 PST. INTENT.md written from the chat.
- Built the first landing page in `docs/` (index, 404, favicon, CNAME `sovgrid.ca`, `.nojekyll`). Content sticks to the company's stated purpose: no figures, clients or names that haven't been confirmed.
- Emma set the Namecheap DNS records (4 A records on `@`, CNAME `www`).
- Created public repo EmmaLeonhart/sovgrid-website, pushed, enabled GitHub Pages (main, /docs) with custom domain sovgrid.ca. First build succeeded; emmaleonhart.github.io/sovgrid-website 301s to sovgrid.ca, and the page serves correctly when requested from GitHub's IP directly. sovgrid.ca itself is not yet in the .ca registry's DNS (NXDOMAIN at 12:19 PST).
- 12:23 PST: added a Founders section to the site (Arkhos Winter, Emma Leonhart, both "Co-founder"), with the spelling Emma confirmed.
- 12:27 PST: added a Contact section (emma@topazcomputing.com) and a footer line "a subsidiary of Topaz Computing", linking to topazcomputing.com.
- 12:42 PST: DNS is propagating. Google DNS answers sovgrid.ca with the four GitHub IPs on some queries and NXDOMAIN on others; www.sovgrid.ca resolves and 301s to sovgrid.ca. GitHub has not issued the HTTPS certificate yet ("The certificate does not exist yet"), so HTTPS can't be enforced. Domain is still "unverified" with GitHub (needs Emma's TXT record).
