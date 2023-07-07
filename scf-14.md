# Soroswap's SCF#14 Submission

Check the sumbission [here](https://communityfund.stellar.org/projects/soroswap-protocol-scf-14)

- Pending equivalent expected hous: 70 (1,7 weeks)
- Total expected: 480
- Total completed (%): 85,4%


# Deliverables:

## Deliverable 1: Beta version of contracts
___
### Deliverable 1.1
**Description:** Split  liquidity_pool contract into 1) Factory and 2) Pair contract. Write unit and integration testing

**Reviewer Instructions:** Reviewer clones https://github.com/soroswap/core and follows the instructions to run unit and integration tests. Check docs issue #1

**Result:** Competed ✅. Now we have a Factory and a Pair contract. Check the core repo.
___


### Deliverable 1.2
**Description:** Write bash scripts in order to experiment with these contracts from the command-line interface and write a tutorial about this

**Reviewer Instructions:** Reviewer visits https://github.com/soroswap/docs or docs.soroswap.finance where there will be an article about this tutorial. The tutorial will also be published in https://dev.to/ and will be shared with the community in the Stellar Developers Discord.


**Result:** Competed ✅. Check https://docs.soroswap.finance/03-interact-with-contracts  and the Soroswap.Finance Introduction Series https://dev.to/esteblock/series/22986 
___

## Deliverable 2: Choose and implement new UniswapV2 functionalities
___
### Deliverable  2.1

**Description:** Study and choose functionalities of UniswapV2 to be added to the contracts. Take decisions depending on Rust, Soroban, and Token interface limits. Write the Soroswap litepaper, based on the Uniswap whitepaper and the design decisions made.

**Reviewer Instructions:** Reviewer visits https://github.com/soroswap/docs or docs.soroswap.finance to read the article about the decisions made. Finds the Litepaper. 

**Result:** Competed ✅. Check https://docs.soroswap.finance/01-concepts/02-design-decisions and https://docs.soroswap.finance/02-soroswap-litepaper

___
### Deliverable 2.2

**Description:** Implement new chosen functionalities, write unit and integration testing. 

**Reviewer Instructions:** Reviewer goes to https://github.com/soroswap/core and sees the new functionalities have been implemented correctly.  Clones the repo and test. Check core issue #4

**Result:** Competed ✅. Check the core repo.
___

# Deliverable 4: Support for @soroban-react, a multichain library with documentation and tutorials

___
### Deliverable 4.1

**Description:** Update to Preview 8, support multichain dApps, make an multichain example dapp and write a tutorial about it

**Reviewer Instructions:** Verifier clones https://github.com/esteblock/soroban-react and sees that the library has been updated to Preview 8 and that supports multichain dApps. The multichain example dapp will be published in https://soroban-react.gitbook.io.

**Result:** Competed ✅. Currently supporting Preview 9. Multichain support is Ok. Check the multichain dapp here: https://github.com/esteblock/multichain-dapp. Featured as a Key Feature in the library's document page: https://soroban-react.gitbook.io/index/


___
### Deliverable 4.2

**Description:** Write documentation for soroban-react library

**Reviewer Instructions:** Check https://soroban-react.gitbook.io

**Result:** Competed ✅. Check https://soroban-react.gitbook.io


___
### Deliverable 

**Description:** 

**Reviewer Instructions:** 

**Result:** Competed ✅. 


## Deliverable 5: Prepare front-end for only 1 Pair of tokens
___
### Deliverable 5.1

**Description:** Create an MVP front.end in order to implement @soroban-reac library to connect wallet and show user address and balance of tokens

**Reviewer Instructions:** Reviewer clones https://github.com/soroswap/frontend and follows the instructions to deploy contracts and front-end locally. Relevant sections are identified and unused code is removed from the front-end. Wallet is connected, user address and user balance of both tokens is displayed for 1 pair. Check interface issue #1

**Result:**
- ✅ Repository available at https://github.com/soroswap/frontend. 
- ❓ (pending) Also in https://soroswap.finance (pending). 
- ❓ (pending) Documentation on how to deploy contracts in frontend repo is pending. See https://github.com/soroswap/frontend/issues/31
- ✅ Wallet is connected. Currently supporting Freighter.
- ✅ User balance of tokens is displayed for all tokens and paris

Pending hours (aprox): 10

___
### Deliverable 5.2

**Description:** Fetch best price. Give expected amount, price impact, minimum received after slippage. Add liquidity: Only 1 pair is available: show user balance, calculate amount to input, number of LP tokens and share of pool (%)


**Reviewer Instructions:** Reviewer clones the project and checks.

**Result:** 
- ❓ (pending) Fetch best price. Check https://github.com/soroswap/frontend/issues/33
- ❓ (pending) Give expected amount. Check https://github.com/soroswap/frontend/issues/15
- ❓ (pending) Calculate splippae. Check https://github.com/soroswap/frontend/issues/34
- ❓ (pending) Give minimum received after splippage. Check https://github.com/soroswap/frontend/issues/34
- ✅ Provide liquidity: Several pairs are available
- ✅ Provide liquidity: Show user balance
- ✅ Provide liquidity: Calculate optimal amount of token B of input. Check. https://github.com/soroswap/frontend/issues/9
-❓ (pending) Provide liquidity: Give number of LP tokens to receive. https://github.com/soroswap/frontend/issues/12
- ❓ (pending) Provide liquidity: Give share of pool (%) to receive. https://github.com/soroswap/frontend/issues/12


Pending hours: 40

## D6: Deployment of soroswap.finance in Production (Futurenet)
___
### Deliverable 6.1

**Description:** Write an script to deploy the Factory Contract and 4 Pairs contracts; run the script. Add a tab to mint tokens. Deploy in soroswap.finance

**Reviewer Instructions:** Script in https://github.com/soroswap/core, contract addresses in docs.soroswap.finance. Front-end in soroswap.finance

**Result:** ❓ (pending). Check https://github.com/soroswap/core/issues/45

Pending hours: 15
___
### Deliverable 6.2

**Description:** Keep the front-end updated to the latest @soroban-react library and soroban-client SDK

**Reviewer Instructions:** https://github.com/soroswap/frontend

**Result:** ✅ Completed. Currently supporting @soroban-react version 5.3.12 & soroban-client version 8.0.1

___
## Deliverable 7: 

**Description:** Support @soroban-react library: Upgrade it to the latest Soroban SDK and add testing using the Jest testing framework

**Reviewer Instructions:** Check https://github.com/esteblock/soroban-react/issues/10

**Result:** ❓ (pending). Check  https://github.com/esteblock/soroban-react/issues/10

Pending hours: 5
