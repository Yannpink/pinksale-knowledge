# Create a Buyback Baby Token

## Overview
This guide explains how to create a buyback baby token using PinkSale and MetaMask. The process includes configuring token parameters, setting up fees, and managing the buyback function.

## Step 1: Access Token Creation
1. Go to https://www.pinksale.finance
2. Click "Launchpads" => "Create token"
3. You will be redirected to: https://www.pinksale.finance/launchpad/token/create

## Step 2: Select Token Type
1. Choose "Buyback Baby Token" in Token Type section

## Step 3: Token Configuration Requirements

### Reward Token
- Input contract address of reward token
- Example: For DOGE rewards, use Binance-Peg Dogecoin contract address

### Fee Settings
- Liquidity Fee (%): Percentage automatically sent to liquidity pool

- Buyback Fee (%): Percentage of BNB used for token buyback
  - Note: Generates contract address to store BNB
  - Note: Requires manual buyback function call

- Reflection Fee (%): Percentage distributed to token holders
  - Note: If using DOGE as reward, holders receive DOGE instead of base token

- Marketing Fee (%): Percentage of BNB sent to owner wallet

## Step 4: Create Token
1. Click "Create Token" button
2. Confirm transaction in MetaMask
3. Pay required transaction fee
4. Wait for confirmation

## Manual Buyback Function
- Function: triggerZeusBuyback(uint256 amount, bool triggerBuybackMultiplier)
- Purpose: Execute manual buyback with accumulated BNB
- Parameters:
  - amount: BNB amount for buyback
  - triggerBuybackMultiplier: If true, doubles sell tax rate for 30 minutes after buyback
