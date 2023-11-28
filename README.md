
## Update and upgrade
```
sudo apt update && sudo apt upgrade -y
```

```
sudo apt-get install libssl-dev
```

## Install git
```
sudo apt-get install git-all -y
```

## Install curl
```
sudo apt-get install curl -y
```

## Rust installation
```
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```

Reply 1

## Source Cargo environment variables
```
source "$HOME/.cargo/env"
```

## Update and install build-essential
```
sudo apt-get update
sudo apt-get install build-essential -y
```

## Build using Cargo
```
cargo build
```

## Install libc6-dev
```
sudo apt-get install libc6-dev -y
```

## Update and install additional dependencies
```
sudo apt-get update
sudo apt-get install pkg-config libssl-dev -y
```

## Build using Cargo again
```
cargo build
```

## Clone Repo

```
git clone https://github.com/AleoHQ/leo

cd leo

cargo install --path .
```

Copy private key, from wallet, go to LEO WALLET settings, click on reveal private key and copy

`leo account import "private key"`

## Let’s initiate the example file

```
leo example tictactoe
```

```
cd tictactoe && leo run new
```

## Initialize Repo with main branch

```
git init -b main && git add .
```

```
git config --global user.email "replace-here -with -email"
```

```
git commit -m "My first commit"
```

CREATING GIT REPO:
Visit Github — https://github.com/

Create a “New Repository”

## Back to Terminal

```
git branch -m main
```

```
git remote add origin "Replace-with repo-link"
```

## Push into Repo

```
git remote -v && git push -u origin main
```

In the password field, we are gonna generate an OTP

Visit: https://github.com/settings/tokens/new

## CLAIMING BADGE 🏆
Visit the issues — — https://github.com/AleoHQ/leo/issues

Click on “Create New Issue”

DONE WAIT TO BE APPROVED


