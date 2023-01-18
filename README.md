## Build a DAO for your NFT holders

## Requirements

-   Anyone with a  `CryptoDevs`  NFT can create a proposal to purchase a different NFT from an NFT marketplace
-   Everyone with a  `CryptoDevs`  NFT can vote for or against the active proposals
-   Each NFT counts as one vote for each proposal
-   Voter cannot vote multiple times on the same proposal with the same NFT
-   If majority of the voters vote for the proposal by the deadline, the NFT purchase is automatically executed

## What we will make

-   To be able to purchase NFTs automatically when a proposal is passed, you need an on-chain NFT marketplace that you can call a  `purchase()`  function on. There exist a lot of NFT marketplaces out there, but to avoid overcomplicating things, we will create a simplified fake NFT marketplace for this tutorial as the focus is on the DAO.
-   We will also make the actual DAO smart contract using Hardhat.
-   We will make the website using Next.js to allow users to create and vote on proposals

## Building our DAO

You want to launch a DAO for holders of your  `CryptoDevs`  NFTs. From the ETH that was gained through the ICO, you built up a DAO Treasury. The DAO now has a lot of ETH, but currently does nothing with it.

You want to allow your NFT holders to create and vote on proposals to use that ETH for purchasing other NFTs from an NFT marketplace, and speculate on price. Maybe in the future when you sell the NFT back, you split the profits among all members of the DAO.
