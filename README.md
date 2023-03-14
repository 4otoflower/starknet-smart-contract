# starknet-smart-contract
all you need to publish a smart contract on starknet

## Starknet

```
curl -L https://raw.githubusercontent.com/software-mansion/protostar/master/install.sh |
bash

source /root/.bashrc

protostar init

cd <project-folder>

protostar build

echo "pr-key" > .env

protostar declare ./build/main.json --account-address <wallet> --max-fee auto --private-key-path ./.env --network mainnet

protostar deploy <class hash> --account-address <wallet> --max-fee auto --private-key-path ./.env --network mainnet
```
