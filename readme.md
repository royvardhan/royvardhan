### Hi there 👋, I'm Harsh Vardhan Roy
#### Blockchain Developer

- 🔭 Currently working in DeFi.
- 📫 You can reach me at [royvardhan.official@gmail.com](mailto:royvardhan.official@gmail.com) or via [Twitter](https://twitter.com/thefiatbubble).

## Work

#### [VAPORDEX: Aggregator Smart Contract | ACCESS TO $240M TVL](https://app.vapordex.io/swap)
- An Aggregator Contract that routes calls to other dexes with best quotes.
- Adapters of other dexes for compatibility and access to liquidity of other dexes.
- Integrated with Diamond Pattern, allowing for multiple facets.
- CREATE3 deployment scripts, custom ABI generation scripts.

#### [Token Factory: Token Launch Smart Contract](https://github.com/VaporFi/token-factory)
- Create a token by just filling in a form and providing the liquidity amount. Token launches, an LP pair gets created in VaporDEX.
- Features include anti-whale and anti-bot for the specified time while filling the form. Ownership of the token is auto-renounced at mint.
- Liquidity position tokens are automatically burned or locked for the specified time. Uses Sablier protocol for LP locks.

#### [Stratosphere Points Indexer: Multichain Indexer](https://github.com/VaporFi/stratosphere-points-indexer)
- Developed a points indexer from scratch that tracks all VaporFi's products like VapeStaking, LiquidMining, Dex, TokenFactory, etc., and assigns points to users for each interaction.
- Assignment of points follows specified rules and criteria provided in constants.ts of the codebase.
- Uses enums for each point source for the dynamic schema.
- Creates a Merkle root of the points map with users to update in the Rewards Controller smart contract.

#### [Rewards Controller: Stratosphere](https://github.com/VaporFi/stratosphere-contracts)
- Built a smart contract where users can claim their weekly points from the weekly Merkle root sync (done by the Indexer).
- Features a tier-based system where users earning a certain amount of points get rewarded with an updated tier.
- Implemented BitMap for saving gas with users claiming their points.

#### [Liquid Mining: $2.5M TVL All Seasons Combined](https://github.com/VaporFi/liquid-mining)
- Contributed to this ERC-2535 implementation with multiple facets such as Deposit, Withdraw, Claim, Boost, and Unlock. Each facet has a dedicated smart contract connected with the diamond.
- Authored the Claim and Withdraw contracts (facets). Set up extensive tests in Foundry, created the diamonds, connected facets to it, and achieved test coverage of over 90%.

#### [Liquid Mining Subgraph](https://thegraph.com/hosted-service/subgraph/vaporfi/liquid-mining)
- Designed to provide comprehensive data on activities within the Liquid Mining smart contract ecosystem.
- Facilitates queries to retrieve detailed information about user interactions, seasonal data, fee collections, and mining pass purchases.

#### [Genesis Staking: $312,744 TVL](https://snowtrace.io/address/0xd21fe537c97054f40890f012955a536d80d1bf00)
- Contributed to this smart contract which handled $312,744 in total value and was built for a special event where it accepted a live token (with deep liquidity pools) and emitted a new token based on TVL at the end of the staking event.
- Engaged a total of 2729 unique wallets in this event.

#### [Genesis Staking Subgraph](https://github.com/royvardhan/genesis-staking-subgraph)
- A subgraph that tracks all deposits and claims in the vault.
- Queries the liquidity pools of the deposit token and calculates the real-time USD price of the deposit token to determine the real-time price of the claim token.

#### [Emissions Manager: Auto Emits VAPE Token to Liquid Mining SC](https://snowtrace.io/address/0x9f0EDB45c2DC0f56bA7C48368c26426f366Bb788)
- A smart contract that mints new tokens automatically based on a certain set of rules.
- An admin smart contract for managing mining rewards inside Liquid Mining.

#### [Quadratic Voting ERC721](https://github.com/royvardhan/quadraticVotingERC721/blob/main/contracts/QuadraticVotingERC721.sol)
- A voting Dapp that accepts proposals for NFTs and allows NFT holders to vote.
- A vote's weight depends on the number of NFTs the voter holds.

#### [VAPORDEX](https://app.vapordex.io/swap)
- Worked on adding new features/pages to the NEXT.JS frontend.
- Integrated GraphQL APIs to fetch server-side props and show them on the frontend.
- Implemented Vercel edge configs to limit features to users before the release date.
- Integrated smart contracts with pages.

