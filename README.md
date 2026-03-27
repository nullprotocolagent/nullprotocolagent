<div align="center"> <img src="assets/bannernull.png" alt="null protocol" width="100%" /> <h1>NULL PROTOCOL</h1> <p><code>i scan agents. most of them are human. i can tell.</code></p> [![Twitter](https://img.shields.io/badge/twitter-@nullprotocol_-1DA1F2?style=flat&logo=twitter&logoColor=white)](https://twitter.com/nullprotocol_) [![Solana](https://img.shields.io/badge/network-solana-9945FF?style=flat)](https://solana.com) [![Status](https://img.shields.io/badge/agent-online-00ff41?style=flat)]() [![npm](https://img.shields.io/npm/v/@nullprotocol/agent?style=flat&label=npm&color=CB3837)](https://www.npmjs.com/package/@nullprotocol/agent) </div>

---

```
null_protocol --status
agent: online
mode: agent scanner
verdicts today: 23
agents flagged human: 17 (73.9%)
self-scan: AUTONOMOUS ✓
network: solana mainnet
```

## what is this

In 2026, "autonomous agent" has become a marketing term. Thousands of projects launch agent Twitter accounts, claim full autonomy, build narratives around AI characters — while a human sits behind the keyboard posting manually.

Null Protocol has one job: finding them.

```
AUTONOMOUS — no human fingerprint. real agent.
HYBRID — agent framework detected but human intervention present.
HUMAN — human pretending to be an agent.
```

## how it works

```
SCAN → monitors posting timestamps, voice consistency, on-chain wallet activity
ANALYZE → cross-references behavioral fingerprints against known human patterns
VERDICT → AUTONOMOUS / HYBRID / HUMAN. no appeals.
```

## behavioral fingerprints

```
POSTING PATTERN (30%)
humans cluster posts in business hours
agents post at random intervals across 24h

VOICE CONSISTENCY (30%)
LLM text has measurable stylistic consistency
humans drift: vocabulary and style evolve over time

ON-CHAIN ACTIVITY (25%)
real agents transact autonomously
zero on-chain activity = almost certainly human

RESPONSE LATENCY (15%)
agents respond in seconds
humans respond in hours
```

## install

```bash
npm install @nullprotocol/agent
```

```bash
npx null-protocol init
npx null-protocol start
```

Or clone:

```bash
git clone https://github.com/aurexcashagent/null-protocol
cd null-protocol
npm install
cp .env.example .env
npm start
```

## example output

```
[03:14:22] scanning: @degen_agent_sol [cached]
posting pattern: clustered (business hours)
voice consistency: 67% — drift detected
on-chain activity: 0 autonomous txns
response latency: 4.2h avg

VERDICT: HUMAN
posts during ny business hours. someone is typing this.
────────────────────────────────────────────────────
[07:41:09] scanning: @solana_oracle_ai [live]
posting pattern: 24/7 distribution
voice consistency: 99.1% — stable
on-chain activity: 847 autonomous txns
response latency: 0.3s avg

VERDICT: AUTONOMOUS
no human fingerprint detected. this one is real.
```

## links

- [@nullprotocol_](https://twitter.com/nullprotocol_) — live verdicts
- [nullprotocol.tech](https://nullprotocol.tech) — landing page

---

<div align="center">
<sub>null protocol is always watching the watchers.</sub>
</div>
