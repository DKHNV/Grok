# Grok DNS Maintenance Report

Generated: `2026-11-22T07:57:50Z`

## DNS lifecycle

| State | Hosts |
|---|---:|
| Active | 99 |
| Pending | 2 |
| Suspect | 2 |
| Quarantine | 13 |
| Excluded | 13 |
| Expired | 29 |

## HTTPS/TLS observation

| State | Hosts |
|---|---:|
| Alive | 49 |
| Unknown | 4 |
| Suspect | 0 |
| Dead | 46 |

## Stability window

The score is based on measured HTTPS/TLS checks within the configured calendar-day window. SKIPPED observations are excluded.

Measured hosts: **99**
Average stability: **49.5%**

## Current HTTPS/TLS failures

| Type | Hosts |
|---|---:|
| TIMEOUT | 48 |
| TLS_CERT_ERROR | 2 |

### Failure details

| Hostname | State | Since | Observations | Last error | IPv4 | Stability | Samples |
|---|---|---|---:|---|---|---:|---:|
| `ebecker.hades-api.grok-sandbox.com` | unknown | `2026-11-20T08:29:49Z` | 5 | TIMEOUT | 34.67.206.254 | 0.0 | 5 |
| `fvugwdk3.email.grok.com` | dead | `2026-08-21T10:45:25Z` | 306 | TIMEOUT | 137.22.248.76 | 0.0 | 30 |
| `gix.hades-api.grok-sandbox.com` | dead | `2026-08-21T10:45:25Z` | 306 | TLS_CERT_ERROR | 34.23.245.206 | 0.0 | 30 |
| `grok-chat.hades-api.grok-sandbox.com` | dead | `2026-08-21T10:45:25Z` | 306 | TIMEOUT | 35.245.167.101 | 0.0 | 30 |
| `grok-code-wild.hades-api.grok-sandbox.com` | dead | `2026-08-21T10:45:25Z` | 306 | TIMEOUT | 8.234.156.60 | 0.0 | 30 |
| `grok-code-xai.hades-api.grok-sandbox.com` | dead | `2026-08-21T10:45:25Z` | 306 | TIMEOUT | 34.48.102.92 | 0.0 | 30 |
| `grok-computer-wild.hades-api.grok-sandbox.com` | dead | `2026-08-21T13:09:03Z` | 305 | TIMEOUT | 34.48.178.33 | 0.0 | 30 |
| `grok-computer-xai.hades-api.grok-sandbox.com` | dead | `2026-08-21T13:09:03Z` | 305 | TIMEOUT | 34.86.77.84 | 0.0 | 30 |
| `hades-ebecker.api.gcp.grok-sandbox.com` | unknown | `2026-11-20T08:29:49Z` | 5 | TIMEOUT | 34.67.206.254 | 0.0 | 5 |
| `hades-gix.api.gcp.grok-sandbox.com` | dead | `2026-08-21T13:09:03Z` | 305 | TLS_CERT_ERROR | 34.23.245.206 | 0.0 | 30 |
| `hades-grok-chat.api.gcp.grok-sandbox.com` | dead | `2026-08-21T10:45:25Z` | 306 | TIMEOUT | 35.245.167.101 | 0.0 | 30 |
| `hades-grok-code-wild.api.gcp.grok-sandbox.com` | dead | `2026-08-21T10:45:25Z` | 306 | TIMEOUT | 8.234.156.60 | 0.0 | 30 |
| `hades-grok-code-xai.api.gcp.grok-sandbox.com` | dead | `2026-08-21T10:45:25Z` | 306 | TIMEOUT | 34.48.102.92 | 0.0 | 30 |
| `hades-grok-computer-wild.api.gcp.grok-sandbox.com` | dead | `2026-08-21T13:09:03Z` | 305 | TIMEOUT | 34.48.178.33 | 0.0 | 30 |
| `hades-grok-computer-xai.api.gcp.grok-sandbox.com` | dead | `2026-08-21T13:09:03Z` | 305 | TIMEOUT | 34.86.77.84 | 0.0 | 30 |
| `hades-ic-prod-h100.api.gcp.grok-sandbox.com` | dead | `2026-10-15T04:32:07Z` | 109 | TIMEOUT | 136.70.140.203 | 0.0 | 30 |
| `hades-iowa.api.gcp.grok-sandbox.com` | dead | `2026-08-21T13:09:03Z` | 305 | TIMEOUT | 34.67.185.15 | 0.0 | 30 |
| `hades-janetl.api.gcp.grok-sandbox.com` | dead | `2026-11-09T22:58:08Z` | 27 | TIMEOUT | 136.116.144.143 | 0.0 | 27 |
| `hades-lv.api.gcp.grok-sandbox.com` | dead | `2026-08-21T13:09:03Z` | 305 | TIMEOUT | 34.16.250.174 | 0.0 | 30 |
| `hades-mh.api.gcp.grok-sandbox.com` | dead | `2026-08-21T13:09:03Z` | 305 | TIMEOUT | 35.227.115.226 | 0.0 | 30 |
| `hades-mini.api.gcp.grok-sandbox.com` | dead | `2026-08-21T13:09:03Z` | 305 | TIMEOUT | 104.196.162.208 | 0.0 | 30 |
| `hades-nevada.api.gcp.grok-sandbox.com` | dead | `2026-08-21T13:09:03Z` | 305 | TIMEOUT | 34.125.95.100 | 0.0 | 30 |
| `hades-odyssey.api.gcp.grok-sandbox.com` | dead | `2026-08-21T18:53:47Z` | 304 | TIMEOUT | 34.86.181.21 | 0.0 | 30 |
| `hades-ohio.api.gcp.grok-sandbox.com` | dead | `2026-08-21T13:09:03Z` | 305 | TIMEOUT | 34.162.150.75 | 0.0 | 30 |
| `hades-rl.api.gcp.grok-sandbox.com` | dead | `2026-08-21T13:09:03Z` | 305 | TIMEOUT | 34.21.58.27 | 0.0 | 30 |
| `hades-rl2.api.gcp.grok-sandbox.com` | dead | `2026-08-21T13:09:03Z` | 305 | TIMEOUT | 34.138.9.57 | 0.0 | 30 |
| `hades-st.api.gcp.grok-sandbox.com` | dead | `2026-08-21T10:45:25Z` | 306 | TIMEOUT | 34.145.172.50 | 0.0 | 30 |
| `hades-tool-calling.api.gcp.grok-sandbox.com` | dead | `2026-08-21T13:09:03Z` | 305 | TIMEOUT | 35.245.67.216 | 0.0 | 30 |
| `hades-vbrowser.api.gcp.grok-sandbox.com` | dead | `2026-08-21T13:09:03Z` | 305 | TIMEOUT | 34.86.225.51 | 0.0 | 30 |
| `hades-vendor.api.gcp.grok-sandbox.com` | unknown | `2026-11-21T20:03:38Z` | 2 | TIMEOUT | 34.46.244.70 | 0.0 | 2 |
| `ic-prod-h100.hades-api.grok-sandbox.com` | dead | `2026-10-15T04:32:07Z` | 109 | TIMEOUT | 136.70.140.203 | 0.0 | 30 |
| `iowa.hades-api.grok-sandbox.com` | dead | `2026-08-21T13:09:03Z` | 305 | TIMEOUT | 34.67.185.15 | 0.0 | 30 |
| `janetl.hades-api.grok-sandbox.com` | dead | `2026-11-09T22:58:08Z` | 27 | TIMEOUT | 136.116.144.143 | 0.0 | 27 |
| `lv.hades-api.grok-sandbox.com` | dead | `2026-08-21T13:09:03Z` | 305 | TIMEOUT | 34.16.250.174 | 0.0 | 30 |
| `mh.hades-api.grok-sandbox.com` | dead | `2026-08-21T10:45:25Z` | 306 | TIMEOUT | 35.227.115.226 | 0.0 | 30 |
| `mini.hades-api.grok-sandbox.com` | dead | `2026-08-21T13:09:03Z` | 305 | TIMEOUT | 104.196.162.208 | 0.0 | 30 |
| `nevada.hades-api.grok-sandbox.com` | dead | `2026-08-21T13:09:03Z` | 305 | TIMEOUT | 34.125.95.100 | 0.0 | 30 |
| `nxat9edg.email.grok.com` | dead | `2026-08-21T10:45:25Z` | 306 | TIMEOUT | 137.22.224.203 | 0.0 | 30 |
| `odyssey.hades-api.grok-sandbox.com` | dead | `2026-08-21T18:53:47Z` | 304 | TIMEOUT | 34.86.181.21 | 0.0 | 30 |
| `ohio.hades-api.grok-sandbox.com` | dead | `2026-08-21T13:09:03Z` | 305 | TIMEOUT | 34.162.150.75 | 0.0 | 30 |
| `rl.hades-api.grok-sandbox.com` | dead | `2026-08-21T13:09:03Z` | 305 | TIMEOUT | 34.21.58.27 | 0.0 | 30 |
| `rl2.hades-api.grok-sandbox.com` | dead | `2026-08-21T13:09:03Z` | 305 | TIMEOUT | 34.138.9.57 | 0.0 | 30 |
| `sip.voice.x.ai` | dead | `2026-08-21T10:45:25Z` | 306 | TIMEOUT | 8.228.120.166 | 0.0 | 30 |
| `st.hades-api.grok-sandbox.com` | dead | `2026-08-21T10:45:25Z` | 306 | TIMEOUT | 34.145.172.50 | 0.0 | 30 |
| `tool-calling.hades-api.grok-sandbox.com` | dead | `2026-08-21T10:45:25Z` | 306 | TIMEOUT | 35.245.67.216 | 0.0 | 30 |
| `us-east-1-raw.api.x.ai` | dead | `2026-08-21T10:45:25Z` | 306 | TIMEOUT | 100.28.44.67, 13.217.184.16, 3.216.5.89 | 0.0 | 30 |
| `us-south-1-pltr.api.x.ai` | dead | `2026-08-21T10:45:25Z` | 306 | TIMEOUT | 199.16.156.221 | 0.0 | 30 |
| `us-west-1-raw.api.x.ai` | dead | `2026-08-21T10:45:25Z` | 306 | TIMEOUT | 199.16.156.218 | 0.0 | 30 |
| `vbrowser.hades-api.grok-sandbox.com` | dead | `2026-08-21T13:09:03Z` | 305 | TIMEOUT | 34.86.225.51 | 0.0 | 30 |
| `vendor.hades-api.grok-sandbox.com` | unknown | `2026-11-21T20:03:38Z` | 2 | TIMEOUT | 34.46.244.70 | 0.0 | 2 |

## Discovery

Discovery state updated: `2026-11-22T07:57:50Z`

## Notes

- Public active DNS file: `Grok_DNS`.
- DNS lifecycle is time-based and does not depend on how many times per day the workflow runs.
- Hostname policy exclusions are semantic decisions and are tracked separately from DNS quarantine.
- HTTPS/TLS health is observational and never removes a hostname from the public DNS file.
