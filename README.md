Recreating ~$42k profit arbitrage transaction: etherscan tx link
📃 Instructions to run
Install dependencies in project directory(working with node v14.16.1)
npm i
Install ganache-cli (globaly)
npm i -g ganache-cli
In 1st terminal window fork mainnet on 10633644 block
ganache-cli -p 7545 -f <https://YOUR_ETH_PROVIDER>@10633644
In 2nd terminal window migrate Arb contract
truffle migrate --reset
Execute script
truffle exec scripts/arb.js
!Note: To reset data, restart ganache-cli after each test.
