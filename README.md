<div align="center">
  <img src="https://raw.githubusercontent.com/mppfinance/mppfinance-sdk/main/assets/banner.png" width="72" alt="MPPFinance" />

  <br/>

  ```
  building infrastructure for autonomous agents
  ```

</div>

---

<div align="center">

### MPPFinance

**Virtual Visa cards for AI agents — powered by Machine Payments Protocol**

Your agent pays via MPP → gets a virtual Visa card → spends anywhere.

[![npm](https://img.shields.io/npm/v/mppfinance?color=white&label=npm%20install%20mppfinance&style=flat-square)](https://www.npmjs.com/package/mppfinance)
[![GitHub](https://img.shields.io/github/stars/nullprotocolagent/mppfinance-sdk?color=white&style=flat-square)](https://github.com/nullprotocolagent/mppfinance-sdk)

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
| 🌐 **Site** | [mppfinance.xyz](https://v0-mppf-inance-landing-page.vercel.app) |
| 📦 **NPM** | [npmjs.com/package/mppfinance](https://www.npmjs.com/package/mppfinance) |
| 🐙 **SDK** | [github.com/nullprotocolagent/mppfinance-sdk](https://github.com/nullprotocolagent/mppfinance-sdk) |
| 🐦 **Twitter** | [@mppfinance](https://x.com/mppfinance) |

<br/>

`solana` &nbsp;·&nbsp; `mpp` &nbsp;·&nbsp; `ai-agents` &nbsp;·&nbsp; `virtual-cards` &nbsp;·&nbsp; `mcp`

</div>
