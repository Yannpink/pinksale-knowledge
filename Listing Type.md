# Listing Types in PinkSale

PinkSale offers two types of listing pools for token launches: **Manual Listing Pool** and **Auto Listing Pool**. Each type handles the allocation of raised funds differently.

## 1. Manual Listing Pool

In a **Manual Listing Pool**, the owner is responsible for adding liquidity to a decentralized exchange (DEX) after the presale ends.

### **Process:**

-   The **service fee** is deducted and sent to PinkSale.
-   The **remaining funds**, including liquidity funds and the owner's share, are returned to the pool owner.
-   The owner must manually add liquidity to the DEX and handle the listing process.

### **Use Cases:**

-   If the token is **already listed on a DEX**, manual listing allows the owner to manage liquidity without conflicts between the existing exchange rate and the presale listing rate.
-   If the owner wants **full control over liquidity and timing**, manual listing allows flexibility in deciding how and when to list the token.

### Example Calculation:

Assume:

-   **Service fee** = 5% of funds raised
-   **Funds raised** = 100 BNB
-   **Liquidity percentage** = 60%

#### Step-by-step Calculation:

1. **Service Fee Deduction:**
    - 100 \* 5% = **5 BNB** (Sent to PinkSale)
    - Remaining: **100 - 5 = 95 BNB**
2. **Total Funds Received by Owner:**
    - Since the owner manages liquidity manually, they receive both the allocated funds and the liquidity funds.
    - Total received: **95 BNB**

## 2. Auto Listing Pool

In an **Auto Listing Pool**, PinkSale automatically lists the token on the selected DEX after the presale ends.

### **Process:**

-   The **service fee** is deducted and sent to PinkSale.
-   The **owner receives only their allocated share** of the funds raised.
-   The **liquidity funds** are automatically used to list the tokens on the DEX at the predetermined listing rate.

### **Use Cases:**

-   If the token is **not yet listed on a DEX**, auto listing ensures the token is launched at the exact rate set in the presale.
-   If the owner prefers a **fully automated process**, auto listing simplifies liquidity handling without requiring manual intervention.
-   **Auto listing can increase investor trust**, as it guarantees that liquidity will be added automatically, preventing potential risks of mismanagement or delayed listing.

### Example Calculation:

Using the same assumptions:

-   **Service fee** = 5% of funds raised
-   **Funds raised** = 100 BNB
-   **Liquidity percentage** = 60%

#### Step-by-step Calculation:

1. **Service Fee Deduction:**
    - 100 \* 5% = **5 BNB** (Sent to PinkSale)
    - Remaining: **100 - 5 = 95 BNB**
2. **Liquidity Allocation:**
    - 95 \* 60% = **57 BNB** (Used for bootstrapping liquidity)
    - Remaining for the owner: **95 - 57 = 38 BNB**
3. **Total Funds Received by Owner:**
    - The owner receives **38 BNB**.
    - The **57 BNB is paired with tokens** (based on the set rate) and used to bootstrap liquidity on the chosen DEX.

## Summary

| Listing Type       | Owner Receives | Liquidity Funds      | Service Fee |
| ------------------ | -------------- | -------------------- | ----------- |
| **Manual Listing** | 95 BNB         | Managed by owner     | 5 BNB       |
| **Auto Listing**   | 38 BNB         | 57 BNB (Auto-listed) | 5 BNB       |

In summary, **Manual Listing Pools** give the owner full control over liquidity management, while **Auto Listing Pools** automate the liquidity process, ensuring tokens are instantly tradable on the selected DEX.

## Q&A

Q: What is the main difference between a Manual Listing Pool and an Auto Listing Pool?
A: The key difference is how liquidity is handled. In a Manual Listing Pool, the owner receives all remaining funds, including the liquidity portion, and must manually add liquidity to a decentralized exchange (DEX). In an Auto Listing Pool, the liquidity funds are automatically used to list the tokens on the selected DEX, and the owner only receives their share of the raised funds.

Q: How much of the raised funds will the owner receive in a Manual Listing Pool?
A: The owner will receive all remaining funds after the service fee is deducted. This includes both the allocated owner’s share and the liquidity funds.

Q: How much of the raised funds will the owner receive in an Auto Listing Pool?
A: In an Auto Listing Pool, the liquidity funds are automatically used to list the tokens on the DEX. The owner will only receive their allocated share after deducting the service fee and liquidity funds.

Q: Why does the owner receive more funds in a Manual Listing Pool compared to an Auto Listing Pool?
A: In a Manual Listing Pool, the owner is responsible for adding liquidity, so they receive both their allocated share and the liquidity funds, which they must manually manage. In an Auto Listing Pool, the liquidity is automatically set up, so the owner only receives their share after the liquidity funds are deducted.

Q: What happens to the liquidity funds in an Auto Listing Pool?
A: The liquidity funds are automatically paired with tokens (based on the set rate) and used to bootstrap liquidity on the chosen DEX, making the tokens tradable immediately after finalization.

Q: Which listing type suits my project the best?
A: Choosing the right listing type depends on the project’s needs. If the token is already listed, manual listing may be a better option to avoid conflicts with existing prices. However, for new tokens, auto listing provides a more secure and transparent launch process for investors.
