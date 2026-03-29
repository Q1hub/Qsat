# QSATS: The World's First High-Velocity Bitcoin L3 (Pure 1:1)

**Non-Custodial. Zero Inflation. QUBIC Deflationary. Batched for $10M BTC.**

QSATS is a specialized **Bitcoin Layer 3 (L3)** built on the Qubic Network (L2). It allows users to mint a 1:1 mirror token (**QSATS**) while maintaining 100% control of their BTC in their own **private cold wallets**. Secured by Qubic’s 676 Computor Quorum, QSATS turns Bitcoin liquidity into a massive revenue and buyback engine for the Qubic ecosystem.

---

## 🏗 Modular Architecture
- **Layer 1 (Security):** **Bitcoin** – BTC remains in self-custodial Taproot/Miniscript vaults.
- **Layer 2 (Logic):** **Qubic** – 676 Computors act as decentralized Oracle Machines to verify L1 locks.
- **Layer 3 (Application):** **QSATS** – High-velocity, 10-second batched transfers with 0 decimals.

## 🛠 Core Technical Specs
- **Minimum Lock:** 100,000 Satoshis (0.001 BTC).
- **Mint Ratio:** Strict 1:1 (No inflation).
- **Batching Engine:** 10-Second Transaction "Ticks" (Built for 1B+ transactions/day).
- **Safety Mechanism:** 30-day L1 Emergency Timelock (Direct Bitcoin Recovery).

---

## 💸 L3 Transaction Fees (Flat 25 Sats)
QSATS utilizes **10-Second Batching** to group thousands of transfers into single state updates. Every transfer triggers an automated four-way split:


| Allocation | Amount (Sats) | Destination |
| :--- | :--- | :--- |
| **Refuel Fund** | 10.0 | Passive Income for 676 Computors (Shareholders) |
| **QUBIC Buyback** | 5.0 | Permanent QUBIC Deflation (Buy & Burn via Qx) |
| **Dev Fund** | 5.0 | L3 Maintenance, Batching Optimization & R&D |
| **Staking Reward** | 5.0 | Yield for Active L3 Stakers (1-Year Cliff) |

---

## 🛡 Security & Resilience (The 30-Day Fix)
In the event of a critical L3 bug or L2 network outage:
1. **Computor Window:** Computors have **30 days** to reach a quorum (451+ votes) and patch the contract.
2. **User Fail-Safe:** If no resolution occurs within 30 days, the user's **L1 Bitcoin Timelock** expires. Users can then recover their BTC via their private key on the Bitcoin L1 network, bypassing the L3 entirely. **No funds are ever permanently trapped.**

---

## ⚖️ Exit & Yield Rules
- **1-Year Yield Cliff:** Staking rewards (from the 5-Sat pool) are only paid out after a continuous **365-day lock**.
- **Exit Fee:** 100 Satoshis.
- **Loyalty Waiver:** The 100-Sat exit fee is **waived** for users remaining for **1 year+**.

---

## 🔌 Hardware Compatibility
QSATS is compatible with all major hardware wallets supporting **BIP-86 (Taproot)** and **PSBTs**:
- **Trezor:** Safe 3, 5, 7, and Model T.
- **Ledger:** Nano X, Nano S Plus, Flex, and Stax.
- **Others:** BitBox02, Coldcard Q/Mk4, Foundation Passport, Blockstream Jade.

---

## ❓ FAQ

**Why 10-second batching?**
Batching groups thousands of L2 movements into single state updates. This ensures that even if Bitcoin reaches $10M, the 25-Sat fee remains economically viable for retail micro-payments while the protocol remains profitable.

**Is it truly self-custodial?**
Yes. You hold the L1 keys. The Bitcoin never leaves the L1 blockchain. You are simply using a Taproot script to authorize L3 utility.

**Does this require Trezor/Ledger approval?**
No. QSATS uses standard Bitcoin protocols (PSBT). Any hardware wallet that supports Taproot can sign the "Lock" transaction today.

