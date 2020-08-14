# 👨‍💻 Developer Guide: macOS

The following list summarizes some of the relevant tools for developers on macOS.

| Name | Type | URL | Part of dotfiles |
| ---- | ---- | --- | ---------------- |
| iTerm2 | Terminal | [link](https://iterm2.com/) | ✔️ |
| Oh My Zsh | Terminal Extension | [link](https://github.com/ohmyzsh/ohmyzsh) | ✔️ |
| Powerlevel10k | Terminal Theme | [link](https://github.com/romkatv/powerlevel10k) | ✔️ |
| Zsh Autosuggestions | Terminal Extension | [link](https://github.com/zsh-users/zsh-autosuggestions) | ✔️ |
| VSCode | IDE | [link](https://code.visualstudio.com/download) | ✔️ |
| [IntelliJ](#intellij-settings) | IDE | [link](https://www.jetbrains.com/de-de/idea/download/#section=mac) | ✔️ |
| Firefox | Browser | [link](https://www.mozilla.org/de/firefox/download/thanks/) | ✔️ |
| Postman | REST Client | [link](https://www.postman.com/downloads/) | ✔️ |
| Spotify | Music (dont get bored) | [link](https://www.spotify.com/de/download/mac/) | ✔️ |
| SDKMAN | SDK Manager | [link](https://github.com/sdkman/sdkman-cli) | - |
| Homebrew | Package Manager | [link](https://brew.sh/index_de) | ✔️ |
| Enpass | Password Manager | [link](https://www.enpass.io/) | ✔️ |
| gopass | Password Store CLI | [link](https://github.com/gopasspw/gopass) | ✔️ |
| Docker | Container Management | [link](https://docs.docker.com/docker-for-mac/) | ✔️ |
| Cloud Foundry CLI | CLI | [link](https://docs.cloudfoundry.org/cf-cli/install-go-cli.html) | ✔️ |
| Kubernetes CLI | CLI | [link](https://kubernetes.io/docs/tasks/tools/install-kubectl/#install-kubectl-on-macos) | ✔️ |
| Flutter | Hybrid App Framework | [link](https://flutter.dev/docs/get-started/install) | - |
| Node.js | JavaScript Framework | [link](https://nodejs.org/en/download/) | ✔️ |

## Setup your Mac with ease

While setting up a sparkling fresh Mac can be of course a lot of fun, it is somtimes required to get started real fast. In order to speed up the transformation from a freshly installed Mac to a fully setup developer machine, you can utilize the following [dotfiles](https://github.com/timoknapp/.files#install). After the installation is done, dont forget about the [post-installation](https://github.com/timoknapp/.files#post-install). When both is done you will have a properly setup Mac with all tools you need to get coding started. If you want to review the tools which are part of the setup go [here (brew)](https://github.com/timoknapp/.files/blob/master/install/Brewfile) and [here (brew cask)](https://github.com/timoknapp/.files/blob/master/install/Caskfile).

## Custom Setup

### IntelliJ Settings

Run following commands to zip the settings and after that import them `File > Import Settings...`

```
cd IntelliJ
zip -r settings.zip settings
```

## Contribution

Feel free to extend: PRs welcome!
