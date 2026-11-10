# Grok DNS Maintenance Report

Generated: `2026-11-10T20:26:49Z`

## DNS lifecycle

| State | Hosts |
|---|---:|
| Active | 93 |
| Pending | 1 |
| Suspect | 4 |
| Quarantine | 23 |
| Excluded | 13 |
| Expired | 14 |

## HTTPS/TLS observation

| State | Hosts |
|---|---:|
| Alive | 48 |
| Unknown | 2 |
| Suspect | 0 |
| Dead | 44 |

## Stability window

The score is based on measured HTTPS/TLS checks within the configured calendar-day window. SKIPPED observations are excluded.

Measured hosts: **94**
Average stability: **51.1%**

## Current HTTPS/TLS failures

| Type | Hosts |
|---|---:|
| TIMEOUT | 44 |
| TLS_CERT_ERROR | 2 |

### Failure details

| Hostname | State | Since | Observations | Last error | IPv4 | Stability | Samples |
|---|---|---|---:|---|---|---:|---:|
| `fvugwdk3.email.grok.com` | dead | `2026-08-21T10:45:25Z` | 282 | TIMEOUT | 137.22.248.76 | 0.0 | 36 |
| `gix.hades-api.grok-sandbox.com` | dead | `2026-08-21T10:45:25Z` | 282 | TLS_CERT_ERROR | 34.23.245.206 | 0.0 | 36 |
| `grok-chat.hades-api.grok-sandbox.com` | dead | `2026-08-21T10:45:25Z` | 282 | TIMEOUT | 35.245.167.101 | 0.0 | 36 |
| `grok-code-wild.hades-api.grok-sandbox.com` | dead | `2026-08-21T10:45:25Z` | 282 | TIMEOUT | 8.234.156.60 | 0.0 | 36 |
| `grok-code-xai.hades-api.grok-sandbox.com` | dead | `2026-08-21T10:45:25Z` | 282 | TIMEOUT | 34.48.102.92 | 0.0 | 36 |
| `grok-computer-wild.hades-api.grok-sandbox.com` | dead | `2026-08-21T13:09:03Z` | 281 | TIMEOUT | 34.48.178.33 | 0.0 | 36 |
| `grok-computer-xai.hades-api.grok-sandbox.com` | dead | `2026-08-21T13:09:03Z` | 281 | TIMEOUT | 34.86.77.84 | 0.0 | 36 |
| `hades-gix.api.gcp.grok-sandbox.com` | dead | `2026-08-21T13:09:03Z` | 281 | TLS_CERT_ERROR | 34.23.245.206 | 0.0 | 36 |
| `hades-grok-chat.api.gcp.grok-sandbox.com` | dead | `2026-08-21T10:45:25Z` | 282 | TIMEOUT | 35.245.167.101 | 0.0 | 36 |
| `hades-grok-code-wild.api.gcp.grok-sandbox.com` | dead | `2026-08-21T10:45:25Z` | 282 | TIMEOUT | 8.234.156.60 | 0.0 | 36 |
| `hades-grok-code-xai.api.gcp.grok-sandbox.com` | dead | `2026-08-21T10:45:25Z` | 282 | TIMEOUT | 34.48.102.92 | 0.0 | 36 |
| `hades-grok-computer-wild.api.gcp.grok-sandbox.com` | dead | `2026-08-21T13:09:03Z` | 281 | TIMEOUT | 34.48.178.33 | 0.0 | 36 |
| `hades-grok-computer-xai.api.gcp.grok-sandbox.com` | dead | `2026-08-21T13:09:03Z` | 281 | TIMEOUT | 34.86.77.84 | 0.0 | 36 |
| `hades-ic-prod-h100.api.gcp.grok-sandbox.com` | dead | `2026-10-15T04:32:07Z` | 85 | TIMEOUT | 136.70.140.203 | 0.0 | 36 |
| `hades-iowa.api.gcp.grok-sandbox.com` | dead | `2026-08-21T13:09:03Z` | 281 | TIMEOUT | 34.67.185.15 | 0.0 | 36 |
| `hades-janetl.api.gcp.grok-sandbox.com` | unknown | `2026-11-09T22:58:08Z` | 3 | TIMEOUT | 136.116.144.143 | 0.0 | 3 |
| `hades-lv.api.gcp.grok-sandbox.com` | dead | `2026-08-21T13:09:03Z` | 281 | TIMEOUT | 34.16.250.174 | 0.0 | 36 |
| `hades-mh.api.gcp.grok-sandbox.com` | dead | `2026-08-21T13:09:03Z` | 281 | TIMEOUT | 35.227.115.226 | 0.0 | 36 |
| `hades-mini.api.gcp.grok-sandbox.com` | dead | `2026-08-21T13:09:03Z` | 281 | TIMEOUT | 104.196.162.208 | 0.0 | 36 |
| `hades-nevada.api.gcp.grok-sandbox.com` | dead | `2026-08-21T13:09:03Z` | 281 | TIMEOUT | 34.125.95.100 | 0.0 | 36 |
| `hades-odyssey.api.gcp.grok-sandbox.com` | dead | `2026-08-21T18:53:47Z` | 280 | TIMEOUT | 34.86.181.21 | 0.0 | 36 |
| `hades-ohio.api.gcp.grok-sandbox.com` | dead | `2026-08-21T13:09:03Z` | 281 | TIMEOUT | 34.162.150.75 | 0.0 | 36 |
| `hades-rl.api.gcp.grok-sandbox.com` | dead | `2026-08-21T13:09:03Z` | 281 | TIMEOUT | 34.21.58.27 | 0.0 | 36 |
| `hades-rl2.api.gcp.grok-sandbox.com` | dead | `2026-08-21T13:09:03Z` | 281 | TIMEOUT | 34.138.9.57 | 0.0 | 36 |
| `hades-st.api.gcp.grok-sandbox.com` | dead | `2026-08-21T10:45:25Z` | 282 | TIMEOUT | 34.145.172.50 | 0.0 | 36 |
| `hades-tool-calling.api.gcp.grok-sandbox.com` | dead | `2026-08-21T13:09:03Z` | 281 | TIMEOUT | 35.245.67.216 | 0.0 | 36 |
| `hades-vbrowser.api.gcp.grok-sandbox.com` | dead | `2026-08-21T13:09:03Z` | 281 | TIMEOUT | 34.86.225.51 | 0.0 | 36 |
| `ic-prod-h100.hades-api.grok-sandbox.com` | dead | `2026-10-15T04:32:07Z` | 85 | TIMEOUT | 136.70.140.203 | 0.0 | 36 |
| `iowa.hades-api.grok-sandbox.com` | dead | `2026-08-21T13:09:03Z` | 281 | TIMEOUT | 34.67.185.15 | 0.0 | 36 |
| `janetl.hades-api.grok-sandbox.com` | unknown | `2026-11-09T22:58:08Z` | 3 | TIMEOUT | 136.116.144.143 | 0.0 | 3 |
| `lv.hades-api.grok-sandbox.com` | dead | `2026-08-21T13:09:03Z` | 281 | TIMEOUT | 34.16.250.174 | 0.0 | 36 |
| `mh.hades-api.grok-sandbox.com` | dead | `2026-08-21T10:45:25Z` | 282 | TIMEOUT | 35.227.115.226 | 0.0 | 36 |
| `mini.hades-api.grok-sandbox.com` | dead | `2026-08-21T13:09:03Z` | 281 | TIMEOUT | 104.196.162.208 | 0.0 | 36 |
| `nevada.hades-api.grok-sandbox.com` | dead | `2026-08-21T13:09:03Z` | 281 | TIMEOUT | 34.125.95.100 | 0.0 | 36 |
| `nxat9edg.email.grok.com` | dead | `2026-08-21T10:45:25Z` | 282 | TIMEOUT | 137.22.224.203 | 0.0 | 36 |
| `odyssey.hades-api.grok-sandbox.com` | dead | `2026-08-21T18:53:47Z` | 280 | TIMEOUT | 34.86.181.21 | 0.0 | 36 |
| `ohio.hades-api.grok-sandbox.com` | dead | `2026-08-21T13:09:03Z` | 281 | TIMEOUT | 34.162.150.75 | 0.0 | 36 |
| `rl.hades-api.grok-sandbox.com` | dead | `2026-08-21T13:09:03Z` | 281 | TIMEOUT | 34.21.58.27 | 0.0 | 36 |
| `rl2.hades-api.grok-sandbox.com` | dead | `2026-08-21T13:09:03Z` | 281 | TIMEOUT | 34.138.9.57 | 0.0 | 36 |
| `sip.voice.x.ai` | dead | `2026-08-21T10:45:25Z` | 282 | TIMEOUT | 8.228.120.166 | 0.0 | 36 |
| `st.hades-api.grok-sandbox.com` | dead | `2026-08-21T10:45:25Z` | 282 | TIMEOUT | 34.145.172.50 | 0.0 | 36 |
| `tool-calling.hades-api.grok-sandbox.com` | dead | `2026-08-21T10:45:25Z` | 282 | TIMEOUT | 35.245.67.216 | 0.0 | 36 |
| `us-east-1-raw.api.x.ai` | dead | `2026-08-21T10:45:25Z` | 282 | TIMEOUT | 100.28.44.67, 52.3.15.34, 54.205.173.184 | 0.0 | 36 |
| `us-south-1-pltr.api.x.ai` | dead | `2026-08-21T10:45:25Z` | 282 | TIMEOUT | 199.16.156.221 | 0.0 | 36 |
| `us-west-1-raw.api.x.ai` | dead | `2026-08-21T10:45:25Z` | 282 | TIMEOUT | 199.16.156.218 | 0.0 | 36 |
| `vbrowser.hades-api.grok-sandbox.com` | dead | `2026-08-21T13:09:03Z` | 281 | TIMEOUT | 34.86.225.51 | 0.0 | 36 |

## Discovery

Discovery state updated: `2026-11-10T20:26:49Z`

## Notes

- Public active DNS file: `Grok_DNS`.
- DNS lifecycle is time-based and does not depend on how many times per day the workflow runs.
- Hostname policy exclusions are semantic decisions and are tracked separately from DNS quarantine.
- HTTPS/TLS health is observational and never removes a hostname from the public DNS file.
