# Create a Presale Using Stablecoin

## Overview

This guide explains how to create a presale using stablecoins (BUSD, USDT, USDC) on supported blockchains:

-   BSC
-   ETH
-   Matic
-   Avax
-   Cronos Chain
-   Solana
-   TON
-   SUI

The example below demonstrates using BUSD on BSC chain.

## Step 1: Verify Token

1. Connect wallet
2. Access: https://www.pinksale.finance/#/launchpad/create
3. Input token address or create new token
4. Select stablecoin (e.g., USDT)
5. Select fee option
6. Approve token spending

### Important Notes

-   Stablecoin pair works ONLY with standard tokens
-   Does NOT support taxed tokens (Liquidity Generator, BabyToken, Buyback Baby Token)
-   Contact PinkSale for more information

## Step 2: DeFi Launchpad Configuration

### Key Parameters

-   Use positive numbers only
-   Presale Rate: Token amount received during presale
-   Whitelist: Optional, can enable/disable anytime
-   Soft Cap: Must be ≥ 50% of Hard Cap
-   Unsold Tokens: Choose Burn or Refund

### PancakeSwap Settings

-   Liquidity Percentage: 51-100% of raised funds
-   Listing Rate: Initial pool rate (1 BUSD = x tokens)
-   Note: Usually lower than presale rate for higher listing price

### Timeline Settings

-   Start time must be before end time
-   Liquidity lockup period (e.g., 365 days)
-   Optional: Enable Vesting Contributor (see: https://docs.pinksale.finance/Presale-Vesting-Guide-13bd7dc69b3e80e097aed8dc43e8384a)

## Step 3: Additional Information

### Required Fields

1. Logo URL
    - Must end with: png, jpg, jpeg or gif
2. Website
3. Social media links
4. Project description

## Step 4: Finalize

1. Review all information
2. Option to return to previous steps
3. Submit and confirm transaction
4. Pay required fees

## Special Considerations

For tokens with burns, rebase or special transfers:

-   Ensure you can whitelist multiple addresses
-   OR turn off special transfer events (e.g., set fees to 0) during presale
