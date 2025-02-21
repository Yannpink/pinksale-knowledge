# Pink Anti-Bot Guide

## Overview

Pink Anti-Bot is a system designed to protect presales and fair launches from bot manipulation. It helps maintain fair participation by blocking malicious bots.

## Setup Process

1. Connect wallet and access Pink Anti-Bot at https://www.pinksale.finance/#/antibot
2. Select existing token or create new token with Pink Anti-Bot System enabled
3. Configure Anti-Bot parameters:
   - Select Router Exchange (e.g. PancakeSwap)
   - Select Pair Token (e.g. BNB)
   - Set Amount Limit Per Trade
   - Configure Amount Added Per Block
   - Set Time Limit Per Trade (seconds)
   - Set Block Number to Disable (min 150)
4. Save configuration and pay required fee
5. Enable Pink Anti-Bot before adding liquidity

## Configuration Parameters

### Amount Limit Per Trade
- Initial limit on tradable tokens at listing
- Traders cannot exceed this amount

### Amount Added Per Block
- Added to Amount Limit Per Trade from block 1
- Increases maximum tradable amount over time
- Example: 1 token limit + 1 token per block = 100 token limit after 100 blocks

### Time Limit Per Trade
- Delay between transactions (e.g. 60 seconds)
- Prevents rapid trading
- Automatically disabled when Block Number reached

### Block Number to Disable
- Anti-Bot works from listing until this block
- Must be 150 or higher
- Can manually disable anytime

## Management Features

### Blacklist Management
- Add users to blacklist to prevent trading
- Remove users from blacklist as needed

### Status Monitoring
- View project protection status
- Track remaining blocks until disable
- Monitor current trading limits

## Important Notes

- Must enable before adding liquidity
- Cannot be enabled after liquidity added
- Free service for all PinkSale users
- Manual disable option available

Tutorial Video: https://www.youtube.com/watch?v=37s-8BCFNOU
Documentation: https://docs.pinksale.finance/important/pink-anti-bot