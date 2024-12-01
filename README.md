**Prepare**\
`sudo mkdir -p /srv/gitlab`

**Generate ssl**\
`docker compose --env-file .env.ssl up -d`\
`docker compose --env-file .env.ssl down`

**Run**\
`docker compose --env-file .env.prod up -d`\
`docker compose --env-file .env.prod down`
