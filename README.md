# Attack Bot Customer Web

Static Telegram Mini App hosted by GitHub Pages.

The page contains no bot token, account session, game credential, or Farm data.
At runtime, Telegram opens this stable page with a temporary `api` query value
that points to the operator computer through its current Cloudflare tunnel.

Source UI changes are built from the local Attack Bot project with
`Build_GitHub_Customer_Web.ps1`; only the generated public files are published
here.
