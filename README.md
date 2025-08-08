# Parking Space Rental Smart Contract

## 📌 Project Title
**Parking Space Rental on Aptos Blockchain**

---

## 📖 Description
The **Parking Space Rental** smart contract is a decentralized application built on the Aptos blockchain using the Move programming language.  
It enables parking space owners to register their spaces with a defined hourly rate, and allows renters to pay directly for their parking duration using Aptos Coins (APT).  
All transactions are transparent, secure, and verifiable on-chain.

**Key Features:**
- Owners can **register** their parking spaces with a chosen hourly rate.
- Renters can **pay** for parking hours, transferring tokens directly to the owner.
- The contract keeps track of **total earnings** for each owner.
- No intermediaries — purely peer-to-peer.

---

## 🎯 Vision
To create a **trustless, transparent, and efficient** system for short-term and long-term parking rentals, empowering individuals to monetize unused parking spaces while providing renters with secure and instant payment options.

---

## 🚀 Future Scope
- **Location Integration**: Link parking spaces with GPS coordinates for real-world use.
- **Time Tracking**: Automatically calculate fees based on actual parking time.
- **Booking System**: Allow renters to reserve spaces in advance.
- **Multi-Currency Support**: Accept various token types beyond AptosCoin.
- **Rating & Review System**: Build trust between owners and renters.
- **Mobile App Integration**: Enable on-the-go payments and reservations.

---

## 📂 Module Details
- **Module Name:** `ParkingRental`
- **Structs:**  
  - `ParkingSpace` → Stores hourly rate and total earnings.
- **Functions:**  
  - `register_space(owner: &signer, hourly_rate: u64)` → Registers a parking space.  
  - `rent_space(renter: &signer, owner_addr: address, hours: u64)` → Pays rent for a set number of hours.

---

## 🛠 Technology Stack
- **Blockchain:** Aptos
- **Language:** Move
- **Framework:** Aptos Framework & Move Standard Library
