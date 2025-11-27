# penaltycard
# 🟨 PenaltyCard Smart Contract

A simple and beginner-friendly Solidity smart contract designed to issue, track, and clear penalty points on the blockchain. Built for learning, experimenting, and showcasing basic smart-contract logic without requiring any input during deployment.

---

## 📌 Project Description

**PenaltyCard** is a minimal smart contract that allows an owner (the deployer) to issue penalties to Ethereum addresses.  
Addresses with penalties can pay fines in Ether to remove their penalty points.  
This project is focused on **simplicity**, **clarity**, and **educational value**, making it perfect for beginners exploring Solidity and blockchain interactions.

---

## 🎯 What It Does

- Lets the contract **owner** issue or clear penalties for any address.  
- Tracks how many penalty points each address has.  
- Allows penalized users to **pay fines** to remove penalties.  
- Stores all collected fines inside the contract balance.  
- Allows the owner to **withdraw Ether** collected as fines.  
- Includes a dynamic fine amount and block-threshold that the owner can update.

---

## ⭐ Features

### ✔ No deployment inputs  
The contract deploys instantly — no parameters required.

### ✔ Penalty system  
- Add penalties to an address  
- Clear penalties  
- Check if an address is “blocked” (based on threshold)

### ✔ Fine payment system  
- Users can pay Ether to remove penalty points  
- Extra wei is automatically refunded  
- Fine amount is configurable

### ✔ Owner-only controls  
- Issue penalties  
- Clear penalties  
- Withdraw all collected Ether  
- Update fine amount  
- Update block threshold

### ✔ Events for transparency  
Every important action emits an event:
- PenaltyIssued  
- PenaltiesCleared  
- PenaltyPaid  
- Withdrawn  
- FineAmountChanged  
- BlockThresholdChanged  

---

## 🔗 Deployed Smart Contract

Contract successfully deployed on **Flare Coston2 Testnet**:  

👉 **https://coston2-explorer.flare.network/tx/0x7614474018303ab7e8237af4dc989f015186d6b3306459acfb7886460c9afe07?tab=index**

You can use this explorer link to verify the transaction and interact with the code on-chain.

---

## 📦 Smart Contract Code (Solidity)

Replace the placeholder below with your actual contract code when uploading to GitHub:

```solidity
// XXX
// paste your code
