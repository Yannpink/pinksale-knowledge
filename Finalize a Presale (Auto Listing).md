# Finalize a Presale on Solana (Auto Listing)

## Overview
This guide explains how to finalize your presale on Solana after meeting softcap/hardcap, with specific instructions for both Raydium and GoatSwap DEX options.

## Listing on Raydium

### Step 1: Create OpenBook Market ID
1. Access OpenBook Market ID creation tool: https://openbook-tools.dexlab.space/market/create
2. Important: You need at least 3 $SOL for transaction fees. Platform fee is non-refundable even if market ID creation fails.

### Step 2: Configure Market Settings
1. Keep default setting on 'Create Market ID' tab
2. Enter token details:
   - Base Mint: Your token mint address
   - Quote Mint: Choose pairing token address
     - USDC: EPjFWdd5AufqSSqeM2qN1xzybapC8G4wEGGkZwyTDt1v
     - USDT: Es9vMFrzaCERmJfrF4H2FYD4KCoNkY11McCe8BenwNYB
     - Wrapped SOL: So11111111111111111111111111111111111111112

3. Set trading parameters:
   - Min. Order Size: Sets minimum order quantity
     - 4 = 0.0001 unit
     - 0 = 1 unit
     - 1 = 0.1 unit
   - Price Tick: Sets price display decimals
     - 5 = display like 11.12345
     - 4 = display like 11.1234

### Important Configuration Rules
- Minimum order size cannot exceed base token's decimals
- Price tick size cannot exceed quote token's decimals
- Sum of minimum order size + price tick cannot exceed quote token decimals
- Example: For base token with 9 decimals paired with USDC (6 decimals):
  - Valid: Min order size 3 + Price tick 2 = 5 (less than 6)
  - Invalid: Min order size 4 + Price tick 4 = 8 (exceeds 6)

### Step 3: Finalize Listing
1. Copy your new market ID after creation
2. Paste ID in "Finalize" selection on PinkSale

## Listing on GoatSwap

### Step 1: Finalize Pool
1. Click "Finalize" in Pool Actions
2. Configure settings:
   - Set Tax Setting for trading
   - Set Trading Time (must be after current time)
3. Click "Finalize" to complete

### Step 2: Post-Listing Actions
1. Users can claim tokens after finalization
2. Trading can begin via:
   - Click "Swap token" button
   - Click "GoatSwap" link to access www.goatswap.com
3. Connect wallet on GoatSwap to start trading