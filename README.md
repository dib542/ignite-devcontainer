An environment for using Ignite CLI and Cosmos SDK / Cosm.js within VSCode easily.

For more info on how this works, see: https://code.visualstudio.com/docs/remote/containers

# How to use

1. After opening this project in VS Code, use the Remote Containers extension to "Reopen in container", and VS Code will build this docker enviroment where you can open a new terminal that starts inside the docker container. You can use `ignite scaffold chain ...` from this VS Code terminal to scaffold a new ignite project.

2. And/or in a scaffolded ignite project you can copy the `.devcontainer` directory here into your main project directory and then use the Remote Containers extension to "Reopen in container". Your project should now have Go and the Go and proto extensions available and connected (even without having Go installed on your local machine).

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
- Ignite CLI
- [VS Code Go extenstion](https://marketplace.visualstudio.com/items?itemName=golang.Go)
- [VS Code Proto3 extension](https://marketplace.visualstudio.com/items?itemName=zxh404.vscode-proto3)

See `.devcontainer/Dockerfile` for exact version numbers.
