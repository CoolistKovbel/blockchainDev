# Ethereum networks: local public testnets and mainnet

etheruem can run on several networks
- same address can be re-used on several networks
- the balance of ether is compeletely independent from other networks
- you can transfer ether between differeent networks


**Each network has a different purpose**

## Ethereum clients

- geth, the go implementation, popular
- parity, the rust implementation, focused on enterprises needs - now called open ethereum
- hyperledger besu, java implementation, focus on enterprises needs

## Mainnet

This is the production network where we use real ether when communicating with our smart contract

## public testnet

This is like a sandbox for your smart contract where you can safely test your smart contracts, in order to test you will need some fake ether .

- ropsten
- kovan
- rinkeby

some testnets use the same Proof-Of-Work algorithm others use the Proof-Of-Authority, you cant run your own testnet node.

Rinkeby is recommended to use for testing done frequently and ropsten is good for onece it while its much slower than rinkeby.

## private networks 

private netowrks are mainly used for consortium of big companies like in the supply chain industry or banking and you would use the **Hyperledger Besu** client to allow you to setup a network for this.

## local networks 

local networks are usef for local development that starts you of with a fresh ethereum blockcahin every time you resume your work, using **ganache** will make it easier to get your fake ether to use on your local blockchain in order to test your smart contract.
