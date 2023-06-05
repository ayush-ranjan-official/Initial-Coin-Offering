# Initial-Coin-Offering

https://initial-coin-offering-flame-ten.vercel.app/

NOTE: In NFT collection dAPP, we didn't performed any function from `Whitelist.sol` in the `index.js` file, hence we don't need the ABI and Address of Whitelist.sol in constants. And for the Interface used in CryptoDevs.sol, we directly take the `WHITELIST_CONTRACT_ADDRESS` using a constructor, while deploying in `hardhat-folder/scripts/deploy.js`. But here in ICO, we need to call the `balanceOf` from the NFT contract to get the number of NFT's held by the user in `index.js`. Hence we need to add its ABI and address in constants.
