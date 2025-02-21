# Create a Subscription

## Overview

This guide outlines the process of creating a subscription on PinkSale, enabling projects to allocate tokens according to the amount committed by each user.

## Step-by-Step Guide

### Step 1: Initial Setup

1. Connect wallet
2. Access subscription creation:

    - From homepage: "Launchpads" => "Create Subscription"
    - Or access directly through PinkSale

3. Configure basic settings:
    - Input token address or create new token
    - Select currency: BNB
    - Select fee option
    - Optional: Enable Affiliate program

### Step 2: Subscription Configuration

#### Important Parameters

-   Use positive numbers only
-   Subscription Rate: Token amount received per subscription period
-   Minimum Subscription Amount
-   Maximum Subscription Amount
-   Subscription Period: Daily, Weekly, Monthly, or Custom
-   Total Supply Available for Subscription

#### Timeline Settings

-   Start time must be before end time
-   Subscription duration
-   Lock period for tokens (if applicable)
-   Optional: Enable Vesting Schedule

#### Vesting Configuration (Optional)

-   First release percentage
-   Vesting period
-   Vesting release frequency
-   Total vesting duration

### Step 3: Additional Information

1. Required Fields:
    - Logo URL (must end with: png, jpg, jpeg or gif)
    - Website
    - Project description
2. Optional Fields:
    - Social media links
    - Whitepaper
    - GitHub repository
    - Team information

### Step 4: Finalize

1. Review all information
2. Option to return to previous steps
3. Approve token spending
4. Confirm transaction in MetaMask
5. Pay required fees
6. Submit and wait for confirmation

## Additional Features

-   Subscription Management Dashboard
-   Analytics and Reporting
-   Subscriber List Management
-   Payment History Tracking

## Security Recommendations

-   Set appropriate subscription limits
-   Configure secure vesting schedules
-   Enable whitelist if needed
-   Consider adding security badges (KYC, Audit, etc.)

## Additional Tools

-   Pink Lock for token locking
-   PinkSale Calculator for subscription metrics

## Q&A

Q: How does a Subscription differ from a traditional presale?
A: While a Subscription pool shares similarities with a traditional presale, such as predetermined rates and listing rates, it introduces key differences that make it unique.

In a Subscription, the owner specifies the total number of tokens for sale and a soft cap, which is also represented by the selling tokens. Unlike traditional presales, there are no minimum or maximum contribution limits—users can commit any amount.

Additionally, at the end of the sale in a Subscription format, there will be a phase called the Calculation Phase, indicated by the "calculating" status on the website for that pool. During this phase, PinkSale determines whether the pool has successfully met the soft cap. If the soft cap is met, the system then calculates token allocations based on the total committed funds.

Each user has a maximum allocation cap. If a user commits an amount exceeding the tokens they are eligible to receive, the excess allocation is redistributed to other users who haven't reached their cap. In essence, the more a user commits, the higher their chance of securing the maximum allocation. Any remaining excess commitment is refunded to the user.
