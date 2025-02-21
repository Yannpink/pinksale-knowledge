# Create a 2022 Token

## Overview
This guide explains how to create a token on Solana with PinkSale using Phantom wallet (Desktop).

## Step-by-Step Guide

### Step 1: Access Token Creation
1. Go to https://pinksale.finance
2. Click "Token" => "Create Token"

### Step 2: Token Configuration Requirements
- Decimals: Must be positive and >= 9
- Total Supply: Must be positive number

### Step 3: Transfer Fee Settings
1. Enable Transfer Fee Config option
2. Configure Transfer Fee Percent (in basis points)
   - Example: 50 basis points on 1,000 tokens = 5 tokens fee
3. Set Max Transfer Fee
   - Example: 5,000 tokens max fee even on 10,000,000,000,000 transfer

### Step 4: Authority Settings
1. Mint Authority
   - Required for creating new tokens
   - Can increase total supply up to max supply
   - Must sign new token minting transactions

2. Freeze Authority
   - Controls token transfer ability
   - Can freeze tokens in specific wallets
   - Useful for non-transferable/soul-bound tokens

3. Update Authority
   - Smart contract control
   - Can update smart contract program
   - Has full upgrade authority rights

### Step 5: Token Creation
1. Click "Create" button
2. Confirm transaction in Phantom wallet
3. Pay required transaction fee
4. Wait for confirmation

## References
Documentation: https://spl.solana.com/token-2022/extensions#transfer-fees
