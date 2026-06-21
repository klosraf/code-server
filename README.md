# code-server

> Web-based VS Code development environment for remote coding, cloud IDEs, and containerized workspaces.

A fork of [code-server](https://github.com/coder/code-server) — explore, customize, and experiment with browser-based VS Code.

## Features

- Full VS Code in the browser
- Containerized deployment ready
- Custom extensions and themes
- Remote development without local setup

## Deployment

```bash
docker run -d \
  --name code-server \
  -p 8080:8080 \
  -v "${HOME}/.config:/home/coder/.config" \
  codercom/code-server:latest
```

## License

MIT
