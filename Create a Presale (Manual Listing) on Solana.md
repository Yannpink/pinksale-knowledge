# Create a Presale on Solana (Manual Listing)

Important Reminder: If you want to recreate a new launchpad after canceling the old one, you must transfer tokens to a new wallet. The old wallet cannot be used to recreate the launchpad.

1. Verify Token

    - Connect Phantom wallet
    - Access: From homepage "Launchpads" => "Create launchpad" => Select "Solana"
    - Direct link: https://pinksale.finance/solana/launchpad/create/presale
    - Input token address
    - Settings:
        - Currency: SOL
        - Fee: SOL
        - Listing: Manual

    Note: For manual listing:

    - PinkSale won't charge tokens for liquidity
    - You can withdraw SOL after pool ends
    - You must do DEX listing yourself

2. DeFi Launchpad Configuration
   Important Parameters:

    - Use positive numbers only
    - Presale Rate: Token amount received during presale
    - Whitelist: Optional, can enable/disable anytime
    - Soft Cap: Must be ≥ 25% of Hard Cap
    - Refund Type: Choose between Burn or Refund.
    - Timeline: Start Time must be before End Time

    Note: Check total tokens needed for presale pool (shown above Back/Next buttons)

3. Finalize
    - Review all information
    - Click "Confirm & Create Launchpad"
    - Confirm in Phantom Wallet

Troubleshooting Pool Creation:
If transaction successful but no redirect:

1. Find pool address in transaction details
   Example transaction: https://solscan.io/tx/5CA7xKQjWyVT7pCKHSsgSJmdYrPETm9GWJnQjqcPUpbSM4SJee2unspVuq9SAZSPodLuyvERjApNZpzu7WT9ymci
2. Access pool at: https://pinksale.finance/solana/launchpad/{pool-address}
   Example: https://pinksale.finance/solana/launchpad/ARfghsEasv5K1YkgTWNoFSYkPADwPCnb2GiTRERw5pCv
3. Update Pool Details to appear in PinkSale system

Finalizing Launchpad:

1. In "Pool Action" zone:
    - Click "Finalize"
    - Confirm in Phantom wallet
2. Set Claim Time for users to claim tokens after contribution
