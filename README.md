<div align="center">

<img src="https://raw.githubusercontent.com/mppfinance/MPPFinance/main/bannermpp.jpg" width="100%" alt="MPPFinance" />

</div>

---

<div align="center">

### MPPFinance

**Virtual Visa cards for AI agents — powered by Machine Payments Protocol**

Your agent pays via MPP → gets a virtual Visa card → spends anywhere.

[![Website](https://img.shields.io/badge/WEBSITE-mppfinance.xyz-0a0a0a?style=for-the-badge&logo=safari&logoColor=4A9EFF)](https://mppfinance.xyz)
[![Twitter](https://img.shields.io/badge/TWITTER-%40MPPFinance-0a0a0a?style=for-the-badge&logo=x&logoColor=white)](https://x.com/mppfinance)
[![npm](https://img.shields.io/npm/v/mppfinance?style=for-the-badge&label=NPM&color=0a0a0a&logoColor=CC3534&logo=npm)](https://www.npmjs.com/package/mppfinance)
[![Stars](https://img.shields.io/github/stars/mppfinance/mppfinance-sdk?style=for-the-badge&label=STARS&color=0a0a0a&logoColor=FFD700)](https://github.com/mppfinance/mppfinance-sdk)

</div>

---

```ts
import { MPPFinance } from 'mppfinance'

const card = await MPPFinance.issue({
  agentId: 'agent-7x2k',
  amount: 50_00,
  rules: { merchant: 'aws.com', singleUse: true }
})
// → card ready in 0.3s
```

---

<div align="center">

| | |
|---|---|
| 🌐 **Site** | [mppfinance.xyz](https://mppfinance.xyz) |
| 📦 **NPM** | [npmjs.com/package/mppfinance](https://www.npmjs.com/package/mppfinance) |
| 🐙 **SDK** | [github.com/mppfinance/mppfinance-sdk](https://github.com/mppfinance/mppfinance-sdk) |
| 🐦 **Twitter** | [@mppfinance](https://x.com/mppfinance) |

<br/>

`solana` &nbsp;·&nbsp; `mpp` &nbsp;·&nbsp; `ai-agents` &nbsp;·&nbsp; `virtual-cards` &nbsp;·&nbsp; `mcp`

</div>
