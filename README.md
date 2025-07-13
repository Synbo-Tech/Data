# 📢 Dear Community Members and Brokers,

We hereby make a formal statement: **As an open and permissionless protocol, CCO does not conduct any vetting or endorsement of listed projects.** This principle aligns with the spirit of other public blockchain protocols such as Uniswap.

### ✅ Core Principle: Permissionless Operation  
CCO is a fully decentralized protocol. **Any project can be freely created, published, and participated in without requiring any approval or review from the platform.**

We firmly believe that **"position consensus" is the most fair and just filter in the Web3 world**.  
Just as Satoshi Nakamoto never reviewed each block nor judged who should be rewarded。  

### <span style="color:red"> **the platform does not assess whether a project is “good or bad,” “true or false,” or whether it has “potential.”**。

Everything operates based on **position proof** — that is the true value of the protocol. </span>    
### We collect the following information **solely to help brokers access data more effectively for their own research and consensus judgment** — it is **not** for the purpose of review or recommendation.

---
## Investment Disclaimer

This platform serves solely as an information and service portal for decentralized projects. It does not initiate, manage, or guarantee any fundraising or token subscription activities. All project-related materials, data, whitepapers, and token models are published by the respective project teams. The platform does not conduct in-depth due diligence or endorse any projects.

Investing in digital assets carries risk. Participation in fundraising, token subscription, or trading activities via this platform is entirely at the user's own discretion and risk. The platform shall not be held liable for any financial loss, profit fluctuation, or legal consequence arising therefrom.

Important reminders:

- The platform does not provide any form of investment advice or profit guarantees;

- The platform does not guarantee the authenticity, legality, or feasibility of any project;

- Users should make decisions based on independent research and risk tolerance;

- The platform reserves the right to adjust, suspend, or remove certain features in response to regulatory requirements.

By using this platform, you acknowledge that you have read, understood, and accepted this disclaimer. If you do not agree, please refrain from participating in any subscription or investment activity.


-------------------------------
----------------
--------
---



# Project Submission Guidelines

Please submit projects using **feature branches**.

Within the `projects` folder, create a **new subfolder** following this naming convention:  
`TokenName_TokenSymbol_ChainName`  
Example: `AlphaSynboMeme_ASM_BSC`

---

## Folder Structure

Inside this folder, include the following files:

### 1. Token Metadata File  
- Filename: `TokenName_TokenSymbol_ChainName.json`  
- Example: `AlphaSynboMeme_ASM_BSC.json`

### 2. Project Details (Descriptive Content)  
- Filename: `Project_Details.md`  
- Format: Markdown (`.md`)

### 3. Financing Proposal  
- Filename: `Raising_Proposal_YYYYMMDD.md`  
- Example: `Raising_Proposal_20250423.md`  
- Format: Markdown (`.md`)
- This file will not be modified once used. You can provide multiple proposal files.

### 4. Withdrawal Proposal *(optional, can be added later)*  
- Filename: `Withdrawal_Proposal_YYYYMMDD.md`  
- Example: `Withdrawal_Proposal_20250423.md`  
- Format: Markdown (`.md`)
- This file will not be modified once used. You can provide multiple proposal files.

---

## Notes

- All descriptive documentation **must be written in Markdown (`.md`) format**.
- Please follow all naming conventions strictly when submitting on GitHub.

---

## Example Structure

projects/
└── AlphaSynboMeme_ASM_BSC/
    ├── AlphaSynboMeme_ASM_BSC.json
    ├── Project_Details.md
    ├── Raising_Proposal_20250423.md
    └── Withdrawal_Proposal_20250423.md


An example is shown below.

## 1. Token Info
### Naming Convention
- TokenName_TokenSymbol_ChainName.Json
e.g. : AlaphaSynboMeme_ASM_BSC.Json

### File Content
The file content is as follows. Please read it carefully.
```javascript
{
    "Token": {
        "Name": "",  // For example, SYNBO  
        "Symbol": "",   
        "Logo": " ",  // svg，less 120 * 120  
        "CA": " ",  // ERC20，BEP20 contract address    
        "TotalSupply": "",  // Total token supply  
        "CirculatingSupply": "",  // Circulating supply  
        "WhereChain": "",  // Token chain, e.g., ETH, BNB  
        "TokenType": "",  // e.g., ERC20, BEP20, Native Token  
        "Tags":",", // multi-choice, "like": Infra,DeFi,AI,Layer1,Layer2,DePIN,Modular,Cloud Computing,Restaking,LSD,others      
        "Token-Description": "",  // Description of the token’s function, utility, or lifecycle  
        "Project-Relationship": " " // Explain its relationship with the project   
    },   
    "Project": {  
        "Title": "",  // Project name, e.g., "SYNBO protocol"  
        "Logo": "",  // svg file，less 300 * 300   
        "Description": "",  // Project introduction within 50 characters   
        "Chains": "",  // Supported blockchains, e.g., "ETH, BNB" , MiltiChain  
        "Tokens":" " // List of Tokens Related to the Project， Format："Token-CA,Token-CA"   
    },   
    "Social": {   
        "Website": "",   
        "Twitter": "",   
        "Telegram": "",   
        "Github": "",   
        "Medium": "",   
        "Discord": "",   
        "Email": "",   
        "Others": ""  
    }  
}   
```


# Here we only verify the correctness of the format, not the correctness of the content.
