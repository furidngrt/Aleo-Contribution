
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
