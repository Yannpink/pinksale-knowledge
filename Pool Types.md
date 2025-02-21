# PinkSale Pool Types

PinkSale offers different types of pools for fundraising. Below is a breakdown of the available pool types:

## 1. Presale Pool

A Presale pool is a traditional fundraising pool that operates with predefined caps and exchange rates.

### Features:

-   Soft Cap: Minimum amount to be raised for the pool to be considered a success.
-   Hard Cap: Maximum amount that can be raised during the fundraising period.
-   Rate & Listing Rate: The pool exchange rate of the token and the dex listing rate are predetermined and must be provided upfront.

### Success Criteria:

-   Success is achieved if the soft cap is reached.
-   Fundraising cannot exceed the hard cap.

## 2. Fair Launch Pool

A Fair Launch pool allows for open fundraising where the final token price is determined at the end of the sale based on total funds raised.

### Features:

-   Token Allocation: The pool owner specifies the total number of tokens available for sale.
-   Soft Cap: A minimum fundraising target in the native currency that must be met for the pool to succeed.
-   Dynamic Token Rate: Unlike a Presale pool, the exchange rate is not fixed at the start. Instead, the final rate is determined at the end of the sale using the formula:
    Final Rate = Total Tokens for Sale / Total Funds Raised
-   No Hard Cap: Fundraising can exceed the soft cap, meaning there is no maximum limit on the amount that can be raised.

### Success Criteria:

-   The pool is successful if the soft cap is reached before the sale ends.
-   Investors receive tokens based on the final calculated rate.

## 3. Subscription Pool

A Subscription pool is similar to a presale pool, but with a different contribution process. Users commit an arbitrary amount of funds, and token allocation is proportional to their commitment.

### Features:

-   Soft Cap & Hard Cap: Same as the Presale pool, specifying the minimum and maximum amounts for the pool.
-   Rate & Listing Rate: Same as the Presale pool, but users commit funds instead of buying tokens directly.
-   User Commitment: Users commit funds, and the amount they can purchase is based on their contribution relative to the total commitment from all users.
-   Purchase Cap: Each user has a cap on the number of tokens they can purchase.

### Success Criteria:

-   Success is achieved if the soft cap is reached.
-   Token allocation is determined based on the proportion of each user's commitment to the total amount of funds raised.
