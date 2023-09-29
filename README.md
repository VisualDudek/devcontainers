# DevContainers Templates Repository

Welcome to the DevContainers Templates Repository! This repository contains a collection of development container templates to streamline the setup of development environments for various projects and technologies. Using DevContainers can help ensure consistency and ease of collaboration across your development team.

## Table of Contents

1. [Introduction](#introduction)
2. [Getting Started](#getting-started)
   - [Prerequisites](#prerequisites)
   - [Usage](#usage)
3. [Templates](#templates)
4. [Contributing](#contributing)
5. [License](#license)

## Introduction

DevContainers, powered by Visual Studio Code and Docker, allow you to define development environments as code. With this repository, you can quickly set up development environments tailored to your specific projects or technologies, all within isolated containers. This ensures that everyone working on your project uses the same development environment configuration, making it easier to collaborate and onboard new team members.

## Getting Started

### Prerequisites

Before you get started, you'll need the following tools installed on your system:

- [Docker](https://www.docker.com/get-started)
- [Visual Studio Code](https://code.visualstudio.com/) with the [Remote - Containers extension](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers) installed.

### Usage

1. Clone this repository to your local machine:
2. Open the desired template directory in Visual Studio Code.
3. **Open in a DevContainer:** <br/> With VS Code, use the command palette (`Cmd/Ctrl + Shift + P`) and choose "Remote-Containers: Open Folder in Container..." and select the template directory.
4. **Start developing within the container**: </br> All the required tools and dependencies will be available within the isolated environment. </br> The container will build based on the specifications of the `Dockerfile` and `.devcontainer/devcontainer.json` in the chosen template. Once it's done, you'll have a fully configured development environment ready to go!

> Visual Studio Code will automatically detect the DevContainer configuration and ask if you want to reopen the project in a development container. Confirm to start the container.

## License
This project is licensed under the MIT License. Feel free to use, modify, and distribute the templates as needed.

Happy coding!
