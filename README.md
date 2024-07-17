# my-dev-environment
How I set up my first development environment - this is good stuff


### Installed Homebrew in terminal

/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

- Run these two commands in your terminal to add Homebrew to your PATH:
```
    (echo; echo 'eval "$(/opt/homebrew/bin/brew shellenv)"') >> /Users/aidanboyce/.zprofile
```

```
    eval "$(/opt/homebrew/bin/brew shellenv)"
```

### Install iterm2 using homebrew

```
brew install --cask iterm2
````

### Install OMZ - Oh My Zshelll

```
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

### Install SSH for github

```
ssh-keygen -t ed25519 -C "aidanboyce213@gmail.com"
```
- Then upload the public key in my setting on github

### Some brew installs

- brew install python
- brew install python-tk
- brew install openjdk11
- brew install maven

### Install IDEs

- IntelliJ Idea
- PyCharm

