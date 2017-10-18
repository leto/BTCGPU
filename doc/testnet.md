# Bitcoin Gold Testnet

## What is a Testnet?

This software is the Bitcoin Gold node and command-line Testnet client. It provides
a safe place - off the main network - for testing of new features,
applications and ideas without compromising the security of the main network.

## How is running the Testnet different to running a Mainnet node?

In essence their is very little difference in running a Testnet to a Mainnet node
it only requires one of many possible changes in how you start the node - we will
look at just a few.

However - it is important that before you choose which method to use, you consider
if you will be ONLY running a Testnet node, or if you will be running one alongside
a Mainnet node on the same computer.

### Simplest way to run a testnet

Make sure there are no other instances of Bitcoin Gold running:
```
cd BTCGPU
./src/bitcoingold-cli stop
```
Start the Testnet:
```
./src/bitcoingoldd -testnet
```

This will give you a running node on testnet - and your node will verify testnet
transactions.
