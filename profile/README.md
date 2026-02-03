# SupplyShark (2024 - 2025)

### 🦈 High-Performance Supply Chain Security (Post-Mortem)

**SupplyShark** was a SaaS platform designed to detect software supply chain vulnerabilities in real-time. It scanned thousands of packages to notify businesses of potential package hijacking vulnerabilities before an attack could occur.

While the business entity has wound down, the core technology remains a powerful example of **high-scale security engineering** and is now open source.

### 🏆 Battle-Tested & Proven
This tool was not just a prototype. I personally used the **SupplyShark Engine** to report critical vulnerabilities in bug bounty programs across:
* **Immunefi** (Crypto/Web3)
* **HackerOne**
* **Private Disclosures**

The engine successfully identified dependency confusion and package hijacking vectors in major protocols and platforms, securing thousands of dollars in bounties.

### 🔓 Why Open Source?
I am releasing the core engine because **package hijacking** remains a widespread and critical issue, especially in the modern crypto ecosystem where a single compromised dependency can lead to remote code execution (RCE) and potentially lead to the draining of user funds.

My goal is for **Whitehat Hackers** and **Security Teams** to use this tool to:
1.  **Secure their own infrastructure** against dependency attacks.
2.  **Hunt for vulnerabilities** in the wild to keep the ecosystem safe.

### 📂 Key Repositories
* **[supplyshark/supplyshark](https://github.com/supplyshark/supplyshark)** - The core scanning engine (Now Public).
* **[supplyshark/npm_poc](https://github.com/supplyshark/npm_poc)** - Proof-of-concept vectors used for internal testing.

---
*Built by [@haccer](https://github.com/haccer). For inquiries about the architecture or security research, please contact me directly.*
