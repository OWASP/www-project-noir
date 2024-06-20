---
title: installation
displaytext: Installation
layout: null
tab: true
order: 1
tags: noir install
---

## Intallation

### Homebrew

```bash
brew install noir

# https://formulae.brew.sh/formula/noir
```

### Snapcraft

```bash
sudo snap install noir

# https://snapcraft.io/noir
```

### From Sources
```bash
# Install Crystal-lang
# https://crystal-lang.org/install/

# Clone this repo
git clone https://github.com/owasp-noir/noir
cd noir

# Install Dependencies
shards install

# Build
shards build --release --no-debug

# Copy binary
cp ./bin/noir /usr/bin/
```

### Docker (GHCR)
```bash
docker pull ghcr.io/owasp-noir/noir:main
```