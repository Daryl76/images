# [dotnet](https://github.com/devcontainers/images/tree/main/src/dotnet)

**Image version:** dev

**Source release/branch:** [main](https://github.com/devcontainers/images/tree/main/src/dotnet)

**Image variations:**
- [7.0-bullseye-slim](#variant-70-bullseye-slim)
- [7.0-jammy](#variant-70-jammy)
- [6.0-bullseye-slim](#variant-60-bullseye-slim)
- [6.0-jammy](#variant-60-jammy)
- [6.0-focal](#variant-60-focal)
- [3.1-bullseye](#variant-31-bullseye)
- [3.1-focal](#variant-31-focal)

## Variant: 7.0-bullseye-slim

**Digest:** sha256:2268edaf617169f57df45f2f528e3a22425a50ba8ec23c600400d83ed353dbdd

**Tags:**
```
mcr.microsoft.com/devcontainers/dotnet:dev-7.0-bullseye-slim
mcr.microsoft.com/devcontainers/dotnet:dev-7.0
mcr.microsoft.com/devcontainers/dotnet:dev-7.0-bullseye
```
> *To keep up to date, we recommend using partial version numbers. Use the major version number to get all non-breaking changes (e.g. `0-`) or major and minor to only get fixes (e.g. `0.200-`).*

**Linux distribution:** Debian GNU/Linux 11 (bullseye)

**Architectures:** linux/amd64, linux/arm64

**Available (non-root) user:** vscode

### Contents
**Languages and runtimes**

| Language / runtime | Version | Path |
|--------------------|---------|------|
| [.NET](https://dotnet.microsoft.com/) | 7.0.100 (7.0.0) | /usr |

**Tools installed using git**

| Tool | Commit | Path |
|------|--------|------|
| [Oh My Zsh!](https://github.com/ohmyzsh/ohmyzsh) | fe83581a20ab12010e9168977dc633c9da2924e1 | /home/vscode/.oh-my-zsh |
| [nvm](https://github.com/nvm-sh/nvm.git) | 0ccd099bff8e384043883c4ae01b589794b13d72 | /usr/local/share/nvm |

**Additional linux tools and packages**

| Tool / library | Version |
|----------------|---------|
| apt-transport-https | 2.2.4 |
| apt-utils | 2.2.4 |
| ca-certificates | 20210119 |
| curl | 7.74.0-1.3+deb11u3 |
| dialog | 1.3-20201126-1 |
| git | 1:2.30.2-1 |
| gnupg2 | 2.2.27-2+deb11u2 |
| htop | 3.0.5-7 |
| iproute2 | 5.10.0-4 |
| jq | 1.6-2.1 |
| less | 551-2 |
| libc6 | 2.31-13+deb11u5 |
| libgssapi-krb5-2 | 1.18.3-6+deb11u3 |
| libicu67 | 67.1-7 |
| libkrb5-3 | 1.18.3-6+deb11u3 |
| liblttng-ust0 | 2.12.1-1 |
| libssl1.1 | 1.1.1n-0+deb11u3 |
| libstdc++6 | 10.2.1-6 |
| locales | 2.31-13+deb11u5 |
| lsb-release | 11.1.0 |
| lsof | 4.93.2+dfsg-1.1 |
| man-db | 2.9.4-2 |
| manpages | 5.10-1 |
| manpages-dev | 5.10-1 |
| nano | 5.4-2+deb11u1 |
| ncdu | 1.15.1-1 |
| net-tools | 1.60+git20181103.0eebece-1 |
| openssh-client | 1:8.4p1-5+deb11u1 |
| procps | 2:3.3.17-5 |
| psmisc | 23.4-2 |
| rsync | 3.2.3-4+deb11u1 |
| strace | 5.10-1 |
| sudo | 1.9.5p2-3 |
| unzip | 6.0-26+deb11u1 |
| vim-tiny | 2:8.2.2434-3+deb11u1 |
| wget | 1.21-1+deb11u1 |
| yarn | 1.22.19-1 |
| zip | 3.0-12 |
| zlib1g | 1:1.2.11.dfsg-2+deb11u2 |
| zsh | 5.8-6+deb11u1 |

## Variant: 7.0-jammy

**Digest:** sha256:7be32ab9084ee744f67f8f8e508b220e406fda5679c738d3a174dbe623c102bf

**Tags:**
```
mcr.microsoft.com/devcontainers/dotnet:dev-7.0-jammy
```
> *To keep up to date, we recommend using partial version numbers. Use the major version number to get all non-breaking changes (e.g. `0-`) or major and minor to only get fixes (e.g. `0.200-`).*

**Linux distribution:** Ubuntu 22.04.1 LTS (debian-like distro)

**Architectures:** linux/amd64, linux/arm64

**Available (non-root) user:** vscode

### Contents
**Languages and runtimes**

| Language / runtime | Version | Path |
|--------------------|---------|------|
| [.NET](https://dotnet.microsoft.com/) | 7.0.100 (7.0.0) | /usr |

**Tools installed using git**

| Tool | Commit | Path |
|------|--------|------|
| [Oh My Zsh!](https://github.com/ohmyzsh/ohmyzsh) | fe83581a20ab12010e9168977dc633c9da2924e1 | /home/vscode/.oh-my-zsh |
| [nvm](https://github.com/nvm-sh/nvm.git) | 0ccd099bff8e384043883c4ae01b589794b13d72 | /usr/local/share/nvm |

**Additional linux tools and packages**

| Tool / library | Version |
|----------------|---------|
| apt-transport-https | 2.4.8 |
| apt-utils | 2.4.8 |
| ca-certificates | 20211016 |
| curl | 7.81.0-1ubuntu1.6 |
| dialog | 1.3-20211214-1 |
| git | 1:2.34.1-1ubuntu1.5 |
| gnupg2 | 2.2.27-3ubuntu2.1 |
| htop | 3.0.5-7build2 |
| iproute2 | 5.15.0-1ubuntu2 |
| jq | 1.6-2.1ubuntu3 |
| less | 590-1build1 |
| libc6 | 2.35-0ubuntu3.1 |
| libgssapi-krb5-2 | 1.19.2-2 |
| libicu70 | 70.1-2 |
| libkrb5-3 | 1.19.2-2 |
| libstdc++6 | 12.1.0-2ubuntu1~22.04 |
| locales | 2.35-0ubuntu3.1 |
| lsb-release | 11.1.0ubuntu4 |
| lsof | 4.93.2+dfsg-1.1build2 |
| man-db | 2.10.2-1 |
| manpages | 5.10-1ubuntu1 |
| manpages-dev | 5.10-1ubuntu1 |
| nano | 6.2-1 |
| ncdu | 1.15.1-1 |
| net-tools | 1.60+git20181103.0eebece-1ubuntu5 |
| openssh-client | 1:8.9p1-3 |
| procps | 2:3.3.17-6ubuntu2 |
| psmisc | 23.4-2build3 |
| rsync | 3.2.3-8ubuntu3.1 |
| strace | 5.16-0ubuntu3 |
| sudo | 1.9.9-1ubuntu2.1 |
| unzip | 6.0-26ubuntu3.1 |
| vim-tiny | 2:8.2.3995-1ubuntu2.1 |
| wget | 1.21.2-2ubuntu1 |
| yarn | 1.22.19-1 |
| zip | 3.0-12build2 |
| zlib1g | 1:1.2.11.dfsg-2ubuntu9.2 |
| zsh | 5.8.1-1 |

## Variant: 6.0-bullseye-slim

**Digest:** sha256:5657450c1521cc92eb34508f9a5df17d73023da617b47bb3c91186939dcf7ecb

**Tags:**
```
mcr.microsoft.com/devcontainers/dotnet:dev-6.0-bullseye-slim
mcr.microsoft.com/devcontainers/dotnet:dev-6.0
mcr.microsoft.com/devcontainers/dotnet:dev-6.0-bullseye
```
> *To keep up to date, we recommend using partial version numbers. Use the major version number to get all non-breaking changes (e.g. `0-`) or major and minor to only get fixes (e.g. `0.200-`).*

**Linux distribution:** Debian GNU/Linux 11 (bullseye)

**Architectures:** linux/amd64, linux/arm64

**Available (non-root) user:** vscode

### Contents
**Languages and runtimes**

| Language / runtime | Version | Path |
|--------------------|---------|------|
| [.NET](https://dotnet.microsoft.com/) | 6.0.403 (6.0.1) | /usr |

**Tools installed using git**

| Tool | Commit | Path |
|------|--------|------|
| [Oh My Zsh!](https://github.com/ohmyzsh/ohmyzsh) | fe83581a20ab12010e9168977dc633c9da2924e1 | /home/vscode/.oh-my-zsh |
| [nvm](https://github.com/nvm-sh/nvm.git) | 0ccd099bff8e384043883c4ae01b589794b13d72 | /usr/local/share/nvm |

**Additional linux tools and packages**

| Tool / library | Version |
|----------------|---------|
| apt-transport-https | 2.2.4 |
| apt-utils | 2.2.4 |
| ca-certificates | 20210119 |
| curl | 7.74.0-1.3+deb11u3 |
| dialog | 1.3-20201126-1 |
| git | 1:2.30.2-1 |
| gnupg2 | 2.2.27-2+deb11u2 |
| htop | 3.0.5-7 |
| iproute2 | 5.10.0-4 |
| jq | 1.6-2.1 |
| less | 551-2 |
| libc6 | 2.31-13+deb11u5 |
| libgssapi-krb5-2 | 1.18.3-6+deb11u3 |
| libicu67 | 67.1-7 |
| libkrb5-3 | 1.18.3-6+deb11u3 |
| liblttng-ust0 | 2.12.1-1 |
| libssl1.1 | 1.1.1n-0+deb11u3 |
| libstdc++6 | 10.2.1-6 |
| locales | 2.31-13+deb11u5 |
| lsb-release | 11.1.0 |
| lsof | 4.93.2+dfsg-1.1 |
| man-db | 2.9.4-2 |
| manpages | 5.10-1 |
| manpages-dev | 5.10-1 |
| nano | 5.4-2+deb11u1 |
| ncdu | 1.15.1-1 |
| net-tools | 1.60+git20181103.0eebece-1 |
| openssh-client | 1:8.4p1-5+deb11u1 |
| procps | 2:3.3.17-5 |
| psmisc | 23.4-2 |
| rsync | 3.2.3-4+deb11u1 |
| strace | 5.10-1 |
| sudo | 1.9.5p2-3 |
| unzip | 6.0-26+deb11u1 |
| vim-tiny | 2:8.2.2434-3+deb11u1 |
| wget | 1.21-1+deb11u1 |
| yarn | 1.22.19-1 |
| zip | 3.0-12 |
| zlib1g | 1:1.2.11.dfsg-2+deb11u2 |
| zsh | 5.8-6+deb11u1 |

## Variant: 6.0-jammy

**Digest:** sha256:8ec02c31d6e10fb25f83c79a1323a0980a10ae4bf258b88e4e96d16866a5672a

**Tags:**
```
mcr.microsoft.com/devcontainers/dotnet:dev-6.0-jammy
```
> *To keep up to date, we recommend using partial version numbers. Use the major version number to get all non-breaking changes (e.g. `0-`) or major and minor to only get fixes (e.g. `0.200-`).*

**Linux distribution:** Ubuntu 22.04.1 LTS (debian-like distro)

**Architectures:** linux/amd64, linux/arm64

**Available (non-root) user:** vscode

### Contents
**Languages and runtimes**

| Language / runtime | Version | Path |
|--------------------|---------|------|
| [.NET](https://dotnet.microsoft.com/) | 6.0.403 (6.0.1) | /usr |

**Tools installed using git**

| Tool | Commit | Path |
|------|--------|------|
| [Oh My Zsh!](https://github.com/ohmyzsh/ohmyzsh) | fe83581a20ab12010e9168977dc633c9da2924e1 | /home/vscode/.oh-my-zsh |
| [nvm](https://github.com/nvm-sh/nvm.git) | 0ccd099bff8e384043883c4ae01b589794b13d72 | /usr/local/share/nvm |

**Additional linux tools and packages**

| Tool / library | Version |
|----------------|---------|
| apt-transport-https | 2.4.8 |
| apt-utils | 2.4.8 |
| ca-certificates | 20211016 |
| curl | 7.81.0-1ubuntu1.6 |
| dialog | 1.3-20211214-1 |
| git | 1:2.34.1-1ubuntu1.5 |
| gnupg2 | 2.2.27-3ubuntu2.1 |
| htop | 3.0.5-7build2 |
| iproute2 | 5.15.0-1ubuntu2 |
| jq | 1.6-2.1ubuntu3 |
| less | 590-1build1 |
| libc6 | 2.35-0ubuntu3.1 |
| libgssapi-krb5-2 | 1.19.2-2 |
| libicu70 | 70.1-2 |
| libkrb5-3 | 1.19.2-2 |
| libstdc++6 | 12.1.0-2ubuntu1~22.04 |
| locales | 2.35-0ubuntu3.1 |
| lsb-release | 11.1.0ubuntu4 |
| lsof | 4.93.2+dfsg-1.1build2 |
| man-db | 2.10.2-1 |
| manpages | 5.10-1ubuntu1 |
| manpages-dev | 5.10-1ubuntu1 |
| nano | 6.2-1 |
| ncdu | 1.15.1-1 |
| net-tools | 1.60+git20181103.0eebece-1ubuntu5 |
| openssh-client | 1:8.9p1-3 |
| procps | 2:3.3.17-6ubuntu2 |
| psmisc | 23.4-2build3 |
| rsync | 3.2.3-8ubuntu3.1 |
| strace | 5.16-0ubuntu3 |
| sudo | 1.9.9-1ubuntu2.1 |
| unzip | 6.0-26ubuntu3.1 |
| vim-tiny | 2:8.2.3995-1ubuntu2.1 |
| wget | 1.21.2-2ubuntu1 |
| yarn | 1.22.19-1 |
| zip | 3.0-12build2 |
| zlib1g | 1:1.2.11.dfsg-2ubuntu9.2 |
| zsh | 5.8.1-1 |

## Variant: 6.0-focal

**Digest:** sha256:ef4faf02986a8109f30d572598fcfa5dcc1fd3d5d10344233a7c26cf63b08d8e

**Tags:**
```
mcr.microsoft.com/devcontainers/dotnet:dev-6.0-focal
```
> *To keep up to date, we recommend using partial version numbers. Use the major version number to get all non-breaking changes (e.g. `0-`) or major and minor to only get fixes (e.g. `0.200-`).*

**Linux distribution:** Ubuntu 20.04.5 LTS (debian-like distro)

**Architectures:** linux/amd64

**Available (non-root) user:** vscode

### Contents
**Languages and runtimes**

| Language / runtime | Version | Path |
|--------------------|---------|------|
| [.NET](https://dotnet.microsoft.com/) | 6.0.403 (6.0.1) | /usr |

**Tools installed using git**

| Tool | Commit | Path |
|------|--------|------|
| [Oh My Zsh!](https://github.com/ohmyzsh/ohmyzsh) | fe83581a20ab12010e9168977dc633c9da2924e1 | /home/vscode/.oh-my-zsh |
| [nvm](https://github.com/nvm-sh/nvm.git) | 0ccd099bff8e384043883c4ae01b589794b13d72 | /usr/local/share/nvm |

**Additional linux tools and packages**

| Tool / library | Version |
|----------------|---------|
| apt-transport-https | 2.0.9 |
| apt-utils | 2.0.9 |
| ca-certificates | 20211016~20.04.1 |
| curl | 7.68.0-1ubuntu2.14 |
| dialog | 1.3-20190808-1 |
| git | 1:2.25.1-1ubuntu3.6 |
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
| nano | 4.8-1ubuntu1 |
| ncdu | 1.14.1-1 |
| net-tools | 1.60+git20180626.aebd88e-1ubuntu1 |
| openssh-client | 1:8.2p1-4ubuntu0.5 |
| procps | 2:3.3.16-1ubuntu2.3 |
| psmisc | 23.3-1 |
| rsync | 3.1.3-8ubuntu0.4 |
| strace | 5.5-3ubuntu1 |
| sudo | 1.8.31-1ubuntu1.2 |
| unzip | 6.0-25ubuntu1.1 |
| vim-tiny | 2:8.1.2269-1ubuntu5.9 |
| wget | 1.20.3-1ubuntu2 |
| yarn | 1.22.19-1 |
| zip | 3.0-11build1 |
| zlib1g | 1:1.2.11.dfsg-2ubuntu1.5 |
| zsh | 5.8-3ubuntu1.1 |

## Variant: 3.1-bullseye

**Digest:** sha256:6fecdcf00b8367312dbbff6411cea2ef0af0675c561392a045841218bf24fb5b

**Tags:**
```
mcr.microsoft.com/devcontainers/dotnet:dev-3.1-bullseye
mcr.microsoft.com/devcontainers/dotnetcore:dev-3.1-bullseye
```
> *To keep up to date, we recommend using partial version numbers. Use the major version number to get all non-breaking changes (e.g. `0-`) or major and minor to only get fixes (e.g. `0.200-`).*

**Linux distribution:** Debian GNU/Linux 11 (bullseye)

**Architectures:** linux/amd64, linux/arm64

**Available (non-root) user:** vscode

### Contents
**Languages and runtimes**

| Language / runtime | Version | Path |
|--------------------|---------|------|
| [.NET](https://dotnet.microsoft.com/) | 3.1.425 (3.1.3) | /usr |

**Tools installed using git**

| Tool | Commit | Path |
|------|--------|------|
| [Oh My Zsh!](https://github.com/ohmyzsh/ohmyzsh) | fe83581a20ab12010e9168977dc633c9da2924e1 | /home/vscode/.oh-my-zsh |
| [nvm](https://github.com/nvm-sh/nvm.git) | 0ccd099bff8e384043883c4ae01b589794b13d72 | /usr/local/share/nvm |

**Additional linux tools and packages**

| Tool / library | Version |
|----------------|---------|
| apt-transport-https | 2.2.4 |
| apt-utils | 2.2.4 |
| ca-certificates | 20210119 |
| curl | 7.74.0-1.3+deb11u3 |
| dialog | 1.3-20201126-1 |
| git | 1:2.30.2-1 |
| gnupg2 | 2.2.27-2+deb11u2 |
| htop | 3.0.5-7 |
| iproute2 | 5.10.0-4 |
| jq | 1.6-2.1 |
| less | 551-2 |
| libc6 | 2.31-13+deb11u5 |
| libgssapi-krb5-2 | 1.18.3-6+deb11u3 |
| libicu67 | 67.1-7 |
| libkrb5-3 | 1.18.3-6+deb11u3 |
| liblttng-ust0 | 2.12.1-1 |
| libssl1.1 | 1.1.1n-0+deb11u3 |
| libstdc++6 | 10.2.1-6 |
| locales | 2.31-13+deb11u5 |
| lsb-release | 11.1.0 |
| lsof | 4.93.2+dfsg-1.1 |
| man-db | 2.9.4-2 |
| manpages | 5.10-1 |
| manpages-dev | 5.10-1 |
| nano | 5.4-2+deb11u1 |
| ncdu | 1.15.1-1 |
| net-tools | 1.60+git20181103.0eebece-1 |
| openssh-client | 1:8.4p1-5+deb11u1 |
| procps | 2:3.3.17-5 |
| psmisc | 23.4-2 |
| rsync | 3.2.3-4+deb11u1 |
| strace | 5.10-1 |
| sudo | 1.9.5p2-3 |
| unzip | 6.0-26+deb11u1 |
| vim-tiny | 2:8.2.2434-3+deb11u1 |
| wget | 1.21-1+deb11u1 |
| yarn | 1.22.19-1 |
| zip | 3.0-12 |
| zlib1g | 1:1.2.11.dfsg-2+deb11u2 |
| zsh | 5.8-6+deb11u1 |

## Variant: 3.1-focal

**Digest:** sha256:291d6529c379d9efe588315adfaa6306e01016a339c2a516f0209e6454005d83

**Tags:**
```
mcr.microsoft.com/devcontainers/dotnet:dev-3.1-focal
mcr.microsoft.com/devcontainers/dotnet:dev-3.1
mcr.microsoft.com/devcontainers/dotnetcore:dev-3.1
```
> *To keep up to date, we recommend using partial version numbers. Use the major version number to get all non-breaking changes (e.g. `0-`) or major and minor to only get fixes (e.g. `0.200-`).*

**Linux distribution:** Ubuntu 20.04.5 LTS (debian-like distro)

**Architectures:** linux/amd64

**Available (non-root) user:** vscode

### Contents
**Languages and runtimes**

| Language / runtime | Version | Path |
|--------------------|---------|------|
| [.NET](https://dotnet.microsoft.com/) | 3.1.425 (3.1.3) | /usr |

**Tools installed using git**

| Tool | Commit | Path |
|------|--------|------|
| [Oh My Zsh!](https://github.com/ohmyzsh/ohmyzsh) | fe83581a20ab12010e9168977dc633c9da2924e1 | /home/vscode/.oh-my-zsh |
| [nvm](https://github.com/nvm-sh/nvm.git) | 0ccd099bff8e384043883c4ae01b589794b13d72 | /usr/local/share/nvm |

**Additional linux tools and packages**

| Tool / library | Version |
|----------------|---------|
| apt-transport-https | 2.0.9 |
| apt-utils | 2.0.9 |
| ca-certificates | 20211016~20.04.1 |
| curl | 7.68.0-1ubuntu2.14 |
| dialog | 1.3-20190808-1 |
| git | 1:2.25.1-1ubuntu3.6 |
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
| nano | 4.8-1ubuntu1 |
| ncdu | 1.14.1-1 |
| net-tools | 1.60+git20180626.aebd88e-1ubuntu1 |
| openssh-client | 1:8.2p1-4ubuntu0.5 |
| procps | 2:3.3.16-1ubuntu2.3 |
| psmisc | 23.3-1 |
| rsync | 3.1.3-8ubuntu0.4 |
| strace | 5.5-3ubuntu1 |
| sudo | 1.8.31-1ubuntu1.2 |
| unzip | 6.0-25ubuntu1.1 |
| vim-tiny | 2:8.1.2269-1ubuntu5.9 |
| wget | 1.20.3-1ubuntu2 |
| yarn | 1.22.19-1 |
| zip | 3.0-11build1 |
| zlib1g | 1:1.2.11.dfsg-2ubuntu1.5 |
| zsh | 5.8-3ubuntu1.1 |

