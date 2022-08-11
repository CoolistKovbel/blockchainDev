# Ethereum accounts: EOA VS CONTRACTS

there are 2 types of ethereum accounts
- EOA (externally owned accounts)
- contract accounts

## EOA accounts
These are ethereum accounts that are controlled by humans or coded outside the bockchain and need to have pirvate key that allows to sign transactions

## Contract Accounts
These are smart contracts they are controlled by their code, they cant initate transcasctions instead they react to transactions aqccording to the code of the smart contract

## account fields

these EOA and contract accounts are associated to these field:
- balance: balance of ehter associated to the address; both EOA and Contract accounts have access
- data: contract accounts thats the data of the smart contract; EOA is empty
- code: this is of the smart contract for contract accounts; EOA is empty
- nonce: EOA number of transactions send by the address, prevents replay attack; smart contracts nounce shoulds number of smart contracts created under that account

**smart contracts can create other smart contracts**