# White Hat CTF Tools Collection


## Getting Started

### Prerequisites

```
git init
git remote add origin git@github.com:WhiteHatCP/ctf-tools.git
git pull origin master
git submodule update --init --recursive
```

### Installing Common Tools:

If running on a Unix environment:

```
./aptInstall.sh
```

If running on macOS with [Homebrew](https://brew.sh "Install Homebrew") installed:

```
./brewInstall.sh
```

### Adding a New CTF Tool:

```
git submodule add git@github.com:[REPO_URL]
```
