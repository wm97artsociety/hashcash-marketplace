# hashcash-marketplace

Hash Cash (HC) is a custom-built, penny-pegged crypto token ecosystem designed as a decentralized free-market marketplace powered by its own blockchain — Manierism — using a Hashcash proof-of-work algorithm. The system includes a native mobile app (Android APK), web marketplace (Firebase), smart tax routing, and dynamic tiered tokenomics to promote fairness, security, and upward-only price growth.

🧠 CORE COMPONENTS
🔹 1. Token System: Hash Cash Token (HC)
Symbol: HC

Blockchain: Manierism (custom blockchain)

Consensus Algorithm: Hashcash (Proof-of-Work)

Starting Value: $0.00

Value Model: 1 penny ($0.01) deposited = $0.01 added to token price

No Liquidity Pools or Exchange Pegs

No Token Burning

🧮 Tokenomics Ladder
Total Deposited (USD)	Buy Fee	Sell Fee
$0–$9,999	14%	7%
$10K–$19,999	12%	5%
$20K–$49,999	10%	3%
$50K–$99,999	8.5%	2.5%
$100K+	5%	1.75%

Tier Upgrades: Triggered automatically when deposit milestones are crossed

Dip Stop: If too many sells occur quickly, sell fees temporarily rise or freeze

Buy Go: Surge in buy volume reduces buy fees to boost market activity

🔹 2. Blockchain: Manierism
Block Time: 3 minutes (180 seconds)

Miner Algorithm: Hashcash SHA-256 (17 difficulty levels)

Miner Access: Mobile APK + Backend block verification

No fees for transactions or mining

On-chain storage of:

hc_value (current token price)

total_deposited (USD equivalent)

feeTierLevel

buyVolume and sellVolume metrics

🔹 3. Wallet System
Integrated Wallet Connect

Supports:

Balance check for HC

Send/receive HC

Unlock access to the upanel/admin

Triggers token uploads, purchases

Admin Wallet used for:

Tax routing (30% savings wallet)

Receiving platform fees

Token uploads and approvals

🔹 4. Frontend Marketplace (Firebase Web App)
Stack: HTML, CSS, JavaScript

Features:

Free product listings

Firebase realtime DB or Firestore

Firebase Hosting deployable

Buy/sell interface with HC token pricing

Dynamic fee ladder visible in UI

Smart token upload flow (with no fees)

User Roles:

Buyers (wallet required)

Sellers (wallet required)

Admin (can view all listings and control global settings)

🔹 5. Android Mobile App (APK)
Name: HC Marketplace

Built With: Android SDK, Java/Kotlin

Features:

Native wallet connection

View and list marketplace products

Start Hashcash mining

View real-time HC token value

Auto-sync with Firebase database

Installable via .apk or Play Store

🧩 TECH STACK
Layer	Tech Used
Blockchain	Custom Node.js engine (Manierism)
Tokenomics	JavaScript rules on deposit-based value
Wallet	JavaScript Web3-like SDK
Frontend	HTML/CSS + Firebase Hosting
Backend API	Node.js (deployable via Render)
Database	Firebase Firestore or Realtime DB
Mobile	Android APK (Java/Kotlin)

🔒 SECURITY FEATURES
No market-based price manipulation (price is fixed by deposits only)

Mining cannot be spoofed (Hashcash difficulty levels required)

Tax routing locked to admin wallet

Tiered economic structure discourages abuse

Wallet access required to list, mine, or purchase

🎯 PURPOSE
Empower any user to create and sell digital goods without friction

Avoid gas fees and central exchanges

Prevent liquidity drains and token rug pulls

Introduce a reliable, deposit-driven token model

Support mobile mining, low-entry access, and developer autonomy

