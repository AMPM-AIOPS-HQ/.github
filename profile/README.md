# AMPM-AIOPS 問問貓

Open, source-cited pricing data for AI tools — maintained by [ampm-aiops.com](https://ampm-aiops.com/?utm_source=github&utm_medium=referral&utm_campaign=org-profile), a Traditional-Chinese AI tool comparison site for Taiwan.

台灣繁體中文 AI 工具比較站「問問貓」的公開資料組織。每一筆價格都附官方來源網址與查核日。

## 📦 Repositories

| Repo | What it is |
| :--- | :--- |
| [awesome-ai-tools-pricing](https://github.com/AMPM-AIOPS-HQ/awesome-ai-tools-pricing) | AI tool free tiers & cheapest paid plans (USD, with TWD where listed), plus Taiwan credit cards, eSIM, VPN, brokers and crypto datasets. CSV + JSON, CC BY-SA 4.0. |

## 🔎 How the data is checked

- Every row links to the vendor's **official** pricing page and carries a `last_verified` date.
- Unknown values are left **empty / `unknown`** — never guessed, and an empty price never means "free".
- Before each push, the data is compared with our live site; any mismatch blocks the push.
- Commits happen only when a price or plan actually changes.

Methodology: [ampm-aiops.com/methodology](https://ampm-aiops.com/methodology/?utm_source=github&utm_medium=referral&utm_campaign=org-profile) · Open data: [ampm-aiops.com/open-data](https://ampm-aiops.com/open-data/?utm_source=github&utm_medium=referral&utm_campaign=org-profile)

Found a wrong price? [Open an issue](https://github.com/AMPM-AIOPS-HQ/awesome-ai-tools-pricing/issues) with a link to the official page.
