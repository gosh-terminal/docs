---
layout: default
---
# gosh

[![Codacy Badge](https://api.codacy.com/project/badge/Grade/51f0c37b6e3c4e559389f2e6fec985f2)](https://www.codacy.com/manual/gosh-terminal/gosh_2?utm_source=github.com&utm_medium=referral&utm_content=gosh-terminal/gosh&utm_campaign=Badge_Grade)
[![Setup Automated](https://img.shields.io/badge/setup-automated-blue?logo=gitpod)](https://gitpod.io/from-referrer/)
[![Pull Requests Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)
[![CodeFactor](https://www.codefactor.io/repository/github/gosh-terminal/gosh/badge)](https://www.codefactor.io/repository/github/gosh-terminal/gosh)
![GitHub repo size](https://img.shields.io/github/repo-size/gosh-terminal/gosh)
![GitHub language count](https://img.shields.io/github/languages/count/gosh-terminal/gosh)

Welcome to gosh! The end goal of this project is to allow you to use the
terminal for everything! Do anything from math, playing music, sending emails,
to searching the web but have these things be built into your terminal.

## Install

### Homebrew (Recommend)

```bash
brew install gosh-terminal/homebrew-gosh/gosh
```

### Gitpod

Use Gitpod, everything is preinstalled.

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/gosh-terminal/gosh)

### One-line curl installer

```bash
curl -s "https://raw.githubusercontent.com/gosh-terminal/gosh/master/tools/setup2.0.bash" | bash
source ~/.bashrc
```

### Go Module

```bash
git clone "https://github.com/gosh-terminal/gosh.git"
cd gosh
go install
echo "export GOSH_HOME=\"$GOPATH/bin\"" >>~/.bashrc
source ~/.bashrc
```

## DH Make

```bash
git clone "https://github.com/gosh-terminal/gosh.git"
cd gosh
dh_auto_install
```

![Example of gosh](https://github.com/gosh-terminal/gosh/blob/master/.github/images/example.png?raw=true)
