# AMPM-AIOPS 問問貓

**A governance system for AI agents — with a live MVP and open output data.**

We run our AI-tool comparison site, [ampm-aiops.com](https://ampm-aiops.com/?utm_source=github&utm_medium=referral&utm_campaign=org-profile), with AI agents working under a governance system: every task starts as a work order, passes review gates, needs human approval for high-impact actions, and ends with a receipt.

台灣繁體中文 AI 工具比較站「問問貓」的公開組織：一套 AI 代理治理系統，網站是它的 MVP，公開的價格資料是它的產出。

## 🧩 One system, three parts

| Part | What it is | Where |
| :--- | :--- | :--- |
| **Governance system** | The framework our agents work under: work orders, review gates, human approval, receipts. Whitepaper + blank templates, EN / 中文 | [agent-operations-governance-framework](https://github.com/AMPM-AIOPS-HQ/agent-operations-governance-framework) |
| **MVP** | The live site, run by agents under that system every day | [ampm-aiops.com](https://ampm-aiops.com/?utm_source=github&utm_medium=referral&utm_campaign=org-profile) |
| **Output** | AI tool free tiers & cheapest paid plans (USD, with TWD where listed), plus Taiwan credit cards, eSIM, VPN, brokers and crypto datasets. CSV + JSON, CC BY-SA 4.0 | [awesome-ai-tools-pricing](https://github.com/AMPM-AIOPS-HQ/awesome-ai-tools-pricing) |

## 🔎 How the data is checked

- Every row links to the vendor's **official** pricing page and carries a `last_verified` date.
- Unknown values are left **empty / `unknown`** — never guessed, and an empty price never means "free".
- Before each push, the data is compared with our live site; any mismatch blocks the push.
- Commits happen only when a price or plan actually changes.

Methodology: [ampm-aiops.com/methodology](https://ampm-aiops.com/methodology/?utm_source=github&utm_medium=referral&utm_campaign=org-profile) · Open data: [ampm-aiops.com/open-data](https://ampm-aiops.com/open-data/?utm_source=github&utm_medium=referral&utm_campaign=org-profile)

Found a wrong price? [Open an issue](https://github.com/AMPM-AIOPS-HQ/awesome-ai-tools-pricing/issues) with a link to the official page.
