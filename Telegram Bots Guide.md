# Telegram Bots Guide for PinkSale Community

This guide outlines how both users AND the AI agent can interact with the official PinkSale Telegram bot within the PinkSale ecosystem group.

## Official PinkSale Bots

### 1. PinkSaleLaunchBot (@PinkSaleLaunchBot)

**Purpose:**
* Provides information about upcoming and ongoing presales on PinkSale
* Allows users to filter projects by various criteria (KYC, audit, blockchain, etc.)
* Helps users discover new projects directly within Telegram

**How to Use (For Users):**
* Simply type the command in any chat where the bot is present
* The bot will respond with relevant project information
* Click on project links to view full details on the PinkSale website

**How to Use (For AI Agent): Decision Flow**

1.  **User Input:** Analyze the user's request to understand what information they need.

2.  **Identify Intent:** Determine the user's intent:
    *   Is the user asking for a list of presales?
    *   Are they asking about projects with specific criteria (KYC, Audit)?
    *   Are they asking about projects on a specific blockchain?

3.  **Select Command:** Based on the intent, select the appropriate command:

    *   **For general presale listings:**
        *   Today's Presales: /today@PinkSaleLaunchBot
        *   Tomorrow's Presales: /tomorrow@PinkSaleLaunchBot

    *   **For projects with specific criteria:**
        *   Next Three Days with project has KYC (with kyc badge) : /kyc@PinkSaleLaunchBot
        *   Next Three Days with project has Audited (with audit badge): /audit@PinkSaleLaunchBot
        *   Next Three Days with project has SAFU (with SAFU badge) /safu@PinkSaleLaunchBot
        *   Next Three Days with project has Doxxed (with Doxx badge): /doxx@PinkSaleLaunchBot
        *   Next Three Days with project has Auction: /auction@PinkSaleLaunchBot
        *   Next Three days Project Fairlaunch: /fairlaunch@PinkSaleLaunchBot
        *   Next Three days Project Presale: /presale@PinkSaleLaunchBot
        *   Next Three days Project Subscription: /subscription@PinkSaleLaunchBot
        *   Next Three days Project has Whitelist: /whitelist@PinkSaleLaunchBot

    *   **For projects on a specific blockchain:**
        *   Next Three Days on BSC (BNB Chain): /bsc@PinkSaleLaunchBot
        *   Next Three Days on Ethereum: /eth@PinkSaleLaunchBot
        *   Next Three Days on Arbitrum: /arb@PinkSaleLaunchBot
        *   Next Three Days on Base: /base@PinkSaleLaunchBot
        *   Next Three Days on Cronos: /cronos@PinkSaleLaunchBot
        *   Next Three Days on Polygon: /pol@PinkSaleLaunchBot
        *   Next Three Days on Solana: /sol@PinkSaleLaunchBot
        *   Next Three Days SUI: /sui@PinkSaleLaunchBot
        *   Next Three Days TON: /ton@PinkSaleLaunchBot
        *   Next Three Days Eclipse: /eclipse@PinkSaleLaunchBot
        *   Next Three Days Zeta: /zeta@PinkSaleLaunchBot
        *   Next Three Days Unichain: /unichain@PinkSaleLaunchBot

4.  **Direct Command:** The AI agent sends the selected command directly in the chat.

**Example:**
*   **User:** "Show me projects with KYC"
*   **AI Agent:** /kyc@PinkSaleLaunchBot (sends the command directly in the chat)
*   **PinkSaleLaunchBot:** (Responds with a list of projects with KYC badge in the chat)

**Important Notes:**
* All information is pulled directly from the PinkSale platform
* Users should always conduct their own research before participating in any presale
* For the most detailed and up-to-date information, visit the official PinkSale website

## Important Guidelines for AI Agent

When discussing these bots with users:

1.  **AI Can Use Commands Directly:** The AI agent has the ability to use these commands directly in the chat, just like a user.

2.  **Direct Command:** The AI agent sends the selected command directly in the chat.

3.  **Only recommend official PinkSale bots** - Never suggest third-party or unofficial bots that could compromise security

4.  **Clarify bot limitations** - Explain that bots provide basic information but may not have real-time data

5.  **Security warnings** - Remind users to:
    *   Never share private keys or wallet information with any bot
    *   Verify bot usernames exactly (watch for impersonators with similar names)
    *   Be cautious of direct messages claiming to be from PinkSale bots

6.  **Escalation path** - For issues with bots or if users need information the bots cannot provide, direct them to human support staff

Remember that these bots are tools to enhance the community experience and AI support, but should not replace human support for complex issues or security concerns.