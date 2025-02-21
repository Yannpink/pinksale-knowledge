# Finalize a Subscription

## Overview

This guide explains how to finalize your subscription pool after meeting the required conditions.

## Prerequisites

-   Your Subscription Pool must have met its soft cap after all calculations have been done by PinkSale admins
-   Pool status must be "Success"
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
    - Confirm transaction in MetaMask or a wallet of your choice
    - Wait for transaction confirmation

## Q&A

Q: The pool has ended, but I can't finalize it. Why?
A: When a subscription pool ends, PinkSale needs to perform calculations to determine the total raised funds and allocate contributions accordingly. This process usually takes only a few minutes. If it's taking too long, contact PinkSale administrators for assistance.

Q: What happens if PinkSale completes the calculations, but the owner doesn’t list it immediately?
A: Once the calculations are finished, the next steps depend on the fundraising result:

-   If the pool is successful (exceeds the soft cap), contributors can withdraw any excess funds based on their allocation.
-   If the pool fails (does not reach the soft cap), contributors can withdraw their full contribution amount.

Q: When can I withdraw my excess commitment funds?
A: Once PinkSale completes the calculations, if the pool meets its soft cap, you can withdraw your excess commitment immediately. Alternatively, you can wait for the owner to list the token and then withdraw the excess funds along with claiming your tokens in a single transaction. If the pool fails to reach the soft cap, you will be able to withdraw your entire committed amount.
