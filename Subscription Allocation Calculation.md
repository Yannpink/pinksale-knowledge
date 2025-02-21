# Subscription Allocation Calculation

## Overview

In subscription format, users commit fund (BNB/ETH/SOL...) to a token sale. Final token allocation is determined by ratio of individual fund commitment to total fund committed by all participants.

## Basic Formula

(Individual fund / Total fund) \* Total Tokens for Sale = Initial Allocation

## Calculation Process

### Input Parameters

-   Total tokens for sale: 1,000,000 ABC
-   Your commitment: 500 BNB
-   Other users' total commitment: 2,000 BNB
-   Hard cap per user: 150,000 ABC tokens

### Step 1: Initial Allocation

1. Calculate total committed BNB = 2,500 BNB
2. Calculate your initial allocation = (500/2,500) \* 1,000,000 = 200,000 ABC
3. Note: Due to hard cap, this will be adjusted

### Step 2: Hard Cap Adjustment

1. Identify users exceeding hard cap (150,000)
2. Calculate excess allocation = 200,000 - 150,000 = 50,000 ABC per affected user
3. Redistribute total excess tokens to remaining users based on their commitment ratio

### Step 3: Final Distribution

1. Finalize allocations after hard cap adjustments
2. Distribute tokens based on adjusted allocation
3. Deduct corresponding fund amount based on token rate
4. Enable withdrawal of excessive committed fund from pool

Note: This system ensures fair distribution while maintaining individual limits through hard caps per user.
