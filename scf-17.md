# Soroswap's SCF#17 Submission

Check the sumbission [here](https://communityfund.stellar.org/projects/soroswap-protocol-scf-17)
Follow our Github Project [here](https://github.com/orgs/soroswap/projects/3/)

- Pending equivalent expected hous: 
- Total expected: 
- Total completed (%): 


# Deliverables:

## Deliverable 1: Router Smart Contract
___
### ✅ Deliverable 1.1
**Description:** Study and select the functionalities of the UniswapV2 Router contract to be implemented in a Soroswap Router contract, considering the limitations of Rust, Soroban, and the Token interface.

**Reviewer Instructions:** Reviewer goes to docs.soroswap.finance and reads about SoroswapRouter v/s UniswapV2Router contract

**Result:** 
1. ✅ [Check completed issue](https://github.com/soroswap/docs/issues/8)
2. ✅ [Read our article in docs.soroswap.finance](https://docs.soroswap.finance/03-technical-reference/06-soroswap-vs-uniswapv2/02-soroswaprouter-comparison)
3. ✅ [Read our article in dev.to](https://dev.to/esteblock/the-router-contract-comparison-between-soroswap-and-uniswapv2-2dmn)
4. ✅ [Post on Discord](https://discord.com/channels/897514728459468821/1151183431976374463/1151183431976374463)
___


### Deliverable 1.2
**Description:** Implement the selected functionalities and write unit and integration tests.

**Reviewer Instructions:** Reviewer clones https://github.com/soroswap/periphery and follows the instructions in order to build and test

**Result:**  In progress. Follow https://github.com/soroswap/core/issues/63
___
### ✅ Deliverable  1.3

**Description:** Write documentation for the Soroswap Router.

**Reviewer Instructions:** docs.soroswap.finance and github.com/soroswap/docs

**Result:** 
1. ✅ [Check completed issue](https://github.com/soroswap/docs/issues/9)
2. ✅ [Read our article in docs.soroswap.finance](https://docs.soroswap.finance/03-technical-reference/04-soroswaprouter)
___

# Deliverable 2: Library Smart Contract

### ✅ Deliverable 2.1

**Description:** Study and select the functionalities of the UniswapV2 Library contract to be implemented in a Soroswap Library contract, considering the limitations of Rust, Soroban, and the Token interface.

**Reviewer Instructions:** Reviewer goes to docs.soroswap.finance and reads about SoroswapLibrary v/s UniswapV2Library contract

**Result:** 

1. ✅ [Check completed issue](https://github.com/soroswap/docs/issues/10)
2. ✅ [Read our article in docs.soroswap.finance](https://docs.soroswap.finance/03-technical-reference/06-soroswap-vs-uniswapv2/03-soroswaplibrary-comparison)
3. ✅ [Read our article in dev.to](https://dev.to/esteblock/the-library-contract-comparison-between-soroswap-and-uniswapv2-46d8)
4. ✅ [Post on Discord](https://discord.com/channels/897514728459468821/1159114140774826066/1159114140774826066)
___
### ✅ Deliverable 2.2
**Description:** Implement the selected functionalities and write unit and integration tests.

**Reviewer Instructions:** Reviewer clones https://github.com/soroswap/core and follows the instructions in order to build and test

**Result:** 

1. ✅ [Check completed issue](https://github.com/soroswap/docs/issues/64)
2. ✅ [Check the code on GitHub](https://github.com/soroswap/core/tree/main/contracts/library)
3. ✅ [Check the published crate on crates.io](https://crates.io/crates/soroswap-library)
4. ✅ [Read a Tutorial about transforming smart contract into a library in dev.to](https://dev.to/esteblock/converting-a-soroban-smart-contract-into-a-crate-library-228m)


___
### ✅ Deliverable  2.3

**Description:** Write documentation for the Soroswap Library.

**Reviewer Instructions:** docs.soroswap.finance and github.com/soroswap/docs

**Result:** 

1. ✅ [Check completed issue](https://github.com/soroswap/docs/issues/11)
2. ✅ [Read our article in docs.soroswap.finance](https://docs.soroswap.finance/03-technical-reference/03-soroswaplibrary)
2. ✅ [Check the soroswap-library crate documentation in docs.io](https://docs.rs/soroswap-library/latest/soroswap_library/)
2. ✅ [Check the soroswap-library crate in in crates.io](https://crates.io/crates/soroswap-library)
___

# Deliverable 3: Partnerships and  inter-protocol integrations

___
### ✅ Deliverable 3.1

**Description:** Conduct research on potential partners, focusing on all current Soroban projects.

**Reviewer Instructions:** Blog article posted on Discord (Stellar's Soroswap Project page) and  dev.to on how do we envision partnerships with different Soroban players

**Result:** 
1. ✅ [Check completed issue](https://github.com/orgs/soroswap/projects/3?pane=issue&itemId=34075459)
2. ✅ [Check blog article in dev.to](https://dev.to/esteblock/soroswap-exploring-potential-partnerships-across-the-soroban-and-stellar-ecosystems-53k)
3. ✅ [Check blog article in Discord](https://discord.com/channels/897514728459468821/1108150952499880061/1148629408031191174)

 

___
### ✅ Deliverable 3.2

**Description:** Reach out, engage in conversations, and conduct interviews with 10 potential partners.|

**Reviewer Instructions:** We write on Discord on how it went

**Result:** 
1. ✅ [Check announcement on Discord](https://discord.com/channels/1122872696649285744/1126905509451141202/1163850876075659295)
___
### ✅ Deliverable 3.3

**Description:**  Choose 2 partners, write an article about our future integration, engage with the community on Discord and social media

**Reviewer Instructions:** Discord (Stellar's Soroswap Project page),  dev.to  and Twitter

**Result:** 
1. ✅ [check Announcement on Discord](https://discord.com/channels/897514728459468821/1108150952499880061/1167123282412187760)
2. ✅ [Check blog article in dev.to](https://dev.to/soroswap/new-partnerships-unveiled-subquery-and-mercury-2p5h)
___
### ✅ Deliverable 3.4

**Description:**  Collaborate with partner A (SubQuery) to achieve a proof-of-concept protocol integration.

**Reviewer Instructions:** Reviewer will visit github.com/soroswap and locate the repository containing the code related to our partner integration. In the event that the partner is unable to disclose their code, we will publish our code (e.g., API) for transparency and collaboration purposes.

**Result:** 
1. ✅ [Check code on github](https://github.com/paltalabs/subquery-sandbox.git)
___
### ✅ Deliverable 3.5

**Description:**  Collaborate with partner B (Mercury) to achieve a proof-of-concept protocol integration.

**Reviewer Instructions:** Reviewer will visit github.com/soroswap and locate the repository containing the code related to our partner integration. In the event that the partner is unable to disclose their code, we will publish our code (e.g., API) for transparency and collaboration purposes.

**Result:** 
1. ✅ [Check code on github](https://github.com/paltalabs/mercury-client.git)

___
### ✅ Deliverable 3.6

**Description:**  Document Integration and publish code. Create content so other ecosystem participants can interact with Soroswap

**Reviewer Instructions:** Reviewer visits docs.soroswap.finance, Discord and dev.to

**Result:** 
1. ✅ [Check blog article in dev.to](https://dev.to/devmonsterblock/collaboration-with-mercury-and-subquery-5bcg)
2. ✅ [Check blog article in Soroswap docs](https://docs.soroswap.finance/04-partners/01-mercury-subquery)
3. ✅ [Check blog article in Discord](https://discord.com/channels/897514728459468821/1108150952499880061/1168989761868927046)


## Deliverable 5: Enhance the user interface.
___
### ✅ Deliverable 5.1

**Description:** Create the first version of the UX/UI design.
Steps:
2. Collaborate to understand the requirements of the Soroswap AMM frontend.
3. Create the first version of the UX/UI design.
4. Share Figma screenshots on Discord and publish the Figma files on our GitHub repository.

**Reviewer Instructions:** Figma screenshots will be shared on Discord and Figma files will be published on our github. Reviewer will see our reports on github.com/soroswap/scf-tracker 

**Result:** 
1. ✅ Bring a Graphic, UX, and UI designer onto the team. Currently working with https://www.litcollective.io/ to bring our first version of the UX/UI design, together with a branding. 
2. ✅ Collaborate to understand the requirements of the Soroswap AMM frontend.
3. ✅ Create the first version of the UX/UI design. First version is ready! Check the next point to see the final deliverables.
4. ✅ Share Figma screenshots on Discord and publish the Figma files on our GitHub repository.

Check Screenshots: https://discord.com/channels/897514728459468821/1108150952499880061/1144588352616681584

Check the Figma [here](https://www.figma.com/file/sJ13aToLx8LnnFijBHzM73/Soroswap-Finance--WebPage---SCF-Deliverable?type=design&node-id=2040%3A3342&mode=design&t=wBw4VexObbjgHuQP-1)

___
### ✅ Deliverable 5.2

**Description:** Refine and finalize the UX/UI design.


**Reviewer Instructions:** Figma screenshots will be shared on Discord and Figma files will be published on our github. Reviewer will see our reports on github.com/soroswap/scf-tracker 

**Result:** Completed ✅

Check Screenshots: https://discord.com/channels/897514728459468821/1108150952499880061/1144588352616681584

Check the Figma [here](https://www.figma.com/file/sJ13aToLx8LnnFijBHzM73/Soroswap-Finance--WebPage---SCF-Deliverable?type=design&node-id=2040%3A3342&mode=design&t=wBw4VexObbjgHuQP-1)

___
### ✅ Deliverable 5.3


**Description:** Develop a React.js frontend, implementing the finalized design.


**Reviewer Instructions:** Reviewer will visit soroswap.finance. Frontend works similary and shows similar information that UniswapV2 interface

**Result:** 
✅ Check https://github.com/soroswap/frontend/issues
✅ Visit https://soroswap.finance
✅ See Testnet Announcement: https://dev.to/soroswap/soroswapfinance-is-live-on-soroban-testnet--5072

___
### ✅ Deliverable 5.4

**Description:** Implement all soroban interaction with the smart contracts and the @soroban-react library


**Reviewer Instructions:** Reviewer will visit soroswap.finance

**Result:** 
✅ Check https://github.com/soroswap/frontend/issues
✅ Visit https://soroswap.finance
✅ See Testnet Announcement: https://dev.to/soroswap/soroswapfinance-is-live-on-soroban-testnet--5072
