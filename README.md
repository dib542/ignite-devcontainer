An environment for using Ignite CLI and Cosmos SDK / Cosm.js within VSCode easily.

For more info on how this works, see: https://code.visualstudio.com/docs/remote/containers

# Requirements

- [Docker](https://docs.docker.com/get-docker/)
- [VS Code](https://code.visualstudio.com/Download)
- [VS Code extension: Remote - Containers](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers)

# Container environment

Is Linux Debian "bullseye" release image maintained by Microsoft for VS Code: Remote Containers extension.

Includes:
- git
- Go
- Node (+ nvm + yarn)
- Rust
- Ignite CLI
- [VS Code Proto3 extension](https://marketplace.visualstudio.com/items?itemName=zxh404.vscode-proto3)
- Other extensions from base VSC-Go docker image

See `.devcontainer/devcontainer.json` for exact version numbers.
