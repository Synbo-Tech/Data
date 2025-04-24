Please submit projects using feature branches. Add a new folder in the "projects" folder. The naming convention for folders is: TokenName_TokenSymbol_ChainName, e.g. : AlaphaSynboMeme_ASM_BSC

Subsequently, you can add token info, project detail files, and financing proposal files under this folder.

## 1. Token Info
### Naming Convention
- TokenName_TokenSymbol_ChainName.Json
e.g. : AlaphaSynboMeme_ASM_BSC.Json

### File Content
The file content is as follows. Please read it carefully.
```json
{
    "Token": {
        "Name": "",  // For example, SYNBO
        "Symbol": "", 
        "Logo": " ",  // svg，less 120*120
        "CA": " ",  // ERC20，BEP20 contract address.
        "TotalSupply": "",  // Total token supply
        "CirculatingSupply": "",  // Circulating supply
        "WhereChain": "",  // Token chain, e.g., ETH, BNB
        "TokenType": "",  // e.g., ERC20, BEP20, Native Token
        "Tags":",", // multi-choice, "like": Infra,DeFi,AI,Layer1,Layer2,DePIN,Modular,Cloud Computing,Restaking,LSD,others, 
        "Token-Description": "",  // Description of the token’s function, utility, or lifecycle
        "Project-Relationship": " " // Explain its relationship with the project.
    },
    "Project": {
        "Title": "",  // Project name, e.g., "SYNBO protocol"
        "Logo": "",  // svg file，less 300*300
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

## 2. Project Detail File
### Naming Convention
- Project_Details.md

### File Content
Kindly provide a detailed description of the project's innovations and development roadmap. You may refer to the template below for guidance.

The document will be uploaded to GitHub to maintain a history of edits and will be shared with brokers and investors throughout the fundraising process.

For example ： 

Please ultimately provide a markdown format file (name.md).

### 1. Project Overview
#### 1.1 Overview
An outline of the project's key features and objectives.
Kindly refer to the attached file.

#### 1.2 Background
Elaborate on the background of the project's birth, such as changes in market demand, industry development trends, or the shortcomings of existing solutions. For example, with the rise of blockchain technology, the traditional financial industry faces high transaction fees and long processing times in cross - border payments. This project aims to utilize the decentralized features of blockchain to create an efficient and low - cost cross - border payment platform.

#### 1.3 Goals
Define the short - term and long - term goals of the project clearly. The short - term goal could be to complete the development of the basic functions of the product within six months and conduct small - scale testing. The long - term goal could be to become a leading global cross - border payment solution provider and capture a certain market share within the next three years.

#### 1.4 Project Features
List the unique aspects that distinguish the project from other competitors. For instance, this cross - border payment platform adopts an innovative consensus algorithm that can reduce the transaction confirmation time to a few seconds while ensuring transaction security, and the transaction fees are 80% lower than the traditional methods.

### 2. Team Details
#### 2.1 Introduction to Core Members
Introduce the core team members of the project one by one, including the project leader, technical backbone, and marketing and operation experts. For example, the project leader [Name] has many years of experience in the fintech industry and has successfully led the development and promotion of several large - scale projects. The technical backbone [Name] is a senior developer in the blockchain field and has participated in the underlying architecture design of several well - known blockchain projects.

#### 2.2 Member Backgrounds
Describe in detail the educational backgrounds, professional skills, and relevant work experiences of team members. For example, a member graduated from the computer science major of [Renowned University], has a solid programming foundation, and has engaged in blockchain development work in [Well - known Enterprise], accumulating rich practical experience.

### 3. Token Economy
#### 3.1 Issuance Mechanism
Explain the issuance method of tokens, including the total issuance volume and whether there is an additional issuance mechanism. For example, the total supply of tokens in this project is set at 100 million, and it is issued in a one - time manner with no subsequent additional issuance to ensure the scarcity of tokens.

#### 3.2 Allocation Plan
Elaborate on the allocation ratio of tokens among different stakeholders. For example, 20% of the tokens are reserved for the team for incentives and operations, 30% for investors, and 50% for community building and user rewards.

#### 3.3 Token Utility
Illustrate the specific uses of tokens within the project ecosystem. For example, in this cross - border payment platform, users can use tokens to pay transaction fees and enjoy certain discounts. Token holders can also participate in the governance decision - making of the platform and vote on important matters.

### 4. Roadmap
#### 4.1 Future Development Plan
Describe in detail the development plans of the project at different stages, including product iteration, market expansion, and cooperation plans. For example, in the first stage, the focus is on improving the cross - border payment function and expanding cooperation with some small - scale financial institutions. In the second stage, optimize the user experience, launch a mobile application, and negotiate cooperation with large - scale financial institutions.

#### 4.2 Timeline
Set clear time nodes for each development stage. For example, the first stage is expected to be completed within the next six months, and the second stage is planned to be advanced within the next 12 months.

### 5. Historical Fundraising Information
#### 5.1 Financing Rounds
List all the financing rounds the project has experienced, such as the seed round, angel round, Series A, etc.

#### 5.2 Financing Amounts
Specify the specific amount of funds raised in each financing round. For example, the seed round financing raised $1 million, and the angel round financing reached $5 million.

#### 5.3 Investors
Introduce the investors who participated in each financing round, including the names of investment institutions and their investment backgrounds. For example, [Renowned Investment Institution] has rich investment experience in the blockchain field and has successfully invested in several leading projects in the industry. This time, it participated in the Series A financing of this project, injecting strong impetus into the project's development.

## 3. Financing Proposal File
### Naming Convention
- Raising_Proposal_CreationTime.md
e.g. :Raising_Proposal_20250423.md

### File Content
The document will be uploaded to GitHub to maintain a history of edits and will be shared with brokers and investors throughout the fundraising process.

For example ：

Please ultimately provide a markdown format file (name.md).

### 1. Distribution Type
Specify the type(s) of asset distribution adopted in this financing round, including but not limited to:
- Finacing
- Airdrop
- Real World Asset (RWA) 
- Fair Launch
- C2C Distribution
- Others

### 2. Asset Description & Valuation
#### 2.1 Asset Details
Provide a detailed description of the distributed asset, including:
- Asset name and total supply
- Functional purpose (e.g., platform token, governance certificate, equity representation)
- For digital or physical assets, describe the technical implementation, ownership structure, and circulation rules

#### 2.2 Valuation Method & Results
- Valuation method adopted (e.g., market comparison, discounted cash flow, cost - based) and rationale for the choice
- Pre - money and post - money valuation with calculation basis

### 3. Voucher Type
Specify the nature and type of the financing instrument used in this round:
- Platform Points
- Digital Tokens (Utility/Crypto)
- Equity Certificates or Rights
- Hybrid Instruments

### 4. Redemption Mechanism (If Applicable)
If the financing voucher allows redemption or exit, please specify:
- What the voucher can be redeemed for (e.g., goods, services, platform revenue)
- Exchange ratios (e.g., 1:1, variable rate)
- Exit mechanism for equity - related vouchers, dividend policy, or lock - up periods

### 5. Purpose & Budget Breakdown
#### 5.1 Purpose of Financing
Clearly define the intended use of funds, including:
- Product and technology development
- Marketing and user acquisition
- Team expansion and talent recruitment
- Daily operations and overheads

### 5.2 Budget Allocation Table
| Category | Estimated Amount (USD) | Description |
| ---- | ---- | ---- |
| Product R&D | [X] | Feature iterations, tech upgrades |
| Marketing | [X] | Advertising, brand campaigns, social media operations |
| Team Expansion | [X] | Recruitment and staff training |
| Operational Costs | [X] | Rent, utilities, equipment procurement |

### 5.3 Funding Timeline & Milestones
The expected usage period for this round of financing is 6–12 months, with key milestones as follows:
| Phase | Time Frame | Key Milestone |
| ---- | ---- | ---- |
| Phase 1 | Months 0–3 | MVP development and launch of core product |
| Phase 2 | Months 3–6 | Initial marketing campaign, achieving early user base |
| Phase 3 | Months 6–9 | Feature optimization, improving UX & retention |
| Phase 4 | Months 9–12 | Overseas market expansion, preparation for next round | 

### 6. Community Rights & Participation
#### 6.1 Participation Rights
Describe how the community can participate in governance, such as:
- Voting mechanisms (e.g., on - chain governance)
- Proposal submission and veto rights

#### 6.2 Rights Allocation
Describe the rights that come with holding the asset, such as:
- Dividend rights
- Priority access to new projects or offerings
- Utility or redemption rights

#### 6.3 Community Development Plan
Outline initiatives to promote community growth and engagement, such as:
- Reward mechanisms
- Event operations
- Community fund establishment

### 7. Qualification Documents (If Applicable)
If applicable, please provide the following documentation:
#### 7.1 Company Credentials
- Business license
- Tax registration
- Unified social credit code or company registration number

#### 7.2 Industry Certifications
If operating in regulated sectors (finance, data, security, etc.), provide relevant licenses or certifications.

#### 7.3 Team Qualifications
- Academic and professional credentials of core members
- Records of past entrepreneurial or project experience

After submission, it will be reviewed by a dedicated team member and merged into the main branch. Project information will only be visible on the merged website. 
