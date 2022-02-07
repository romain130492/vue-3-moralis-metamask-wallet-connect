
# Vue 3 AUTH with Morallis (Metamask & Wallet Connect)


* Simple app to Authenticate with Wallet Connect & Metamask using Moralis
* The Wallet connect auth will work on **mobile** and allow your user to connect to Metamask.


Please ensure, [you signed up for an account](https://moralis.io) and created a server to obtain the

- application id
- server url


Create an `.env` file with theses 2 variables:
```
VUE_APP_MORALIS_APPLICATION_ID=abc123
VUE_APP_MORALIS_SERVER_URL=https://abc123.bigmoralis.com:2053/server
```


## Getting started
```
git clone https://github.com/romain130492/vue-3-moralis-metamask-wallet-connect

cd moralis-vue-boilerplate

yarn install

yarn serve

### production build
yarn build

### linting
yarn lint
```




I took that template from [here](https://github.com/hypescale/moralis-vue-boilerplate) and added `wallet connect` to it. In order to make it work using mobiles.