# Create a Baby Token

## Overview
This guide explains how to create a baby token using PinkSale and MetaMask Wallet (Desktop). A baby token is a special type of token that rewards holders with another cryptocurrency.

Tutorial Video: https://www.youtube.com/watch?v=yMBa2lYnX54

## Step-by-Step Guide

### Step 1: Access Token Creation
1. Go to https://www.pinksale.finance
2. Click "Launchpads" => "Create Token"
3. You will be redirected to: https://www.pinksale.finance/launchpad/token/create

### Step 2: Select Token Type
1. Choose "Baby Token" in Token Type section

### Step 3: Token Configuration Requirements

#### Reward Token
- Input contract address of reward token
- Example: For DOGE rewards, use 0xba2ae424d960c26247dd6c32edc70b295c744c43 (Binance-Peg Dogecoin)

#### Minimum Token Balance
- Set minimum tokens required for dividend eligibility
- Must be worth more than $50

#### Fee Settings
- Token Reward Fee (%): Percentage distributed to holders
  - Note: Auto-swaps to reward token when > 0.002% of total supply
- Auto Add Liquidity (%): Percentage sent to liquidity pool
- Marketing Fee (%): Percentage sent to marketing wallet
  - Note: If using DOGE rewards, marketing wallet receives DOGE

#### Marketing Wallet
- Input wallet address to receive marketing fees

### Step 4: Create Token
1. Click "Create Token" button
2. Confirm transaction in MetaMask
3. Pay required transaction fee
4. Wait for confirmation
