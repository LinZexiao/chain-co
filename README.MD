# Chain-co

This project is used to proxy multiple daemon(venus/lotus) programs. The difference from other proxy(nginx) is that chain-co can automatically select the best daemon to access.

Use [Venus Issues](https://github.com/filecoin-project/venus/issues) for reporting issues about this repository.

## Quick Start

build
```shell
make
```

start
```shell
./chain-co --auth-url <venus-auth url> --node <token>:<url>  --node <token>:<url>
```