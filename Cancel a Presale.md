# Cancel a Presale

## Overview

This guide explains how to cancel a presale and withdraw tokens from a canceled pool.

## Step 1: Cancel Presale

1. Connect your wallet
2. Visit your own presale pool
3. Click "Cancel Pool" button in the Owner Zone, then "Confirm" transaction on MetaMask

## Step 2: Withdraw Tokens from Canceled Pool

### Important Note

-   If your token has fees, rewards, and max tx in the contract, you must exclude those functions for the presale address to finalize the presale pool.

### Withdrawal Process

1. Access your token contract address from blockchain explorer (e.g bscscan, etherscan,...) or click the token address on your launchpad page

2. Navigate to:

    - Contract
    - Write contract
    - Connect to Web3 (use owner address)

3. Exclude Functions:
    - Use Ctrl + F to search for "exclude"
    - Input your presale address
    - Click "Write" to exclude fee, reward, max tx for the presale address
    - If you see exclude (bool), input "True"

### Alternative Method

-   Some contracts use "exempt" instead of "exclude". In this case:
    -   Search for "exempt"
    -   Input presale address
    -   Click "Write" to exclude fee, reward, max tx

4. Confirm Transaction:

    - Review transaction fee in MetaMask
    - Click "Confirm" to complete

5. Final Step:
    - Click "Withdraw canceled tokens" button

# Q&A

Q: When can a presale be canceled?
A: A presale can be canceled at any time as long as it hasn’t been finalized.

Q: What happens when a presale is canceled?
A: When a presale is canceled, contributors can withdraw their funds using the Withdraw Contribution function. No further contributions will be allowed, and the presale can no longer be finalized, even if it reaches the soft cap or hard cap.

Q: Why can't the selling tokens be returned in the same transaction used to cancel a presale?
A: Some tokens have custom code that applies transaction fees, which could affect the refund process. To ensure contributors can safely get their funds back, the cancellation and token retrieval are handled in separate transactions.
