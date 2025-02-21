# Create a Fairlaunch (Auto Listing)

## Overview

Important Reminder: If you want to recreate a new launchpad after canceling the old one, you must transfer tokens to a new wallet. The old wallet cannot be used to recreate the launchpad.

## Step 1: Verify Token

1. Connect Phantom wallet
2. Access the platform:
    - From homepage "Launchpads" => "Create fairlaunch" => Select "Solana"
    - Direct link: https://pinksale.finance/launchpad/create/fairlaunch
3. Input token address
4. Configure basic settings:
    - Currency: SOL
    - Fee: SOL
    - Listing: Auto

**Note:** For auto listing, token will be auto listed on DEX after finalization

## Step 2: Fair Launch Configuration

### Important Parameters

-   Use positive numbers only
-   Total selling amount: Number of tokens for fair launch
-   Softcap: Must be reasonable, not too high
-   Max contribution per user (Max buy)
-   Liquidity Settings:
    -   Percentage: 25-100% of raised funds
-   Timeline:
    -   Start time must be before end time
    -   Liquidity lockup period (e.g., 365 days)

### Additional Tool

-   Use PinkSale Calculator for tokenomics: https://docs.pinksale.finance/PinkSale-Calculator-137d7dc69b3e80fdb206f8c7002e790c

## Step 3: Finalize

1. Review all information
2. Click "Confirm & Create Launchpad"
3. Confirm in Phantom Wallet

## Troubleshooting Pool Creation

If transaction successful but no redirect:

1. Find pool address in transaction details
    - Example transaction: https://solscan.io/tx/5CA7xKQjWyVT7pCKHSsgSJmdYrPETm9GWJnQjqcPUpbSM4SJee2unspVuq9SAZSPodLuyvERjApNZpzu7WT9ymci
2. Access pool at: https://pinksale.finance/solana/launchpad/{pool-address}
    - Example: https://pinksale.finance/solana/launchpad/ARfghsEasv5K1YkgTWNoFSYkPADwPCnb2GiTRERw5pCv
3. Update the pool details to make it visible on the PinkSale platform.

## Q&A

Q: How is a Fair Launch different from a presale?
A: In a Fair Launch, the pool owner only needs to set the total number of tokens for sale and a soft cap. If the funds raised exceed the soft cap, the pool is considered successful. Unlike a presale, the token price is not fixed beforehand. Instead, the exchange rate between the native tokens (used for contributions) and the selling tokens is determined by dividing the total selling tokens by the total funds raised. For example, if a pool sells 1 million tokens and raises 100 BNB, the final rate will be 1 BNB = 10,000 tokens.
