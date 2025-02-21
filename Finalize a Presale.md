# Finalize a Presale on EVM

## Overview
This guide explains how to finalize a presale on EVM-compatible networks like BSC. A video tutorial and technical support resources are available for additional help.

Tutorial Video: https://youtu.be/5lxR3NnWjwc

For technical support, contact trusted developers: https://docs.pinksale.finance/important/contract-developers

## Prerequisites
- Presale must meet softcap and end time or reach hardcap
- If token has fees, rewards, or max tx limits, exclude these functions for presale address

## Step-by-Step Guide

### Step 1: Access Contract on BSCScan
1. Click token address on presale page
2. Go to Contract -> Write Contract
3. Connect Web3 with owner wallet

### Step 2: Exclude Presale Address
1. Search for "exclude" or "exempt" function
2. Input presale address
3. Click "Write" to exclude fees, rewards, max tx
4. For exclude(bool), input "True"
5. Confirm transaction in MetaMask

### Step 3: Finalize Pool
1. Go to "Pool Actions" section
2. Click "Finalize" button
3. Confirm transaction in MetaMask

## Important Notes
- Must use contract owner wallet
- Complete all exclusions before finalizing
- Pay attention to gas fees
- Some contracts use "exempt" instead of "exclude"