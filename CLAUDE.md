# MyApps Dashboard

Static nginx-served landing page (`index.html`) linking out to the other self-hosted services
running on this machine. Central entry point for the home LAN — port 80.

Run it: `docker compose up -d` from this directory (see `docker-compose.yml`). Purely static; edit
`index.html` and restart/reload nginx to change links.

Update its links whenever a project's port changes — see `~/Projects/second-brain/docs/infra.md`
for the current port map.
