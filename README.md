# GamingMembership

Welcome to GamingMembership, a Solidity smart contract for managing gaming subscriptions on the Ethereum blockchain!

## Overview

GamingMembership is a decentralized application (DApp) that allows users to redeem gaming subscriptions using ERC20 tokens. With this contract, users can choose between three subscription levels: Bronze, Silver, and Gold. Each subscription level has its own cost in tokens, which users can redeem to gain access to corresponding benefits.

## Features

### Subscription Levels

1. **Bronze**: Entry-level subscription offering basic benefits.
2. **Silver**: Intermediate-level subscription with additional perks.
3. **Gold**: Premium-level subscription providing the most exclusive benefits.

### Token Management

- **Mint Tokens**: The contract owner can mint new tokens to distribute among users.
- **Burn Tokens**: Users can burn their tokens to reduce the supply and potentially increase the value of remaining tokens.

### Subscription Redemption

Users can redeem their tokens to subscribe to different levels based on their preferences and available token balance.

### Ownership

The contract implements the Ownable pattern, allowing secure ownership management.

## Usage

1. **Deploy the Contract**: Deploy the GamingMembership contract to the Ethereum blockchain.
2. **Mint Tokens**: The contract owner should mint tokens and distribute them among users.
3. **Redeem Subscriptions**: Users can redeem subscriptions by calling the `redeemSubscription` function with the desired subscription level.
4. **Transfer Tokens**: Users can transfer tokens to other addresses using the `transferSubscriptionTokens` function.

## Dependencies

This contract utilizes the OpenZeppelin library for ERC20 token functionality and access control.

## Contributing

Contributions to this project are welcome! Feel free to submit bug reports, feature requests, or pull requests to help improve the contract.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Author

Abhishek

abhishek7abhi7799@gmail.com
