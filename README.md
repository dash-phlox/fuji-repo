# Fuji Linux repository

## Packages

* grimblast-0.1
* hyprland-guiutils-0.2.2
* hyprlauncher-0.1.6
* hyprtoolkit-0.5.4
* qview-7.1

## Installation

Add the signing key:

```sh
wget -O /etc/apk/keys/fuji-6aa27121.rsa.pub https://github.com/dash-phlox/fuji-repo/raw/refs/heads/main/fuji-6aa27121.rsa.pub
```

Add the repository:

```sh
echo "https://github.com/dash-phlox/fuji-repo/raw/refs/heads/main" >> /etc/apk/repositories
```

Update:

```sh
apk update
```
