# Fair Launch Buy-Back Option

## Overview

The fair launch buyback function is an optional feature that allows project owners to use raised funds to buy back and burn tokens. This feature is exclusive to fair launches and can be configured during the creation process.

## Configuration Parameters

### 1. Buyback Percentage

-   Defines percentage of raised funds allocated for buyback
-   Combined with liquidity percentage must exceed 51%
-   Input as percentage value

### 2. Amount Per Buyback

-   Default: 1 BNB
-   Represents funds used per buyback operation
-   Tokens bought will be burned automatically

### 3. Timing Controls

1. Minimum Buyback Delay:

    - Default: 1 hour
    - Minimum wait time between buybacks
    - Only owner can initiate during this period

2. Maximum Buyback Delay:
    - Default: 6 hours
    - After this period, any user can trigger buyback
    - Resets after each buyback operation

## Post-Launch Operations

### Step 1: Initial Buyback

1. Available one hour after fair launch finalization
2. Must be initiated by project owner

### Step 2: Subsequent Buybacks

1. Can be triggered by any investor after 6 hours
2. Uses predetermined amount per buyback
3. Automatically burns purchased tokens

## Important Notes

-   Feature must be enabled during fair launch creation
-   Buyback funds are locked in contract
-   All buybacks are automated and transparent
-   Bought back tokens are permanently burned and removed from circulation
