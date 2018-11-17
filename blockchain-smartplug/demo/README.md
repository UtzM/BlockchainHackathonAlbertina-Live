# Blockchain JavaScript demo

This code allows you to preview deployed contract to the blockchain and see current energy consumption stored in this contract for a given smart plug (wallet)

## Run the code

```bash
npm install
npm run
```

## Changing the code

You will find entire JavaScript code in the `index.js` file. You can use it to check deployed contract's registered energy consumption for your smart plug. In order to do so make sure that line 3 (`index.js:3`) `key` is set to private key representing wallet of your smart plug.

If you need help creating a wallet based on a unique string (e.g. smart plug hardware ID) we recommend using a handy command line tool `correntlykeygenerator` that will generate a sequence you can use for as a wallet's private key.

```bash
npm install -g correntlykeygenerator  # this command may need administrator rights
$ corrently-keygen some-string
```