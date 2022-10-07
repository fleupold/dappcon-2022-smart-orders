# Smart Order

A sample CoW protocol smart order contract.

CoW protocol supports EIP-1271 signatures.
While this is typically thought of as a way for Smart Contract wallets to sign things,
we can leverage this standard for creating special order types on CoW with custom validation logic.

## Usage

1. yarn
2. export INFURA_PROJECT_ID=<...> (or configure your node URL in hardhat.json.config)
3. export PRIVATE_KEY=<...> (make sure the account is funded with at least 0.01 WETH and some ETH for gas)
4. yarn place-order
