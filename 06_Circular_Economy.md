# ♻️ 06: Economy & Incentives

## Dual-Incentive Infrastructure

V-Ledger provides the financial rails to incentivize sustainable behavior for mass-market goods and reward brand value for luxury assets.

### 📈 1. The Pfand (Deposit) System
*Target: Mass-Market, Electronics, Apparel*

```mermaid
graph TD
    M[Brand/Mint] -- locks x EURC --> SC[Smart Contract]
    SC -- associates deposit --> P[Product Passport]
    C[Customer] -- scans returned item --> R[Recycler/Hub]
    R -- verifies authentic tag --> SC
    SC -- releases x EURC --> C
```

### 💎 2. Secondary Market Royalties
*Target: Luxury Watches, Handbags, Limited Editions, High-End Tech*

V-Ledger allows brands to capture a percentage of every resale. When ownership is transferred via the app, the smart contract automatically routes a **Royalty Fee** back to the brand.

```mermaid
graph LR
    S[Seller] -- transfers passport --> B[Buyer]
    B -- pays price --> P[Payment Portal]
    P -- 95% --> S
    P -- 5% Royalty --> BR[Original Brand]
    BR -- verifies authenticity --> B
```

**Value for Brands:**
- **Continuous Revenue:** Profit from the increasing value of rare items.
- **Controlled Resale:** Ensure that high-value assets are only traded through verified channels.
- **Customer Insights:** Maintain a connection with the product owner across multiple life stages.

---

<details>
<summary>🇩🇪 Wirtschaftliche Anreize auf Deutsch anzeigen</summary>

### **Infrastruktur für Pfand & Royalties**
V-Ledger bietet zwei zentrale finanzielle Anreizsysteme:

**1. Das Pfandsystem (Mass-Market):**
Sicherstellung der Materialrückführung durch On-Chain hinterlegte Deposits.

**2. Secondary Market Royalties (Luxury):**
Automatische Umsatzbeteiligung der Marke bei jedem Wiederverkauf. Wann immer ein Produkt (z. B. eine Luxusuhr) den Besitzer wechselt, fließt ein prozentualer Anteil des Verkaufspreises direkt zurück an die Marke.

**Vorteile:** Dauerhafte Einnahmen, Markenschutz und Transparenz über den gesamten Lebenszyklus hochwertiger Assets.

</details>

---
[<< Previous Slide](05_The_Product_Exosystem.md) | [Back to Overview](README.md) | [Next Slide: 07 Business Model >>](07_Business_Model.md)
