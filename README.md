# PCO Metaverse Sales Smart Contract

## Overview
The Sales Smart Contract is a key component of the PCO Metaverse, allowing users to list, bid, and transact the sales of virtual land grids. By integrating with ERC20 tokens, this contract enables a transparent and verifiable marketplace within the metaverse.

## Specifications
- **Solidity Version**: 0.8.20
- **License**: MIT
- **Dependencies**: Utilizes OpenZeppelin's IERC20 interface for ERC20 interactions.

## Features
- Grid listing for sales by users
- Bidding mechanisms for interested buyers
- Transaction processing for sales completion

The contract also cooperates with other metaverse contracts such as LandContract and ValidatorPoolContract for a holistic economic experience.

## Function Highlights
- createSales: List a grid for sale.
- addOffer: Make an offer on a grid listing.
- endSales: Conclude a grid sale.
- paymentOfRestProposedAmount: Complete payment for a winning bid.

## Functionalities
- Listing grids for sale and making bids (createSales, addOffer)
- Completing sales and managing payouts (endSales, creatorWithdraw, paymentOfRestProposedAmount)
- Accessing and providing sales offers (getSalesOffers)
- Administrative functions for tax and deadline management (updateTax, changeWinnerPaymentDeadline)

(Further functions are documented within the contract code.)
