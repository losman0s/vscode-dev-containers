# [dotnet](https://github.com/microsoft/vscode-dev-containers/tree/main/containers/dotnet)

**Image version:** dev

**Source release/branch:** [main](https://github.com/microsoft/vscode-dev-containers/tree/main/containers/dotnet)

**Definition variations:**
- [6.0-bullseye-slim](#variant-60-bullseye-slim)
- [6.0-focal](#variant-60-focal)
- [3.1-bullseye](#variant-31-bullseye)
- [3.1-focal](#variant-31-focal)

## Variant: 6.0-bullseye-slim

**Digest:** sha256:74d8a240ad9d4d9307123503bf7215515e923570f1684c100be73b9485f15912

**Tags:**
```
mcr.microsoft.com/vscode/devcontainers/dotnet:dev-6.0-bullseye-slim
mcr.microsoft.com/vscode/devcontainers/dotnet:dev-6.0
mcr.microsoft.com/vscode/devcontainers/dotnet:dev-6.0-bullseye
```
> *To keep up to date, we recommend using partial version numbers. Use the major version number to get all non-breaking changes (e.g. `0-`) or major and minor to only get fixes (e.g. `0.200-`).*

**Linux distribution:** Debian GNU/Linux 11 (bullseye)

**Architectures:** linux/amd64, linux/arm64

**Available (non-root) user:** vscode

### Contents
**Languages and runtimes**

| Language / runtime | Version | Path |
|--------------------|---------|------|
| [.NET](https://dotnet.microsoft.com/) | 6.0.302 (6.0.7) | /usr |

**Tools installed using git**

| Tool | Commit | Path |
|------|--------|------|
| [Oh My Zsh!](https://github.com/ohmyzsh/ohmyzsh) | 8362ae285a5c227cb20387543483a3597fa31931 | /home/vscode/.oh-my-zsh |
| [nvm](https://github.com/nvm-sh/nvm.git) | 3fea5493a431ac64470d4230d4b51438cf213bd1 | /usr/local/share/nvm |

**Additional linux tools and packages**

| Tool / library | Version |
|----------------|---------|
| apt-transport-https | 2.2.4 |
| apt-utils | 2.2.4 |
| ca-certificates | 20210119 |
| curl | 7.74.0-1.3+deb11u1 |
| dialog | 1.3-20201126-1 |
| git | 1:2.30.2-1 |
| gnupg2 | 2.2.27-2+deb11u2 |
| htop | 3.0.5-7 |
| iproute2 | 5.10.0-4 |
| jq | 1.6-2.1 |
| less | 551-2 |
| libc6 | 2.31-13+deb11u3 |
| libgssapi-krb5-2 | 1.18.3-6+deb11u1 |
| libicu67 | 67.1-7 |
| libkrb5-3 | 1.18.3-6+deb11u1 |
| liblttng-ust0 | 2.12.1-1 |
| libssl1.1 | 1.1.1n-0+deb11u3 |
| libstdc++6 | 10.2.1-6 |
| locales | 2.31-13+deb11u3 |
| lsb-release | 11.1.0 |
| lsof | 4.93.2+dfsg-1.1 |
| man-db | 2.9.4-2 |
| manpages | 5.10-1 |
| manpages-dev | 5.10-1 |
| manpages-posix | 2017a-2 |
| manpages-posix-dev | 2017a-2 |
| nano | 5.4-2+deb11u1 |
| ncdu | 1.15.1-1 |
| net-tools | 1.60+git20181103.0eebece-1 |
| openssh-client | 1:8.4p1-5+deb11u1 |
| procps | 2:3.3.17-5 |
| psmisc | 23.4-2 |
| rsync | 3.2.3-4+deb11u1 |
| strace | 5.10-1 |
| sudo | 1.9.5p2-3 |
| unzip | 6.0-26 |
| vim-tiny | 2:8.2.2434-3+deb11u1 |
| wget | 1.21-1+deb11u1 |
| yarn | 1.22.19-1 |
| zip | 3.0-12 |
| zlib1g | 1:1.2.11.dfsg-2+deb11u1 |
| zsh | 5.8-6+deb11u1 |

## Variant: 6.0-focal

**Digest:** sha256:78605e35075b241b58f0cd52ad7527c6dd96fac129ca7b65bb2740ac4f6868a3

**Tags:**
```
mcr.microsoft.com/vscode/devcontainers/dotnet:dev-6.0-focal
```
> *To keep up to date, we recommend using partial version numbers. Use the major version number to get all non-breaking changes (e.g. `0-`) or major and minor to only get fixes (e.g. `0.200-`).*

**Linux distribution:** Ubuntu 20.04.4 LTS (debian-like distro)

**Architectures:** linux/amd64

**Available (non-root) user:** vscode

### Contents
**Languages and runtimes**

| Language / runtime | Version | Path |
|--------------------|---------|------|
| [.NET](https://dotnet.microsoft.com/) | 6.0.302 (6.0.7) | /usr |

**Tools installed using git**

| Tool | Commit | Path |
|------|--------|------|
| [Oh My Zsh!](https://github.com/ohmyzsh/ohmyzsh) | 8362ae285a5c227cb20387543483a3597fa31931 | /home/vscode/.oh-my-zsh |
| [nvm](https://github.com/nvm-sh/nvm.git) | 3fea5493a431ac64470d4230d4b51438cf213bd1 | /usr/local/share/nvm |

**Additional linux tools and packages**

| Tool / library | Version |
|----------------|---------|
| apt-transport-https | 2.0.9 |
| apt-utils | 2.0.9 |
| ca-certificates | 20211016~20.04.1 |
| curl | 7.68.0-1ubuntu2.12 |
| dialog | 1.3-20190808-1 |
| git | 1:2.25.1-1ubuntu3.5 |
| gnupg2 | 2.2.19-3ubuntu2.2 |
| htop | 2.2.0-2build1 |
| iproute2 | 5.5.0-1ubuntu1 |
| jq | 1.6-1ubuntu0.20.04.1 |
| less | 551-1ubuntu0.1 |
| libc6 | 2.31-0ubuntu9.9 |
| libgcc1 | 1:10.3.0-1ubuntu1~20.04 |
| libgssapi-krb5-2 | 1.17-6ubuntu4.1 |
| libicu66 | 66.1-2ubuntu2.1 |
| libkrb5-3 | 1.17-6ubuntu4.1 |
| liblttng-ust0 | 2.11.0-1 |
| libssl1.1 | 1.1.1f-1ubuntu2.16 |
| libstdc++6 | 10.3.0-1ubuntu1~20.04 |
| locales | 2.31-0ubuntu9.9 |
| lsb-release | 11.1.0ubuntu2 |
| lsof | 4.93.2+dfsg-1ubuntu0.20.04.1 |
| man-db | 2.9.1-1 |
| manpages | 5.05-1 |
| manpages-dev | 5.05-1 |
| manpages-posix | 2013a-2 |
| manpages-posix-dev | 2013a-2 |
| nano | 4.8-1ubuntu1 |
| ncdu | 1.14.1-1 |
| net-tools | 1.60+git20180626.aebd88e-1ubuntu1 |
| openssh-client | 1:8.2p1-4ubuntu0.5 |
| procps | 2:3.3.16-1ubuntu2.3 |
| psmisc | 23.3-1 |
| rsync | 3.1.3-8ubuntu0.3 |
| strace | 5.5-3ubuntu1 |
| sudo | 1.8.31-1ubuntu1.2 |
| unzip | 6.0-25ubuntu1 |
| vim-tiny | 2:8.1.2269-1ubuntu5.7 |
| wget | 1.20.3-1ubuntu2 |
| yarn | 1.22.19-1 |
| zip | 3.0-11build1 |
| zlib1g | 1:1.2.11.dfsg-2ubuntu1.3 |
| zsh | 5.8-3ubuntu1.1 |

## Variant: 3.1-bullseye

**Digest:** sha256:88b374d4f2fda7f3b65e2da9e668b0cbd3a31300e6e318e460b9a94a6d94fc13

**Tags:**
```
mcr.microsoft.com/vscode/devcontainers/dotnet:dev-3.1-bullseye
mcr.microsoft.com/vscode/devcontainers/dotnetcore:dev-3.1-bullseye
```
> *To keep up to date, we recommend using partial version numbers. Use the major version number to get all non-breaking changes (e.g. `0-`) or major and minor to only get fixes (e.g. `0.200-`).*

**Linux distribution:** Debian GNU/Linux 11 (bullseye)

**Architectures:** linux/amd64, linux/arm64

**Available (non-root) user:** vscode

### Contents
**Languages and runtimes**

| Language / runtime | Version | Path |
|--------------------|---------|------|
| [.NET](https://dotnet.microsoft.com/) | 3.1.421 (3.1.2) | /usr |

**Tools installed using git**

| Tool | Commit | Path |
|------|--------|------|
| [Oh My Zsh!](https://github.com/ohmyzsh/ohmyzsh) | 8362ae285a5c227cb20387543483a3597fa31931 | /home/vscode/.oh-my-zsh |
| [nvm](https://github.com/nvm-sh/nvm.git) | 3fea5493a431ac64470d4230d4b51438cf213bd1 | /usr/local/share/nvm |

**Additional linux tools and packages**

| Tool / library | Version |
|----------------|---------|
| apt-transport-https | 2.2.4 |
| apt-utils | 2.2.4 |
| ca-certificates | 20210119 |
| curl | 7.74.0-1.3+deb11u1 |
| dialog | 1.3-20201126-1 |
| git | 1:2.30.2-1 |
| gnupg2 | 2.2.27-2+deb11u2 |
| htop | 3.0.5-7 |
| iproute2 | 5.10.0-4 |
| jq | 1.6-2.1 |
| less | 551-2 |
| libc6 | 2.31-13+deb11u3 |
| libgssapi-krb5-2 | 1.18.3-6+deb11u1 |
| libicu67 | 67.1-7 |
| libkrb5-3 | 1.18.3-6+deb11u1 |
| liblttng-ust0 | 2.12.1-1 |
| libssl1.1 | 1.1.1n-0+deb11u3 |
| libstdc++6 | 10.2.1-6 |
| locales | 2.31-13+deb11u3 |
| lsb-release | 11.1.0 |
| lsof | 4.93.2+dfsg-1.1 |
| man-db | 2.9.4-2 |
| manpages | 5.10-1 |
| manpages-dev | 5.10-1 |
| manpages-posix | 2017a-2 |
| manpages-posix-dev | 2017a-2 |
| nano | 5.4-2+deb11u1 |
| ncdu | 1.15.1-1 |
| net-tools | 1.60+git20181103.0eebece-1 |
| openssh-client | 1:8.4p1-5+deb11u1 |
| procps | 2:3.3.17-5 |
| psmisc | 23.4-2 |
| rsync | 3.2.3-4+deb11u1 |
| strace | 5.10-1 |
| sudo | 1.9.5p2-3 |
| unzip | 6.0-26 |
| vim-tiny | 2:8.2.2434-3+deb11u1 |
| wget | 1.21-1+deb11u1 |
| yarn | 1.22.19-1 |
| zip | 3.0-12 |
| zlib1g | 1:1.2.11.dfsg-2+deb11u1 |
| zsh | 5.8-6+deb11u1 |

## Variant: 3.1-focal

**Digest:** sha256:cebf09090fd807c3fdc9caae95e8c6944df9f45ab698e941344ece83c0b2e489

**Tags:**
```
mcr.microsoft.com/vscode/devcontainers/dotnet:dev-3.1-focal
mcr.microsoft.com/vscode/devcontainers/dotnet:dev-3.1
mcr.microsoft.com/vscode/devcontainers/dotnetcore:dev-3.1
```
> *To keep up to date, we recommend using partial version numbers. Use the major version number to get all non-breaking changes (e.g. `0-`) or major and minor to only get fixes (e.g. `0.200-`).*

**Linux distribution:** Ubuntu 20.04.4 LTS (debian-like distro)

**Architectures:** linux/amd64

**Available (non-root) user:** vscode

### Contents
**Languages and runtimes**

| Language / runtime | Version | Path |
|--------------------|---------|------|
| [.NET](https://dotnet.microsoft.com/) | 3.1.421 (3.1.2) | /usr |

**Tools installed using git**

| Tool | Commit | Path |
|------|--------|------|
| [Oh My Zsh!](https://github.com/ohmyzsh/ohmyzsh) | 8362ae285a5c227cb20387543483a3597fa31931 | /home/vscode/.oh-my-zsh |
| [nvm](https://github.com/nvm-sh/nvm.git) | 3fea5493a431ac64470d4230d4b51438cf213bd1 | /usr/local/share/nvm |

**Additional linux tools and packages**

| Tool / library | Version |
|----------------|---------|
| apt-transport-https | 2.0.9 |
| apt-utils | 2.0.9 |
| ca-certificates | 20211016~20.04.1 |
| curl | 7.68.0-1ubuntu2.12 |
| dialog | 1.3-20190808-1 |
| git | 1:2.25.1-1ubuntu3.5 |
| gnupg2 | 2.2.19-3ubuntu2.2 |
| htop | 2.2.0-2build1 |
| iproute2 | 5.5.0-1ubuntu1 |
| jq | 1.6-1ubuntu0.20.04.1 |
| less | 551-1ubuntu0.1 |
| libc6 | 2.31-0ubuntu9.9 |
| libgcc1 | 1:10.3.0-1ubuntu1~20.04 |
| libgssapi-krb5-2 | 1.17-6ubuntu4.1 |
| libicu66 | 66.1-2ubuntu2.1 |
| libkrb5-3 | 1.17-6ubuntu4.1 |
| liblttng-ust0 | 2.11.0-1 |
| libssl1.1 | 1.1.1f-1ubuntu2.16 |
| libstdc++6 | 10.3.0-1ubuntu1~20.04 |
| locales | 2.31-0ubuntu9.9 |
| lsb-release | 11.1.0ubuntu2 |
| lsof | 4.93.2+dfsg-1ubuntu0.20.04.1 |
| man-db | 2.9.1-1 |
| manpages | 5.05-1 |
| manpages-dev | 5.05-1 |
| manpages-posix | 2013a-2 |
| manpages-posix-dev | 2013a-2 |
| nano | 4.8-1ubuntu1 |
| ncdu | 1.14.1-1 |
| net-tools | 1.60+git20180626.aebd88e-1ubuntu1 |
| openssh-client | 1:8.2p1-4ubuntu0.5 |
| procps | 2:3.3.16-1ubuntu2.3 |
| psmisc | 23.3-1 |
| rsync | 3.1.3-8ubuntu0.3 |
| strace | 5.5-3ubuntu1 |
| sudo | 1.8.31-1ubuntu1.2 |
| unzip | 6.0-25ubuntu1 |
| vim-tiny | 2:8.1.2269-1ubuntu5.7 |
| wget | 1.20.3-1ubuntu2 |
| yarn | 1.22.19-1 |
| zip | 3.0-11build1 |
| zlib1g | 1:1.2.11.dfsg-2ubuntu1.3 |
| zsh | 5.8-3ubuntu1.1 |

