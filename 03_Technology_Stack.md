# ⚙️ 03: Technology Stack

## The Engine of Trust: Hardware-Secured Blockchain

V-Ledger is built on a **Web2.5** architecture, combining the high security and decentralization of Web3 with the frictionless user experience of modern SaaS.

### 🏗️ System Architecture


```mermaid
graph TD
    A[Brand/User] -- Google Auth --> G[API Gateway]
    G -- Transaction Sponsorship --> AA[ERC-4337 Smart Account]
    AA -- Mint/Verify --> BL[Base L2 Blockchain]
    BL -- Metadata --> IPFS[Encrypted IPFS Storage]
    H[Physical Tag] -- SUN Token --> AA
```

### 💎 Core Components

#### 1. Hardware: NTAG 424 DNA (NFC)
- **Anti-cloning:** SUN (Secure Unique NFC) tokens provide a unique cryptographic proof for every scan.
- **Mutual Authentication:** Hardened physical security for industrial and consumer goods.

#### 2. Blockchain: Base (Ethereum L2)
- **Scalability:** Enterprise-grade performance with minimal latency.
- **Security:** Leverages the full security of the Ethereum mainnet while keeping costs low.

#### 3. Abstraction: ERC-4337
- **Invisible Wallets:** Users interact via Social Login; no seed phrases required.
- **Gasless UX:** Platform sponsors transaction fees, ensuring zero friction for the end-user.

---

<details>
<summary>🇩🇪 Technik-Details auf Deutsch anzeigen</summary>

### **Der Motor des Vertrauens: Hardware-gesicherte Blockchain**
V-Ledger basiert auf einer "Web2.5"-Architektur.

**1. Hardware: NTAG 424 DNA (NFC)**
Schutz vor Klonen durch SUN Tokens und kryptografische Authentifizierung pro Scan.

**2. Blockchain-Layer: Base (Ethereum L2)**
Skalierbarkeit auf Enterprise-Niveau und geringe Latenz bei voller Ethereum-Sicherheit.

**3. Web3 Abstraction: ERC-4337**
"Invisible Web3" Onboarding und Gasless-Transaktionen für maximale Usability.

</details>

---
[<< Previous Slide](02_The_Solution.md) | [Back to Overview](README.md) | [Next Slide: 04 Unique Value Props >>](04_Unique_Value_Props.md)
