# Obsidian Plugin For obsidian-tools

Obsidian Plugin for obsidian-tools (https://github.com/antfie/obsidian-tools).

## Local Development

Install the BRAT plugin.

## Releasing

```bash
docker run -v "$(pwd):/app" --rm -it -w /app --entrypoint bash node /app/scripts/build.sh
```

Release the following files:
- main.js
- manifest.json
