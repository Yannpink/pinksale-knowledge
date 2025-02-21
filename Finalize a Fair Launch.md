# Finalize a Fair Launch

## Overview

This guide explains how to properly finalize a fair launch after it has met requirements and ended successfully.

## Prerequisites

-   Fair Launch must have met soft cap and ended
-   Token contract must be properly configured
-   Pool owner wallet must be used for all operations

## Step 1: Exclude Contract Functions

If your token has fees, rewards, or max transaction limits:

1. Access Token Contract:

    - Find contract on bscscan/etherscan/or any other blockchain explorer depends on the chain
    - Navigate to Contract -> Write Contract
    - Connect wallet using owner address

2. Configure Exclusions:
    - Search for "exclude" or "exempt" functions
    - Input presale address
    - Submit each exclusion transaction
    - For boolean inputs, use "true"

For detailed instructions, refer to: [Exclude Fees, Dividends, Max TX on BSCScan](https://docs.pinksale.finance/Exclude-Fees-Dividends-Max-TX-on-BSCScan-13dd7dc69b3e80eebde6c4790044b636)

## Step 2: Finalize Pool

1. Locate Pool Actions:

    - Find "Finalize" button in Pool Actions section
    - Review finalization details

2. Complete Process:
    - Click "Finalize"
    - Confirm transaction in MetaMask
    - Wait for transaction confirmation

## Important Notes

1. Contract Requirements:

    - All exclusions must be completed before finalization
    - Use contract owner wallet
    - Verify each transaction's success

2. Troubleshooting:

    - If finalization fails, check token contract configuration
    - Some token contracts use "exempt" instead of "exclude"
    - Contact trusted developer if issues persist
    - Developer list available at: https://docs.pinksale.finance/Contract-Developers-13bd7dc69b3e8094a557ce12ff42ef47

3. Post-Finalization:
    - Token will be listed automatically on previously chosen dex
    - Trading can begin immediately (except some dexes that allow setting a trading time)
    - Monitor initial transactions

## Q&A

Q: What happens to the funds that exceed the soft cap?
A: If the total raised funds exceed the soft cap, they will be treated as if they were the hard cap in a traditional presale. This means the listing allocation and the owner's share will be calculated based on the total fund raised.
