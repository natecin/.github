# Welcome to NATECIN: Where Your Digital Legacy Lives On

NATECIN is an **automated blockchain-based inheritance vault** designed to ensure your digital assets never fade into silence. Your wealth, effort, and legacy deserve continuity—not disappearance.

By leveraging smart contracts and scheduled automation checks (via GitHub Actions or backend cron jobs), NATECIN automatically transfers digital assets to your chosen heir once wallet inactivity surpasses a predefined threshold.

> *“When your final breath fades, your legacy begins.”*

---

## ✨ Key Features

* **Automated Inheritance Vault** — Your assets are securely locked and transferred upon inactivity.
* **Scheduled Activity Tracking** — Wallet activity timestamps are monitored via automated jobs.
* **Trustless Execution** — No notaries, no middlemen, no human intervention.
* **Maximum Security** — No sharing of seed phrases or private keys.

---

## 🧠 How NATECIN Works

**Silence = Inactivity → Inactivity = Legacy Execution**

1. Owner connects wallet and creates a vault
2. Chooses an heir and sets inactivity period (e.g., 90 days)
3. Any login or transaction updates `lastActiveTimestamp`
4. GitHub Automation routinely checks for wallet activity
5. Once inactivity threshold is reached → contract triggers inheritance transfer

---

## 🟣 System Flowchart (GitHub Automation Version)



## 🛠 Tech Stack

* Solidity Smart Contracts
* GitHub Automation / Cron Jobs
* Ethereum & EVM-Compatible Networks
* ERC-20 / ERC-721 / ERC-1155 Standards

---

## 📜 License

MIT License
