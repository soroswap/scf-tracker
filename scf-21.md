# Soroswap's SCF#21 Submission

Check the sumbission [here](https://dashboard.communityfund.stellar.org/scfawards/scf-21/awarddistribution/suggestion/374)
Follow our Github Project [here](https://github.com/orgs/soroswap/projects/4/)

# Deliverables:

## Deliverable 1: 🔀 Optimal Routing ✅

---

### Deliverable 1.1 ✅

**Description:** Mercury Indexer Client: Implementation of a Mercury client that will subscribe to Soroswap Contracts events and track all pairs reserves.

**Reviewer Instructions:** Client code will be available in [Github](https://github.com/paltalabs/mercury-sdk)

**Result:** 
1. ✅ [mercury-sdk repo](https://github.com/paltalabs/mercury-sdk)
2. ✅ mercury-sdk docs in https://mercury-sdk.paltalabs.io/
3. ✅ [mercury-client](https://github.com/paltalabs/mercury-client)

---

### Deliverable 1.2 ✅

**Description:** Optimization algorithm: Creation and implementation of an algorithm that finds the best route for a trade It takes into account the amount to be swapped, the different paths available to go from a token A to a token B, and the reserves held on liquidity pools.

**Reviewer Instructions:** Checks [Soroswap Docs](https://docs.soroswap.finance) for algorithm description and [GitHub](https://github.com/soroswap/soroswap-router-sdk/) for implementation

**Result:** 
1. ✅ [soroswap-router-sdk](https://github.com/soroswap/soroswap-router-sdk/)
2. ✅ soroswap-router-sdk docs in https://soroswap-router-sdk.soroswap.finance/
3. ✅ [soroswap-router-sdk npm package](https://www.npmjs.com/package/soroswap-router-sdk)
4. ✅ [soroswap backend](https://github.com/soroswap/backend)
---

# Deliverable 2: 🎛 AMM Aggregator

### Deliverable 2.1

**Description:** Indexing of Comet AMM: Study of Comet pools and smart contracts. Index contracts using a Mercury Client.

**Reviewer Instructions:** Client code will be available in https://github.com/soroswap/

**Result:** Waiting for Zephyr. In progress. Follow our [project](https://github.com/orgs/soroswap/projects/4/)

---

### Deliverable 2.2

**Description:** Indexing of Phoenix AMM: Study of Phoenix pools and smart contracts. Index contracts using a Mercury Client.

**Reviewer Instructions:** Client code will be available in https://github.com/soroswap/

**Result:** Waiting for Zephyr. In progress. Follow our [project](https://github.com/orgs/soroswap/projects/4/)

---

### Deliverable 2.3

**Description:** Indexing of Stellar Classic DEX: Study and index implementation.

**Reviewer Instructions:** Client code will be available in https://github.com/soroswap/

**Result:** Waiting for Zephyr. In progress. Follow our [project](https://github.com/orgs/soroswap/projects/4/)

---

### Deliverable 2.4 ✅

**Description:** Smart Order Router.algorithm: Develop an optimal routing algorithm to efficiently find the best prices, routes and swap combining and optimizing trades across Soroswap, Comet, Phoenix and Stellar DEX.

**Reviewer Instructions:** Client code will be available in https://github.com/soroswap/

**Result:** 
1. ✅ Code available on [soroswap-router-sdk repo](https://github.com/soroswap/soroswap-router-sdk.git)

---

### Deliverable 2.5 ✅

**Description:** Documentation.

**Reviewer Instructions:** Client code will be available in https://github.com/soroswap/

**Result:** In progress. Follow our [project](https://github.com/orgs/soroswap/projects/4/)
1. ✅ [soroswap-router-sdk docs](https://soroswap-router-sdk.soroswap.finance/)
---

# Deliverable 3: 🌉 Bridges exploration and beta implementation

---

### Deliverable 3.1 ✅

**Description:** Allbridge: Study and POC. Study Allbridge documentation in order to create a standalone POC code (outside Soroswap) to bridge Stellar USD with Ethereum aeUSD.

**Reviewer Instructions:** Github repo in https://github.com/paltalabs/

**Result:** 
1. ✅ [Github repo](https://github.com/soroswap/allbridge-implementation.git)

---

### Deliverable 3.2 ✅

**Description:** Spacewalk: Study and POC. Study Pendulum’s Spacewalk documentation in order to create a standalone POC code (outside Soroswap) to bridge Stellar USD with Ethereum aeUSD.

**Reviewer Instructions:** Github repo in https://github.com/paltalabs/

**Result:** ✅ [Github repo](https://github.com/soroswap/spacewalk-implementation.git)

---

### Deliverable 3.3 ✅

**Description:** Write an Articles and a Tutorials about both explorations.Our goal is that not only Soroswap implement these bridges, but all the developers community in Soroban! Create content about existing bridges on Stellar.

**Reviewer Instructions:** Articles and Tutorials will be shared in Discord, Soroswap Docs page and dev.to

**Result:** In progress. Follow our [project](https://github.com/orgs/soroswap/projects/4/)
1. 🛠️ Allbridge Article on Discord, Soroswap Docs and dev.to
2. 🛠️ Spacewalk Article on Discord, Soroswap Docs and [dev.to](https://dev.to/soroswap/bridging-stellar-with-allbridge-core-on-soroswap-new-possibilities-unveiled-1j78)
3. ✅ [Video tutorial bridging from Polkadot to Stellar](https://www.youtube.com/watch?v=E4IR67dKxrs)

---

### Deliverable 3.4 ✅

**Description:** Choose one Bridge and implement it into the Soroswap Frontend (beta): Add a cross-chain (beta) tab in Soroswap and let user’s do cross-chain swaps with the chosen bridge. Users will need to accept terms and conditions.

**Reviewer Instructions:** Code in an specific branch of https://github.com/soroswap/frontend. Documentation and Tutorials in dev.to, Discord and Soroswap.Finance. Reviewer can go to https://soroswap.finance

**Result:** 
1. ✅ [Check it live](https://app.soroswap.finance/bridge)
2. ✅ [Github repo](https://github.com/soroswap/frontend)
---

## Deliverable 4: 📊 More information

---

### ✅ Deliverable 5.1

**Description:** Mercury Indexer Client: Implementation of a Mercury client that will subscribe to all Soroswap Contracts and track all types of activities in order to extract and calculate.

- Pool info: TVL
- Pool info: Volume 24h
- Pool info: Volume 7D
- Pool info: Current APY
- Pool info: $ Earned for each user
- Pool info: Last trades
- Asset info: Price
- Asset info: % changed
- Asset info: TVL of each asset across all Soroswap pairs
- Asset info: Volume of each asset across all Soroswap pairs

**Reviewer Instructions:** Client code will be available in https://github.com/soroswap/

**Result:** 
1. ✅ [mercury-sdk repo](https://github.com/paltalabs/mercury-sdk)
2. ✅ mercury-sdk docs in https://mercury-sdk.paltalabs.io/
4. ✅ [soroswap backend](https://github.com/soroswap/backend)

---

### Deliverable 5.2

**Description:** Pool Dashboard and Assets Dashboard Design: UX Design with external design agency in order to achieve similar Dashboards as

- https://info.uniswap.org/#/
- https://info.uniswap.org/#/pools
- https://app.uniswap.org/tokens/ethereum

**Reviewer Instructions:** Figma will be shared with the community on Discord

**Result:** 
1. ✅ [mercury-sdk repo](https://github.com/paltalabs/mercury-sdk)
2. ✅ [soroswap info frontend repo](https://github.com/soroswap/info)
