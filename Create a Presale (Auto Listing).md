# Create a Presale on Solana (Auto Listing)

**Important:** If you want to recreate a new launchpad after canceling the old one, you must transfer your tokens to a new wallet. You cannot use the old wallet to recreate the launchpad.

## Overview
- Access via homepage: https://www.pinksale.finance
- Direct link: https://pinksale.finance/solana/launchpad/create/presale

## Step 1: Token Verification

1. Connect Phantom wallet
2. Navigate to launchpad creation:
   - From homepage: Click "Launchpads" → "Create launchpad"
   - Choose "Solana" in Chain selection
3. Input token address
4. Configure basic settings:
   - Currency: SOL
   - Fee: SOL
   - Listing: Auto (token auto-lists on DEX after finalization)

## Step 2: DeFi Launchpad Configuration

1. Set presale parameters:
   - Use positive numbers only
   - Configure presale rate (tokens per SOL)
   - Enable/disable whitelist for presale contributors
   - Set softcap (must be ≥ 25% of hardcap)
   - Choose refund options (refund or burn)

2. Configure liquidity settings:
   - Set percentage (25-100% of raised funds)
   - Set listing rate (initial DEX pool rate)
   - Note: Listing rate usually lower than presale rate for higher DEX price

3. Set timeline:
   - Configure start time (must be before end time)
   - Set end time
   - Define liquidity lockup period (e.g., 30 days)

## Step 3: Final Steps

1. Review all information carefully
2. Click "Confirm & Create Launchpad"
3. Confirm transaction in Phantom Wallet

## Troubleshooting Pool Creation

If transaction is successful but no redirect occurs:

1. Locate pool address in transaction details
   - Example: https://solscan.io/tx/5CA7xKQjWyVT7pCKHSsgSJmdYrPETm9GWJnQjqcPUpbSM4SJee2unspVuq9SAZSPodLuyvERjApNZpzu7WT9ymci

2. Access pool using format:
   - https://pinksale.finance/solana/launchpad/{pool-address}
   - Example: https://pinksale.finance/solana/launchpad/ARfghsEasv5K1YkgTWNoFSYkPADwPCnb2GiTRERw5pCv

3. Update Pool Details to appear in PinkSale system

## Additional Resources

- PinkSale Calculator for tokenomics planning: https://docs.pinksale.finance/PinkSale-Calculator-137d7dc69b3e80fdb206f8c7002e790c
