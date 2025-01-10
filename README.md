# richallen.info
---
The website for Rich Allen

## Development
---
### Setup environment
Install Docker Desktop on Windows:

```
\$ winget install -e --id Docker.DockerDesktop
```

Install Docker Desktop on MacOS:

```
\$ brew install --cask docker
```

### Day-to-day Development

To run a server locally:
```
\$ docker compose up
```

Or open the project as a dev container and directly start the server:
```
\$ bundle exec jekyll serve --force_polling --livereload --port 4002
```

Configuration
The Minimal Mistakes skin was customized by copying the original main.scss file to assets\css. Any changes to the theme's Sass variables must be made before the any @importlines.
