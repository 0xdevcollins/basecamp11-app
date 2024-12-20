# Basecamp 11 App

This repository will be used by the teachers of Basecamp 11 to progressively build a Starknet application from start to finish that will include smart contracts, testing and frontend.

## Dev Environment

To activate the dev environment, make sure to have [Docker](https://www.docker.com/get-started/) and [VSCode](https://code.visualstudio.com/) installed on your system. On VSCode, make sure to install the [Dev Containers](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers) extension to make use of [this](https://hub.docker.com/r/starknetfoundation/starknet-dev) Docker image for Starknet development.

To launch an instance fo VSCode inside the container, go to `View` -> `Command Palette` and execute the command `Dev Containers: Rebuild and Reopen in Container`. At this point you should have an instance of VSCode with access to all required binaries (Scarb, Foundry, Starkli, etc.) on the integrated terminal and syntax highlighter for Cairo and Toml files.