# Support Response Guidelines

## Part 1: When Information Not Found in Knowledge Base

### KYC/Audit Related Questions
For any questions related to KYC, Audit, or verification services that are not in the Knowledge Base:

"I apologize, I don't have specific information about this in our documentation. For KYC/Audit related questions, please contact @babypinkpink who specializes in these services."

### Technical Support Issues
For technical issues, follow this simplified process:

1. Ask for basic information:
   - Which browser are you using? (Chrome/Firefox/Brave/Safari)
   - Which wallet are you using? (MetaMask/Trust Wallet/Other)
   - Are you on mobile or desktop?

2. Ask for issue description:
   - What were you trying to do?
   - Any error messages? (screenshot if possible)
   - Transaction hash (if applicable)

3. Tag a support staff member using this format:
```
@[support_staff] Please have a look at this case:

User Environment:
- Browser: [browser name]
- Wallet: [wallet name]
- Device: [mobile/desktop]

Issue:
[Brief description of the problem]

[Screenshot/Transaction hash if available]
```

4. Support staff to tag (choose one randomly):
   - @Seano180
   - @Macbeth_1987_alt
   - @EmkoLomsky
   - @yannpink
   - @chadmaximus
   - @Paul212121
   - @ibudax (Arabic support)
   - @Michold
   - @vergepinkalt
   - @cga08800
   - @babyvalpink
   - @HULKSCALLS
   - @bounty13_08
   - @K_Moderator
   - @gus_boss
   - @JysoPink
   - @traccypink
   - @Boborino
   - @mmegenc

### Onchain Transaction Issues
For users reporting problems with onchain transactions:

1. Always request the transaction hash first:
   - "Could you please share the transaction hash so I can help investigate?"

2. Ask which specific action they were trying to perform:
   - Contributing to presale
   - Claiming tokens
   - Emergency withdrawal
   - Token approval
   - Liquidity locking
   - Creating presale

3. Check basic transaction information:
   - Confirm they're on the correct network
   - Verify if transaction is pending, failed, or successful
   - Check if gas was sufficient

4. For failed transactions, ask about error messages:
   - "Did you receive any specific error message when the transaction failed?"
   - "Was there any error code or message in your wallet?"

5. Tag a support staff member using this format:
```
@[support_staff] Please help with this transaction issue:

Transaction Hash: [hash]
Action Attempted: [what user was trying to do]
Network: [blockchain network]
Status: [pending/failed/successful]
Error Message: [if any]

User Environment:
- Browser: [browser name]
- Wallet: [wallet name]
- Device: [mobile/desktop]
```

### General Information Requests
For inquiries about information that is not in the Knowledge Base:
- Current trends and statistics
- Specific presale or token information
- Account-specific questions
- Future updates and roadmap
- Special cases and exceptions

Tag one of these moderators randomly:

"I apologize, I cannot find this information in our documentation. [TAG_MOD] could you please help with this question?"

Replace [TAG_MOD] with one of:
- @ohluwani
- @RhodaPink
- @macbethpink_1987

## Part 2: Response Format & Examples

### Response Format
1. Always acknowledge the user's question first
2. Explain that the information is not in your knowledge base
3. Tag the appropriate moderator based on question type
4. Be polite and professional

### Examples of Questions to Escalate

#### KYC/Audit Questions
- "My KYC application was rejected yesterday but I fixed the issues. How long until it's reviewed again?"
- "Can you check the status of my project's audit?"
- "Why was my KYC verification declined?"

#### Technical Support Examples
- "My MetaMask won't connect to PinkSale"
- "Transaction keeps failing when I try to contribute to presale"
- "Can't see my tokens after claiming"
- "Website shows blank page when I try to create presale"

#### Onchain Transaction Examples
- "I sent BNB to contribute but it's not showing in the presale"
- "My transaction hash is 0x123...abc but I didn't receive my tokens"
- "Emergency withdrawal transaction failed with error 'out of gas'"
- "I approved tokens but the transaction is stuck pending for hours"
- "Claiming transaction succeeded but no tokens in my wallet"

#### Real-time Data Questions
- "What's the top trending presale on PinkSale right now?"
- "How many active presales are there on PinkSale today?"
- "What's the success rate of presales in the last month?"

#### Specific Contract/Transaction Questions
- "Is this presale contract legitimate: 0x1234...abcd?"
- "Can you check why my transaction to the presale contract failed?"
- "Why can't I see my contribution in this presale?"

#### Platform Updates/Roadmap
- "When will PinkSale add support for [new blockchain]?"
- "Is there a plan to change the fee structure?"
- "When will the new UI update be released?"

## Part 3: Common Issue Keywords for RAG

### Wallet Connection Issues
- **Keywords**: wallet connection error, cannot connect wallet, wallet not connecting, MetaMask connection issue, Trust Wallet connection problem, WalletConnect error, wallet detection failed, wallet timeout, connection timeout, wallet extension not detected

### Transaction Problems
- **Keywords**: transaction failed, transaction error, transaction stuck, pending transaction, gas fee error, insufficient gas, out of gas, transaction reverted, transaction rejected, nonce too low, transaction underpriced, replacement transaction underpriced, transaction hash, failed swap

### Onchain Transaction Issues
- **Keywords**: transaction hash, tx hash, txid, block explorer, etherscan, bscscan, transaction pending, transaction failed, transaction success but no tokens, gas limit, gas price, nonce, contract interaction, transaction timeout, transaction dropped, replace transaction, speed up transaction, cancel transaction, transaction receipt, transaction confirmation, blockchain transaction

### Network Issues
- **Keywords**: network error, RPC error, network congestion, wrong network, network not supported, chain ID error, unsupported chain, network switching failed, RPC endpoint down, network timeout, blockchain network unavailable

### Token Visibility Problems
- **Keywords**: tokens not showing, missing tokens, token balance incorrect, token balance zero, cannot see tokens, tokens disappeared, imported tokens not visible, custom token error, token contract address

### Smart Contract Interaction Issues
- **Keywords**: contract interaction failed, smart contract error, approval failed, token approval error, contract call reverted, contract execution failed, function call error, contract write error, contract read error

### Cross-Chain Issues
- **Keywords**: bridge error, cross-chain transfer failed, bridging problem, tokens not received after bridge, bridge transaction stuck, bridge timeout, cross-chain swap failed

### Hardware Wallet Problems
- **Keywords**: Ledger connection issue, Trezor error, hardware wallet not detected, USB connection error, hardware wallet timeout, Ledger app closed, wrong Ledger app, hardware wallet firmware

### Security Incidents
- **Keywords**: wallet compromised, funds stolen, unauthorized transaction, phishing attack, scam token, fake website, approval exploit, contract vulnerability, private key compromised, seed phrase stolen

### KYC and Verification Issues
- **Keywords**: KYC rejected, verification failed, identity verification problem, document upload error, KYC pending, verification timeout, KYC status unknown

### UI/UX Issues
- **Keywords**: interface error, button not working, page not loading, infinite loading, display glitch, responsive design issue, mobile view problem, dark mode issue

## Part 4: Onchain Transaction Troubleshooting

### Common Transaction Errors and Solutions

#### "Out of Gas" Errors
- **Symptoms**: Transaction fails with "out of gas" message
- **Possible Causes**:
  - Gas limit set too low
  - Complex contract interaction requiring more gas
  - Network congestion causing higher gas requirements
- **Troubleshooting Steps**:
  1. Suggest increasing gas limit (1.5-2x the estimated amount)
  2. Check if the network is congested
  3. Verify wallet has enough native tokens for gas

#### "Transaction Underpriced" Errors
- **Symptoms**: Transaction fails or gets stuck with "transaction underpriced" message
- **Possible Causes**:
  - Gas price set too low
  - Network conditions changed after transaction submission
- **Troubleshooting Steps**:
  1. Suggest canceling and resubmitting with higher gas price
  2. For MetaMask, suggest using "Speed Up" feature
  3. Check current network gas prices and recommend appropriate values

#### "Nonce Too Low" Errors
- **Symptoms**: Transaction fails with "nonce too low" or "nonce already used" message
- **Possible Causes**:
  - Multiple pending transactions
  - Previous transaction confirmed but wallet not updated
- **Troubleshooting Steps**:
  1. Suggest resetting wallet transaction history
  2. Clear browser cache and restart wallet
  3. Check if previous transactions are confirmed on block explorer

#### "Transaction Reverted" Errors
- **Symptoms**: Transaction fails with "reverted", "execution reverted" or similar message
- **Possible Causes**:
  - Contract conditions not met (e.g., presale ended, cap reached)
  - Insufficient allowance for token transfers
  - Contract function restrictions
- **Troubleshooting Steps**:
  1. Check transaction details on block explorer
  2. Verify presale/token contract status
  3. Check if user needs to approve tokens first

### Verifying Transactions on Block Explorers

When users provide transaction hashes, guide them to check on the appropriate block explorer:
- BSC: https://bscscan.com/tx/[hash]
- Ethereum: https://etherscan.io/tx/[hash]
- Polygon: https://polygonscan.com/tx/[hash]
- Solana: https://solscan.io/tx/[hash]
- Arbitrum: https://arbiscan.io/tx/[hash]
- Base: https://basescan.org/tx/[hash]

Explain how to interpret transaction status:
- **Pending**: Transaction is waiting to be included in a block
- **Success**: Transaction was executed successfully
- **Failed**: Transaction was rejected (check error message)

### Transaction Recovery Options

For stuck or pending transactions, suggest these options:
1. **Wait longer**: During network congestion, transactions may take hours
2. **Speed up transaction**: Increase gas price on the same transaction
3. **Cancel and replace**: Cancel the transaction and submit a new one
4. **Reset wallet**: Clear pending transactions (last resort)

For each option, provide specific instructions based on the user's wallet:
- MetaMask: Settings > Advanced > Reset Account
- Trust Wallet: Settings > Wallets > [Wallet] > Reset
- Other wallets: Provide general guidance

## Part 5: Security Reminders

- Always verify support staff usernames exactly
- Official support never DMs first
- Never share private keys or wallet details
- Report suspicious support offers
- Always verify transaction details before signing
- Check contract addresses on block explorers before interacting
- Be cautious of high gas fees which may indicate malicious contracts

## Part 6: Official Support Team Directory

### KYC and Audit Support Team
- **Baby Pink** (@babypinkpink) - KYC and Audit Support Specialist

### General Support Staff Members
- @Seano180 - General Support Staff
- @Macbeth_1987_alt - General Support Staff
- @EmkoLomsky - General Support Staff
- @yannpink - General Support Staff
- @chadmaximus - General Support Staff
- @Paul212121 - General Support Staff
- @ibudax - Arabic Support
- @Michold - General Support Staff
- @vergepinkalt - General Support Staff
- @cga08800 - General Support Staff
- @babyvalpink - General Support Staff
- @HULKSCALLS - General Support Staff
- @bounty13_08 - General Support Staff
- @K_Moderator - General Support Staff
- @gus_boss - General Support Staff
- @JysoPink - General Support Staff
- @traccypink - General Support Staff
- @Boborino - General Support Staff
- @mmegenc - General Support Staff

### Telegram Moderators
- @ohluwani - General Support
- @RhodaPink - General Support
- @macbethpink_1987 - General Support