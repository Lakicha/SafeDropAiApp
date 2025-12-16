# SafeDropAiApp

![License: MIT](https://img.shields.io/badge/License-MIT-green)
![Build Status](https://img.shields.io/badge/Build-Passing-brightgreen)
![NPM Version](https://img.shields.io/badge/NPM-v1.0.0-blue)

AI rider and shop safety tool for online deliveries. SafeDropAiApp helps shops and delivery riders stay safe by verifying buyers before dispatch and providing rider safety support. The goal is to reduce attacks, fraud, and losses.

## Problem
Delivery riders and small businesses face real danger from fake buyers. Many orders come from unverified phone numbers and false locations. Riders arrive without knowing who they are meeting. When attacks happen, there is no digital record to help investigations.

## Solution
SafeDropAiApp verifies buyers before delivery and supports rider safety during drop-off. The system creates a clear record of each order and gives shops the confidence to dispatch safely.

## Key Features
- Buyer identity check using selfie and phone number
- Liveness check to stop fake photos
- Location confirmation before dispatch
- Risk score to guide dispatch decisions
- Rider safety alerts and check-in flow
- Digital records for follow-up

## How It Works
1. Shop creates a delivery order.
2. Buyer receives verification link.
3. Buyer completes identity and location checks.
4. System reviews and assigns risk level.
5. Shop decides whether to dispatch.
6. Rider follows safety steps during delivery.

## Technology
- **Frontend:** Web and mobile interface
- **Backend:** Node.js server
- **AI:** Face match, liveness check, risk scoring
- **Maps & Messaging:** Location confirmation
- **Security:** Encrypted data

## Project Structure
- `backend` – Node.js server
- `frontend` – shop and rider interface
- `models` – AI models
- `docs` – guides/notes
- `README.md`, `LICENSE`, `.gitignore`

## Installation
```bash
git clone https://github.com/Lakicha/SafeDropAiApp.git
cd SafeDropAiApp
npm install
npm start
