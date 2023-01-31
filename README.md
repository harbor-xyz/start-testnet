# start-testnet

A project by Harbor to help the user kickstart their first Testnet. This project assumes that you have already installed the Harbor CLI. If you haven't, [run through the installation here.](https://docs.goharbor.com/docs/installation)

## Set-up

### Installation

Run `npm install` or `yarn install` depending on your package manager

### Compilation

Run `npx hardhat compile` to compile your contracts

### Starting Testnet

After you compile your contracts and install the packages, run:

```bash
harbor apply <testnet-name> --config harbor.config.json
```

You can also add whatever configuration you want.
