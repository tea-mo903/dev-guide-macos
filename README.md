# 👨‍💻 Developer Guide: macOS

The following list summarizes some of the relevant tools for developers on macOS.

| Name | Type | URL | Part of dotfiles |
| ---- | ---- | --- | ---------------- |
| iTerm2 | Terminal | https://iterm2.com/ | ✔️ |
| Oh My Zsh | Terminal Extension | https://github.com/ohmyzsh/ohmyzsh | ✔️ |
| Powerlevel10k | Terminal Theme | https://github.com/romkatv/powerlevel10k | ✔️ |
| Zsh Autosuggestions | Terminal Extension | https://github.com/zsh-users/zsh-autosuggestions | ✔️ |
| VSCode | IDE | https://code.visualstudio.com/download | ✔️ |
| [IntelliJ](#intellij-settings) | IDE | https://www.jetbrains.com/de-de/idea/download/#section=mac | ✔️ |
| Firefox | Browser | https://www.mozilla.org/de/firefox/download/thanks/ | ✔️ |
| Postman | REST Client | https://www.postman.com/downloads/ | ✔️ |
| Spotify | Music (dont get bored) | https://www.spotify.com/de/download/mac/ | ✔️ |
| SDKMAN | SDK Manager | https://github.com/sdkman/sdkman-cli | - |
| Homebrew | Package Manager | https://brew.sh/index_de | ✔️ |
| Enpass | Password Manager | https://www.enpass.io/ | ✔️ |
| gopass | Password Store CLI | https://github.com/gopasspw/gopass | ✔️ |
| Docker | Container Management | https://docs.docker.com/docker-for-mac/ | ✔️ |
| Cloud Foundry CLI | CLI | https://docs.cloudfoundry.org/cf-cli/install-go-cli.html | ✔️ |
| Kubernetes CLI | CLI | https://kubernetes.io/docs/tasks/tools/install-kubectl/#install-kubectl-on-macos | - |
| Flutter | Hybrid App Framework | https://flutter.dev/docs/get-started/install | - |
| Node.js | JavaScript Framework | https://nodejs.org/en/download/ | ✔️ |

## Setup your Mac with ease

While setting up a sparkling fresh Mac can be of course a lot of fun, it is somtimes required to get started real fast. In order to speed up the transformation from a freshly installed Mac to a fully setup developer machine, you can utilize the following [dotfiles](https://github.com/timoknapp/dotfiles#install). After the installation is done, dont forget about the [post-installation](https://github.com/timoknapp/dotfiles#post-install). When both is done you will have properly setup Mac with all tools you need to get coding started. If you want to review the tools which are part of the setup go [here (brew)](https://github.com/timoknapp/dotfiles/blob/master/install/Brewfile) and [here (brew cask)](https://github.com/timoknapp/dotfiles/blob/master/install/Caskfile).

## Custom Setup

### IntelliJ Settings

Run following commands to zip the settings and after that import them `File > Import Settings...`

```
cd IntelliJ
zip -r settings.zip settings
```

## Contribution

Feel free to extend: PRs welcome!
