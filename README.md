<div align="center">

<a href="https://aerisvalidator.space/"><img src="assets/banner.svg" alt="AERIS — Weather reads itself" width="100%"></a>

<br>

[![Website](https://img.shields.io/badge/website-aerisvalidator.space-a855f7?style=flat-square&labelColor=131317)](https://aerisvalidator.space/)
[![Bridge Watch](https://img.shields.io/badge/Celestia-Bridge%20Watch-a855f7?style=flat-square&labelColor=131317)](https://aerisvalidator.space/bridge/)
[![Alert Center](https://img.shields.io/badge/Celestia-Alert%20Center-a855f7?style=flat-square&labelColor=131317)](https://aerisvalidator.space/alerts/)
[![RSS](https://img.shields.io/badge/RSS-subscribe-ffc178?style=flat-square&logo=rss&logoColor=ffc178&labelColor=131317)](https://aerisvalidator.space/alerts/api/alerts_feed.xml)
[![Contact](https://img.shields.io/badge/contact-hello%40aeris.xyz-d9b8ff?style=flat-square&labelColor=131317)](mailto:hello@aeris.xyz)

**Independent PoS validator & network-monitoring infrastructure.**<br>
Raw readings first — no forecasts, no curated stories.

</div>

---

## 📡 Live readings

<sub>Pulled straight from the Aeris public API — these numbers update themselves (every ~30 min).</sub>

<p align="center">
  <a href="https://aerisvalidator.space/bridge/"><img alt="Blobstream lag" src="https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Faerisvalidator.space%2Fbridge%2Fapi%2Fbridge_monitor.json&query=%24.blobstream.lag_blocks&label=Blobstream%20lag&suffix=%20blocks&style=for-the-badge&color=a855f7&labelColor=131317&cacheSeconds=1800"></a>
  <a href="https://aerisvalidator.space/bridge/"><img alt="Blobstream lag hours" src="https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Faerisvalidator.space%2Fbridge%2Fapi%2Fbridge_monitor.json&query=%24.blobstream.lag_estimated_hours&label=behind%20live%20chain&suffix=%20h&style=for-the-badge&color=ffc178&labelColor=131317&cacheSeconds=1800"></a>
  <br>
  <a href="https://aerisvalidator.space/bridge/"><img alt="IBC clients" src="https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Faerisvalidator.space%2Fbridge%2Fapi%2Fbridge_monitor.json&query=%24.ibc.total_clients&label=IBC%20clients%20tracked&style=for-the-badge&color=d9b8ff&labelColor=131317&cacheSeconds=1800"></a>
  <a href="https://aerisvalidator.space/bridge/"><img alt="Healthy chains" src="https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Faerisvalidator.space%2Fbridge%2Fapi%2Fbridge_monitor.json&query=%24.ibc.risk_counts_by_chain.healthy&label=chains%20healthy&style=for-the-badge&color=8fe3c0&labelColor=131317&cacheSeconds=1800"></a>
  <a href="https://aerisvalidator.space/bridge/"><img alt="Expired chains" src="https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Faerisvalidator.space%2Fbridge%2Fapi%2Fbridge_monitor.json&query=%24.ibc.risk_counts_by_chain.expired&label=chains%20expired&style=for-the-badge&color=ff8fa3&labelColor=131317&cacheSeconds=1800"></a>
  <br>
  <a href="https://aerisvalidator.space/alerts/"><img alt="Active alerts" src="https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Faerisvalidator.space%2Falerts%2Fapi%2Falerts_feed.json&query=%24.counts.total&label=active%20alerts&style=for-the-badge&color=a855f7&labelColor=131317&cacheSeconds=1800"></a>
  <a href="https://aerisvalidator.space/alerts/"><img alt="High priority alerts" src="https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Faerisvalidator.space%2Falerts%2Fapi%2Falerts_feed.json&query=%24.counts.by_severity.high&label=high%20priority&style=for-the-badge&color=ff8fa3&labelColor=131317&cacheSeconds=1800"></a>
</p>

## 🛰️ Validators

| | Network | Chain ID | Validator |
|:-:|---|---|---|
| <img src="https://www.google.com/s2/favicons?domain=zetachain.com&sz=64" width="22"> | **ZetaChain** | `zetachain mainnet` | [![Mintscan](https://img.shields.io/badge/Mintscan-stake-a855f7?style=flat-square&labelColor=131317)](https://www.mintscan.io/zeta/validators/zetavaloper1ev0vrv6hh44hx9gtkn8fyurdxl2w7fk8awztpj) <br><sub>`zetavaloper1ev0vrv6hh44hx9gtkn8fyurdxl2w7fk8awztpj`</sub> |
| <img src="https://www.google.com/s2/favicons?domain=archway.io&sz=64" width="22"> | **Archway** | `archway-1` | [![Mintscan](https://img.shields.io/badge/Mintscan-stake-a855f7?style=flat-square&labelColor=131317)](https://www.mintscan.io/archway/validators/archwayvaloper1gg6alw26gz6wld3gagz8h6p7e3nu45j7r2sgj8) <br><sub>`archwayvaloper1gg6alw26gz6wld3gagz8h6p7e3nu45j7r2sgj8`</sub> |
| <img src="https://www.google.com/s2/favicons?domain=bandprotocol.com&sz=64" width="22"> | **Band** | `laozi-mainnet` | [![ping.pub](https://img.shields.io/badge/ping.pub-stake-a855f7?style=flat-square&labelColor=131317)](https://ping.pub/band/staking/bandvaloper1vunu4v046w73sw6xvstfj77uvlevch6u3wngkh) <br><sub>`bandvaloper1vunu4v046w73sw6xvstfj77uvlevch6u3wngkh`</sub> |
| <img src="https://www.google.com/s2/favicons?domain=docs.terra.money&sz=64" width="22"> | **Terra** | `phoenix-1` | [![ping.pub](https://img.shields.io/badge/ping.pub-stake-a855f7?style=flat-square&labelColor=131317)](https://ping.pub/terra/staking/terravaloper1ev3kdmq8tgqx4e86gxnyyfsq7uwvvx7y0fts50) <br><sub>`terravaloper1ev3kdmq8tgqx4e86gxnyyfsq7uwvvx7y0fts50`</sub> |

## 🔭 How the instruments work

Every number Aeris publishes is read live from the chains themselves — no third-party dashboards in between.

```mermaid
flowchart LR
    subgraph SRC["On-chain sources"]
        C["Celestia LCD<br/>IBC clients · channels · escrow"]
        E["Ethereum mainnet<br/>SP1Blobstream · eth_call"]
        G["Celestia gov module<br/>proposals"]
        P["celestiaorg/CIPs<br/>upgrade signals"]
    end

    S(("Aeris sampler<br/>every 30 min"))

    subgraph OUT["Outputs"]
        B["🌉 Bridge & Client Watch"]
        A["🚨 Alert Center"]
        J["{ } JSON API"]
        R["RSS 2.0"]
    end

    C --> S
    E --> S
    G --> S
    P --> S
    S --> B
    S --> A
    S --> J
    J --> R
    J -.-> BOT["Telegram / Discord bots"]

    classDef src fill:#131317,stroke:#a855f7,color:#f6f3fc
    classDef core fill:#7c1ff0,stroke:#d9b8ff,color:#ffffff
    classDef out fill:#0e0e11,stroke:#8fe3c0,color:#f6f3fc
    class C,E,G,P src
    class S core
    class B,A,J,R,BOT out
```

## 🌉 Bridge & Client Watch

> **[aerisvalidator.space/bridge →](https://aerisvalidator.space/bridge/)**

Celestia has ~175 IBC light clients open to other chains plus one bridge to Ethereum. A client expires silently if nobody relays a header in time — and recovering it requires a governance vote. Bridge Watch tracks every one of them live, so a problem shows up **before** it becomes a proposal.

| Tab | What it shows |
|---|---|
| **Overview** | Chains actively bridged, chains heading toward expiry, Blobstream lag, TIA locked in live transfer channels |
| **Bridge Pulse** | Live visualization — every dot is a real counterparty chain pulsing at its risk level; particle speed follows the real Blobstream lag |
| **Chains** | IBC clients by counterparty chain: *Healthy · Watch · Critical · Expired*, % of trust window left, abandoned clients counted — not hidden |
| **Blob trend** | Blobstream lag history from Aeris's own 30-min samples, with growth-rate analysis that tells a slow relayer from a fully stalled one |
| **Recent events** | Only real risk-state transitions — no repeated noise |
| **API** | Public JSON behind everything on the page |

Blobstream height is read directly from the SP1Blobstream contract [`0x7Cf3…08fAe`](https://etherscan.io/address/0x7Cf3876F681Dbb6EdA8f6FfC45D66B996Df08fAe) on Ethereum mainnet and cross-checked against Celestia's live height.

## 🚨 Alert Center

> **[aerisvalidator.space/alerts →](https://aerisvalidator.space/alerts/)**

One merged, severity-ranked feed for Celestia — surfaced before it becomes news.

| Category | Source |
|---|---|
| 🗳️ **Governance** | On-chain proposals from Celestia's gov module |
| ⬆️ **Network upgrades** | New & updated CIPs (Celestia Improvement Proposals) |
| 🌉 **Bridge health** | IBC client / Blobstream risk transitions from Bridge Watch |

Filter by category or priority (`HIGH` · `MEDIUM` · `LOW`), or just [subscribe via RSS](https://aerisvalidator.space/alerts/api/alerts_feed.xml).

## 🔌 Public API

No key, no rate limit on our side, refreshed every 30 minutes — reuse it.

| Endpoint | Returns |
|---|---|
| [`/bridge/api/bridge_monitor.json`](https://aerisvalidator.space/bridge/api/bridge_monitor.json) | Full snapshot: IBC clients by chain, Blobstream lag + history, recent risk events |
| [`/alerts/api/alerts_feed.json`](https://aerisvalidator.space/alerts/api/alerts_feed.json) | Unified alert timeline — ready for Telegram / Discord bots |
| [`/alerts/api/alerts_feed.xml`](https://aerisvalidator.space/alerts/api/alerts_feed.xml) | Same alerts as RSS 2.0 |

```bash
# How far behind is Blobstream right now?
curl -s https://aerisvalidator.space/bridge/api/bridge_monitor.json | jq '.blobstream.lag_blocks'

# Latest high-priority alerts
curl -s https://aerisvalidator.space/alerts/api/alerts_feed.json | jq '.alerts[] | select(.severity=="high") | .title'
```

<details>
<summary><b>Example: <code>bridge_monitor.json</code> (trimmed)</b></summary>

```json
{
  "schema": "aeris.celestia.bridge_monitor.v2",
  "ibc": {
    "total_clients": 178,
    "total_chains": 47,
    "risk_counts_by_chain": { "healthy": 14, "watch": 0, "critical": 0, "expired": 33, "frozen": 0 },
    "chains": [
      {
        "chain_id": "osmosis-1",
        "client_count": 22,
        "stale_client_count": 18,
        "primary_risk": "healthy",
        "healthiest_client": {
          "client_id": "07-tendermint-10",
          "pct_remaining": 100.0
        }
      }
    ]
  },
  "blobstream": {
    "contract": "0x7Cf3876F681Dbb6EdA8f6FfC45D66B996Df08fAe",
    "relayed_celestia_height": 13814400,
    "live_celestia_height": 14923206,
    "lag_blocks": 1108806,
    "lag_estimated_hours": 1848
  },
  "recent_events": [ { "chain_id": "...", "risk_from": "healthy", "risk_to": "expired" } ]
}
```

</details>

<details>
<summary><b>Example: <code>alerts_feed.json</code> (trimmed)</b></summary>

```json
{
  "schema": "aeris.celestia.alert_center.v2",
  "counts": { "total": 32, "by_severity": { "high": 1, "medium": 19, "low": 12, "info": 0 } },
  "alerts": [
    {
      "category": "bridge_health",
      "severity": "medium",
      "kind": "risk_change",
      "title": "penumbra-1: IBC client healthy → expired"
    }
  ]
}
```

</details>

## 📜 Standing orders

<table>
<tr>
<td width="33%"><b>§01 · Custody</b><br><sub>Assets remain in verifiable custody at every step.</sub></td>
<td width="33%"><b>§02 · Continuous sampling</b><br><sub>No cached snapshot is ever presented as live.</sub></td>
<td width="33%"><b>§03 · Latency discipline</b><br><sub>Every measurement has a timestamp and margin of error.</sub></td>
</tr>
<tr>
<td><b>§04 · Signal over noise</b><br><sub>Anomalies are surfaced once, not spammed.</sub></td>
<td><b>§05 · Bearing</b><br><sub>Direction and uncertainty are stated together.</sub></td>
<td><b>§06 · Accountability</b><br><sub>Every reading is traceable to its raw sample.</sub></td>
</tr>
</table>

---

<div align="center">

**AERIS** · weather reads itself

[aerisvalidator.space](https://aerisvalidator.space/) · [hello@aeris.xyz](mailto:hello@aeris.xyz)

</div>
