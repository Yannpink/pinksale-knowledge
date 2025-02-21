# Create a Lock

## Overview

PinkLock allows you to edit tokenomic chart on your presale. It was audited by CerTik and many audit firms: https://skynet.certik.com/projects/pinksale

**Important**: Please exclude PinkLock's lockup address 0x5E5b9bE5fd939c578ABE5800a90C566eeEbA44a5 from fees, rewards, max tx amount to start locking tokens.

## Lock Types

### Step 1: Lock Without Vesting

1. Connect wallet
2. Access: From homepage "PinkLock" => "Create Lock" or https://pinksale.finance/pinklock/create
3. Input token/LP token address
4. Optional: Use "another owner" function (unlocked tokens sent to this address)
5. Input lock title (Example: "LOCK PINKSALE.FINANCE")
6. Input token amount for locking (numbers only, no percentages)
7. Set lock time (UTC)
8. Approve transaction and pay fee
9. Confirm lock transaction and pay fee

### Step 2: Lock Using Vesting

1. Connect wallet
2. Access: From homepage "PinkLock" => "Create Lock" or https://pinksale.finance/pinklock/create
3. Input token/LP token address
4. Optional: Use "another owner" function
5. Input lock title (Example: "VESTING PINKSALE.FINANCE")
6. Input token amount for vesting
7. Enable "use vesting" checkbox

#### Vesting Parameters

- TGE Date: Set to listing time
- TGE (percent): First batch release percentage
- Cycle (days): Days between each vesting release
- Cycle Release (percent): Percentage released each cycle
  Note: Rest percent releases in last cycle

#### Final Steps

1. Approve transaction and pay fee
2. Confirm lock transaction and pay fee

## Important Notes

- Team Vesting doesn't support rebase tokens
- All percentages must be input as numbers, not decimal values
