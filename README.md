# jube.dev

Juan C. Beaver's portfolio site — a single static `index.html`, no build step.

## Local preview

Open `index.html` directly in a browser, or serve it locally:

```
python3 -m http.server 8000
```

## Deployment

Pushing changes to `index.html` or `CNAME` on `master` triggers `.github/workflows/deploy.yml`,
which publishes the site to the `gh-pages` branch (served at [jube.dev](https://jube.dev)).
