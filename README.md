# Module 21 Challenge - Martian Token Crowdsale
<img src="Images/application-image.png" alt="drawing" width="800"/>

## Overview
For this project I will assume the role of fintech professional developing a monetary system for a new Mars colony. The goal of the challenge is to develop a new cryptocurrency on blockchain technology named **KaseiCoin**. The currency will be a fungible token that is ERC-20 compliant and will be made available through crowdsale for the people moving to Mars to convert their earthly money to the new Martian KaseiCoin ("KAI").


## Technologies
The coin, crowdsale, and deployment contracts will be developed in the Solidity language using the Remix IDE for Ethereum and the OpenZeppelin framework and library. The transactional accounts will be tested using Ganache and the MetaMask wallet. 

* [Solidity](https://soliditylang.org/): programming language designed for developing smart contracts that run on Ethereum
* [Remix](https://remix.ethereum.org/): a native IDE for Web3 Development and deployment of smart contracts
* [Ganache](https://archive.trufflesuite.com/ganache/): a personal Ethereum blockchain which you can use to run tests, execute commands, and inspect state while controlling how the chain operates
* [MetaMask](https://metamask.io/): a popular cryptocurrency wallet and gateway to blockchain applications
* [OpenZeppelin](https://www.openzeppelin.com/): an open-source framework and library for building secure smart contracts on the Ethereum blockchain

## Application Results
Below are screenshots of the key moments in the compiling, deploying, and use of the crowdsale application to convert the existing currency to KaseiCoin ("KAI").

### MetaMask wallet with `Account 2` and `Account 3` from Ganache
<img src="Evaluation_Evidence/1_MetaMask_initial.png" alt="drawing" width="200"/>

### Ganache accounts linked to MetaMask
<img src="Evaluation_Evidence/2_Ganache_Accounts linked_to_MetaMask.png" alt="drawing" width="700"/>

### `KaseiCoin.sol` compiled without errors
<img src="Evaluation_Evidence/3_KaseiCoin_Compilied.png" alt="drawing" width="700"/>

### `KaseiCoinCrowdsale.sol` compliled without errors
<img src="Evaluation_Evidence/4_KaseiCoinCrowdsale_Compiled.png" alt="drawing" width="700"/>

### KaseiCoinCrowdsaleDeployer with Ganache Account 1
<img src="Evaluation_Evidence/5_KaseiCoinCrowdsaleDeployer_w_Ganache_Acct_1.png" alt="drawing" width="200"/>
<img src="Evaluation_Evidence/8_contract_deployed_verified.png" alt="drawing" width="200"/>
<img src="Evaluation_Evidence/10_KaseiCoinCrowdsale_deployed.png" alt="drawing" width="200"/>


<table>
  <tr>
    <td>
      <img src="Evaluation_Evidence/5_KaseiCoinCrowdsaleDeployer_w_Ganache_Acct_1.png" alt="KaseiCoinCrowdsaleDeployer with Ganache Account 1" width="200"/>
    </td>
    <td>
      <img src="Evaluation_Evidence/8_contract_deployed_verified.png" alt="Contract Deployed and Verified" width="200"/>
    </td>
    <td>
      <img src="Evaluation_Evidence/10_KaseiCoinCrowdsale_deployed.png" alt="KaseiCoinCrowdsale Deployed" width="200"/>
    </td>
  </tr>
</table>


### Buying Tokens for MetaMask `Account 3`
<img src="Evaluation_Evidence/11_buying_tokens_for_acct3.png" alt="drawing" width="200"/>
<img src="Evaluation_Evidence/12_MetaMask_after_transact.png" alt="drawing" width="200"/>
<img src="Evaluation_Evidence/15_KAI_showing_MetaMask_acct3.png" alt="drawing" width="200"/>

### Buying Tokens for MetaMask `Account 2`
<img src="Evaluation_Evidence/18_KAI_showing_MetaMask_acct2.png" alt="drawing" width="200"/>

### Ganache post-transaction blocks
<img src="Evaluation_Evidence/19_ganache_post_transaction_blocks.png" alt="drawing" width="700"/>

### Ganache transactions
<img src="Evaluation_Evidence/20_ganache_transactions.png" alt="drawing" width="700"/>

## Sources
The following sources were consulted in the completion of this project. 

* UCB FinTech Bootcamp instructor-led coding exercises

## License
[MIT License](LICENSE)