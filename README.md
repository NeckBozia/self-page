# self-page

Personal site at [neckbozia.com](https://neckbozia.com).

## Stack

- Astro 5 + Tailwind v4 + MDX
- Geist + Geist Mono (self-hosted via `@fontsource-variable`)
- Deployed to a Proxmox LXC, exposed via Cloudflare Tunnel

## Develop

```sh
npm install
npm run dev      # http://localhost:4321
npm run build    # → ./dist
```

## Deploy

`git push origin main` triggers a webhook on the LXC, which pulls and rebuilds.
