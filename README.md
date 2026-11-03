# Garganta website

Public landing page and interactive demonstration of Garganta, a local workspace for AI development agents.

**Website:** https://ericjoyboy.github.io/garganta-website/

The five-stage walkthrough uses fictional issues, sample code, synthetic timings and example verification reports. It does not run an agent, call external APIs, read local files or deploy software. The 60-second video is a silent visual tour with English captions.

## Preview locally

```sh
python3 -m http.server 8786 --bind 127.0.0.1
```

Open http://127.0.0.1:8786. No build step or npm install is required.

## Deployment

GitHub Pages publishes the root of the `main` branch. `.nojekyll` keeps the static files unchanged. Push an update to publish it.

This repository contains only the website. Garganta's application source remains a private alpha. This website's publication does not announce a public source release or grant a license to the application.

Built by [Eric](https://github.com/EricJoyBoy).
