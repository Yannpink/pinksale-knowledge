# Create a Token on Solana

## Overview
This guide explains how to create a token on Solana using PinkSale platform with Phantom wallet (Desktop).

## Step 1: Access Token Creation

1. Go to PinkSale homepage: https://pinksale.finance/
2. Navigate to: Token -> Create Token

## Step 2: Configure Token Parameters

1. Basic Requirements:
   - Decimals: Must be ≥ 9 and positive
   - Total Supply: Must be positive number

2. Authority Settings:
   
   ### Mint Authority
   - Required for creating new tokens
   - Can increase total supply later by signing transactions
   - Example: With initial supply of 10 tokens, can mint additional tokens up to max supply

   ### Freeze Authority
   - Can freeze tokens in a wallet
   - Frozen tokens cannot be moved/transferred/sold
   - Useful for creating non-transferable (soul-bound) tokens

   ### Update Authority
   - Controls smart contract upgrades on Solana
   - Can replace smart contract when needed
   - Associated with executable accounts containing program binary

## Step 3: Create Token

1. Final Steps:
   - Review all information
   - Click "Create"
   - Confirm transaction in Phantom wallet
   - Pay required transaction fee
   - Wait for confirmation
