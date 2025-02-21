# Exclude Fees, Dividends, Max TX on BSCScan

## Overview

Before finalizing your presale, if your token contract includes max transaction limits, dividend/reward systems, or tax/fee mechanisms, you must exclude these features for the presale contract address.

## Step 1: Access Contract on BSCScan

- Find your token contract address on launchpad page
- Open contract on BSCScan
- Navigate to Contract -> Write Contract section

## Step 2: Connect Wallet

- Click "Connect to Web3"
- Use owner wallet address
- Confirm connection

## Step 3: Exclude Features

- Use search (Ctrl + F) for "exclude" or "exempt"
- Input presale address in the relevant fields
- Click "Write" to submit each exclusion

## Step 4: Confirm Transactions

- Review MetaMask transaction details
- Check gas fees
- Confirm each transaction

## Important Notes

### Boolean Inputs

- If you see exclude(bool), input "true"
- Same applies for exempt(bool) fields

### Alternative Terms

- Some contracts use "exempt" instead of "exclude"
- Function names may vary but serve same purpose

### Requirements

- Must use contract owner wallet
- All exclusions must be completed before finalizing presale
- Verify each transaction's success
