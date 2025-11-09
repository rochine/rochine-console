# Rochine Console (Beta)

The operational dashboard for **Rochine** —  
where automation tasks, AI agents, and connected robots execute verifiable actions and submit proofs to Solana.

> 🧠 Currently in **Active Beta Stage**

---

### 🎯 Purpose
Rochine Console is the human–machine bridge for the Rochine network.  
From one interface, users can:
- Launch new tasks (manual or automated)
- Monitor active agents and hardware nodes
- Review on-chain proofs
- Track and claim earned rewards

---

### 🧩 Architecture
- **Frontend:** Next.js 14 + TailwindCSS  
- **Backend Services:** Supabase (sessions, metadata)  
- **Blockchain Layer:** Solana Devnet (programs in `rochine-lab`)  
- **Storage:** IPFS / Arweave for task proofs  
- **Realtime Layer:** WebSocket + event streaming for agent logs  

---

### ⚙️ Features
| Module | Function |
|---------|-----------|
| 🏠 **Dashboard** | Overview of active agents, modules, and proofs |
| 🧩 **Tasks** | Create and run tasks with dynamic parameters |
| 🤖 **Agents** | Manage linked robots / AI nodes |
| 🦾 **Robotics** | Control and monitor connected hardware devices |
| 💰 **Rewards** | View proof results and withdraw rewards |
| 🧾 **Proofs** | Browse verifiable records and signatures |
| ⚙️ **Settings** | Wallet connection, network, and profile |

---

### 🧠 Stack
- **Framework:** Next.js (App Router)
- **UI:** TailwindCSS + Framer Motion
- **Web3:** Solana Wallet Adapter + RPC hooks
- **Backend:** Supabase / Edge Functions
- **Storage:** IPFS / Arweave
- **Security:** Zero-Trust verification via Rochine Lab protocols

---
## Links
- Console: https://console.rochine.tech/
- Docs: https://docs.rochine.tech/
- Web:  https://www.rochine.tech/

---

### 🚀 Development
```bash
git clone https://github.com/rochine/rochine-console
cd rochine-console
npm install
npm run dev



