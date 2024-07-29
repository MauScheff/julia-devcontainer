
# Julia (julia)

Develop Julia applications in VSCode

# Locally
0. Install docker (https://docs.docker.com/engine/install/)
0.1 Install devcontainers extension in VSCode https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers
1. $ git clone https://github.com/MauScheff/julia-devcontainer.git
2. $ cd julia-devcontainer
3. $ code .
4. Wait for vscode to detect Dev Container and click open in container in bottom right dialog.
4. Alternatively, open the command palette (CMD+SHIFT+P) and write "reopen in container".

# Remotely with Github Codespaces
1. Open with browser https://github.com/MauScheff/julia-devcontainer
2. Click on fork and fork it.
3. Go to your forked repo and click on green code button then HTTPS / Copy url to clipboard.
4. $ git clone PASTE URL
5. With VSCODE command palette (CMD+SHIFT+P) write "create new codespace" and follow instructions.
6. Manage your workspaces on github website (https://github.com/codespaces).