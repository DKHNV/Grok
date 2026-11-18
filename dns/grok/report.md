# Grok DNS Maintenance Report

Generated: `2026-11-18T21:23:23Z`

## DNS lifecycle

| State | Hosts |
|---|---:|
| Active | 94 |
| Pending | 2 |
| Suspect | 2 |
| Quarantine | 19 |
| Excluded | 13 |
| Expired | 23 |

## HTTPS/TLS observation

| State | Hosts |
|---|---:|
| Alive | 48 |
| Unknown | 0 |
| Suspect | 0 |
| Dead | 46 |

## Stability window

The score is based on measured HTTPS/TLS checks within the configured calendar-day window. SKIPPED observations are excluded.

Measured hosts: **94**
Average stability: **51.0%**

## Current HTTPS/TLS failures

| Type | Hosts |
|---|---:|
| TIMEOUT | 44 |
| TLS_CERT_ERROR | 2 |

### Failure details

| Hostname | State | Since | Observations | Last error | IPv4 | Stability | Samples |
|---|---|---|---:|---|---|---:|---:|
| `fvugwdk3.email.grok.com` | dead | `2026-08-21T10:45:25Z` | 299 | TIMEOUT | 137.22.248.76 | 0.0 | 31 |
| `gix.hades-api.grok-sandbox.com` | dead | `2026-08-21T10:45:25Z` | 299 | TLS_CERT_ERROR | 34.23.245.206 | 0.0 | 31 |
| `grok-chat.hades-api.grok-sandbox.com` | dead | `2026-08-21T10:45:25Z` | 299 | TIMEOUT | 35.245.167.101 | 0.0 | 31 |
| `grok-code-wild.hades-api.grok-sandbox.com` | dead | `2026-08-21T10:45:25Z` | 299 | TIMEOUT | 8.234.156.60 | 0.0 | 31 |
| `grok-code-xai.hades-api.grok-sandbox.com` | dead | `2026-08-21T10:45:25Z` | 299 | TIMEOUT | 34.48.102.92 | 0.0 | 31 |
| `grok-computer-wild.hades-api.grok-sandbox.com` | dead | `2026-08-21T13:09:03Z` | 298 | TIMEOUT | 34.48.178.33 | 0.0 | 31 |
| `grok-computer-xai.hades-api.grok-sandbox.com` | dead | `2026-08-21T13:09:03Z` | 298 | TIMEOUT | 34.86.77.84 | 0.0 | 31 |
| `hades-gix.api.gcp.grok-sandbox.com` | dead | `2026-08-21T13:09:03Z` | 298 | TLS_CERT_ERROR | 34.23.245.206 | 0.0 | 31 |
| `hades-grok-chat.api.gcp.grok-sandbox.com` | dead | `2026-08-21T10:45:25Z` | 299 | TIMEOUT | 35.245.167.101 | 0.0 | 31 |
| `hades-grok-code-wild.api.gcp.grok-sandbox.com` | dead | `2026-08-21T10:45:25Z` | 299 | TIMEOUT | 8.234.156.60 | 0.0 | 31 |
| `hades-grok-code-xai.api.gcp.grok-sandbox.com` | dead | `2026-08-21T10:45:25Z` | 299 | TIMEOUT | 34.48.102.92 | 0.0 | 31 |
| `hades-grok-computer-wild.api.gcp.grok-sandbox.com` | dead | `2026-08-21T13:09:03Z` | 298 | TIMEOUT | 34.48.178.33 | 0.0 | 31 |
| `hades-grok-computer-xai.api.gcp.grok-sandbox.com` | dead | `2026-08-21T13:09:03Z` | 298 | TIMEOUT | 34.86.77.84 | 0.0 | 31 |
| `hades-ic-prod-h100.api.gcp.grok-sandbox.com` | dead | `2026-10-15T04:32:07Z` | 102 | TIMEOUT | 136.70.140.203 | 0.0 | 31 |
| `hades-iowa.api.gcp.grok-sandbox.com` | dead | `2026-08-21T13:09:03Z` | 298 | TIMEOUT | 34.67.185.15 | 0.0 | 31 |
| `hades-janetl.api.gcp.grok-sandbox.com` | dead | `2026-11-09T22:58:08Z` | 20 | TIMEOUT | 136.116.144.143 | 0.0 | 20 |
| `hades-lv.api.gcp.grok-sandbox.com` | dead | `2026-08-21T13:09:03Z` | 298 | TIMEOUT | 34.16.250.174 | 0.0 | 31 |
| `hades-mh.api.gcp.grok-sandbox.com` | dead | `2026-08-21T13:09:03Z` | 298 | TIMEOUT | 35.227.115.226 | 0.0 | 31 |
| `hades-mini.api.gcp.grok-sandbox.com` | dead | `2026-08-21T13:09:03Z` | 298 | TIMEOUT | 104.196.162.208 | 0.0 | 31 |
| `hades-nevada.api.gcp.grok-sandbox.com` | dead | `2026-08-21T13:09:03Z` | 298 | TIMEOUT | 34.125.95.100 | 0.0 | 31 |
| `hades-odyssey.api.gcp.grok-sandbox.com` | dead | `2026-08-21T18:53:47Z` | 297 | TIMEOUT | 34.86.181.21 | 0.0 | 31 |
| `hades-ohio.api.gcp.grok-sandbox.com` | dead | `2026-08-21T13:09:03Z` | 298 | TIMEOUT | 34.162.150.75 | 0.0 | 31 |
| `hades-rl.api.gcp.grok-sandbox.com` | dead | `2026-08-21T13:09:03Z` | 298 | TIMEOUT | 34.21.58.27 | 0.0 | 31 |
| `hades-rl2.api.gcp.grok-sandbox.com` | dead | `2026-08-21T13:09:03Z` | 298 | TIMEOUT | 34.138.9.57 | 0.0 | 31 |
| `hades-st.api.gcp.grok-sandbox.com` | dead | `2026-08-21T10:45:25Z` | 299 | TIMEOUT | 34.145.172.50 | 0.0 | 31 |
| `hades-tool-calling.api.gcp.grok-sandbox.com` | dead | `2026-08-21T13:09:03Z` | 298 | TIMEOUT | 35.245.67.216 | 0.0 | 31 |
| `hades-vbrowser.api.gcp.grok-sandbox.com` | dead | `2026-08-21T13:09:03Z` | 298 | TIMEOUT | 34.86.225.51 | 0.0 | 31 |
| `ic-prod-h100.hades-api.grok-sandbox.com` | dead | `2026-10-15T04:32:07Z` | 102 | TIMEOUT | 136.70.140.203 | 0.0 | 31 |
| `iowa.hades-api.grok-sandbox.com` | dead | `2026-08-21T13:09:03Z` | 298 | TIMEOUT | 34.67.185.15 | 0.0 | 31 |
| `janetl.hades-api.grok-sandbox.com` | dead | `2026-11-09T22:58:08Z` | 20 | TIMEOUT | 136.116.144.143 | 0.0 | 20 |
| `lv.hades-api.grok-sandbox.com` | dead | `2026-08-21T13:09:03Z` | 298 | TIMEOUT | 34.16.250.174 | 0.0 | 31 |
| `mh.hades-api.grok-sandbox.com` | dead | `2026-08-21T10:45:25Z` | 299 | TIMEOUT | 35.227.115.226 | 0.0 | 31 |
| `mini.hades-api.grok-sandbox.com` | dead | `2026-08-21T13:09:03Z` | 298 | TIMEOUT | 104.196.162.208 | 0.0 | 31 |
| `nevada.hades-api.grok-sandbox.com` | dead | `2026-08-21T13:09:03Z` | 298 | TIMEOUT | 34.125.95.100 | 0.0 | 31 |
| `nxat9edg.email.grok.com` | dead | `2026-08-21T10:45:25Z` | 299 | TIMEOUT | 137.22.224.203 | 0.0 | 31 |
| `odyssey.hades-api.grok-sandbox.com` | dead | `2026-08-21T18:53:47Z` | 297 | TIMEOUT | 34.86.181.21 | 0.0 | 31 |
| `ohio.hades-api.grok-sandbox.com` | dead | `2026-08-21T13:09:03Z` | 298 | TIMEOUT | 34.162.150.75 | 0.0 | 31 |
| `rl.hades-api.grok-sandbox.com` | dead | `2026-08-21T13:09:03Z` | 298 | TIMEOUT | 34.21.58.27 | 0.0 | 31 |
| `rl2.hades-api.grok-sandbox.com` | dead | `2026-08-21T13:09:03Z` | 298 | TIMEOUT | 34.138.9.57 | 0.0 | 31 |
| `sip.voice.x.ai` | dead | `2026-08-21T10:45:25Z` | 299 | TIMEOUT | 8.228.120.166 | 0.0 | 31 |
| `st.hades-api.grok-sandbox.com` | dead | `2026-08-21T10:45:25Z` | 299 | TIMEOUT | 34.145.172.50 | 0.0 | 31 |
| `tool-calling.hades-api.grok-sandbox.com` | dead | `2026-08-21T10:45:25Z` | 299 | TIMEOUT | 35.245.67.216 | 0.0 | 31 |
| `us-east-1-raw.api.x.ai` | dead | `2026-08-21T10:45:25Z` | 299 | TIMEOUT | 100.28.44.67, 3.216.5.89, 52.3.15.34 | 0.0 | 31 |
| `us-south-1-pltr.api.x.ai` | dead | `2026-08-21T10:45:25Z` | 299 | TIMEOUT | 199.16.156.221 | 0.0 | 31 |
| `us-west-1-raw.api.x.ai` | dead | `2026-08-21T10:45:25Z` | 299 | TIMEOUT | 199.16.156.218 | 0.0 | 31 |
| `vbrowser.hades-api.grok-sandbox.com` | dead | `2026-08-21T13:09:03Z` | 298 | TIMEOUT | 34.86.225.51 | 0.0 | 31 |

## Discovery

Discovery state updated: `2026-11-18T21:23:23Z`

## Notes

- Public active DNS file: `Grok_DNS`.
- DNS lifecycle is time-based and does not depend on how many times per day the workflow runs.
- Hostname policy exclusions are semantic decisions and are tracked separately from DNS quarantine.
- HTTPS/TLS health is observational and never removes a hostname from the public DNS file.
