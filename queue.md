# Queue

- Check DNS for `sovgrid.ca` until it resolves consistently to GitHub's IPs (BLOCKED-ON-EXTERNAL: DNS propagation, partially resolving as of 12:42 PST; unblock signal: `nslookup sovgrid.ca 8.8.8.8` returns 185.199.108-111.153).
- Once DNS resolves and GitHub has issued the certificate, turn on Enforce HTTPS via `gh api -X PUT repos/EmmaLeonhart/sovgrid-website/pages -F https_enforced=true`, then load https://sovgrid.ca and https://www.sovgrid.ca to confirm.
