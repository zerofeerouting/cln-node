# docker-compose based CLN lightning node setup

> Comments? Suggestions? Feel free to open an issue in [GitHub](https://github.com/zerofeerouting/cln-node/issues). 

## Prerequisites

You should have a VPS (or local machine) that the node should run on. 

You also should have a bitcoind node running that has an rpcuser and an rpcpassword configured 
(cln will connect to this) bitcoind.

## How to get it working

1. Clone this repository. 
2. Create an `.env` file (for example by coping end completing the information from `.env.example` in this repository).
3. Run `docker-compose up --build -d`

That's it.

## When running

### Executing commands

You can use all `lightning-cli` commands by executing `./lightning-cli.sh` and adding whatever command you like - 
for example:

```
./lightning-cli getinfo
```

### Seeing the logs

You can see the logs by executing

```
docker container logs cln -f
```

Exit with `ctrl-c`.

