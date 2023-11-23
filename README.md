[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/peter-gy/iml-pa3/HEAD)
[![Open in GitHub Codespaces](https://img.shields.io/badge/launch-Codespaces-blue)](https://github.com/codespaces/new?hide_repo_select=true&ref=main&repo=313704611&machine=standardLinux32gb&devcontainer_path=.devcontainer%2Fdevcontainer.json&location=WestEurope)

# Steps To Reproduce

## Via Binder

> Zero local setup, minutes to wait though for Binder to start

You can run the notebook with zero local setup via binder: [https://mybinder.org/v2/gh/peter-gy/iml-pa3/HEAD](https://mybinder.org/v2/gh/peter-gy/iml-pa3/HEAD)

## Via GitHub Codespaces

> Dev Container, remotely

You can run and tweak the notebook with zero local setup via GitHub Codespaces: [https://github.com/codespaces/new?hide_repo_select=true&ref=main&repo=313704611&machine=standardLinux32gb&devcontainer_path=.devcontainer%2Fdevcontainer.json&location=WestEurope](https://github.com/codespaces/new?hide_repo_select=true&ref=main&repo=313704611&machine=standardLinux32gb&devcontainer_path=.devcontainer%2Fdevcontainer.json&location=WestEurope).

## Via VS Code Dev Container

> Dev Container, locally

1. Install [VS Code](https://code.visualstudio.com/).
2. Install the [Remote - Containers](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers) extension.
3. Install Docker Desktop following the [docs](https://docs.docker.com/get-docker/).
4. Clone this repository.
5. Open this folder in VS Code.
6. Click the button in the bottom left corner and select "Reopen in Container".
7. Wait for the container to build.
8. Open the terminal in VS Code and run `jupyter notebook --allow-root`
9. Open the notebook in the browser.

## Via Local Setup

1. Install Python 3.10+
2. Install the dependencies and start the notebook from this folder:

```bash
pip install jupyter notebook jupyterlab matplotlib scipy numpy pandas altair tqdm vl-convert-python scikit-learn
jupyter notebook
```
