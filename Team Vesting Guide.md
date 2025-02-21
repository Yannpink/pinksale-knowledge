# Team Vesting Guide

## Overview
Team Vesting System locks team tokens for a set period to prevent rug pulls and build investor trust. System was audited by CerTik: https://skynet.certik.com/projects/pinksale

## Setup Process
1. Connect wallet
2. Visit https://pinksale.finance/pinklock/create
3. Input token/LP token address
4. Enter token owner address (for receiving unlocked tokens)
5. Set lock title (e.g. "ProjectName Team Vesting")
6. Input total vesting amount (in tokens, not percentages)
7. Enable "use vesting" checkbox

## Vesting Parameters
- TGE Date: Set to listing time
- TGE Percent: Initial token release percentage
- Cycle (days): Days between releases
- Cycle Release Percent: Percentage released each cycle

## Example Configuration
For 100,000 total team tokens:
- TGE Date: 2022-05-22T18:39
- TGE Percent: 20 (20,000 tokens at launch)
- Cycle: 30 days
- Cycle Release: 40 (40,000 tokens per month)
- Total Cycles: 2 (60 days total)

## Locking Process
1. Click "Approve"
2. Confirm transaction in wallet
3. Click "Lock"
4. Confirm final transaction

## Important Notes
- Not compatible with rebase tokens
- Exclude PinkLock address from fees/rewards: 0x407993575c91ce7643a4d4cCACc9A98c36eE1BBE
- Unclaimed tokens accumulate between cycles
- Can claim anytime after cycle expires

## Claiming Process
1. Visit PinkLock page
2. Click "Unlock" for available tokens
3. Optional: Click "Renounce Lock Ownership" to permanently lock (irreversible)

Note: Renouncing transfers ownership to dead wallet - only do if you fully understand implications.