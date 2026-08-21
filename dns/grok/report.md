# Grok DNS Maintenance Report

Generated: `2026-08-21T10:45:25Z`

## DNS lifecycle

| State | Hosts |
|---|---:|
| Active | 61 |
| Pending | 22 |
| Suspect | 0 |
| Quarantine | 0 |
| Expired | 0 |

## HTTPS/TLS observation

| State | Hosts |
|---|---:|
| Alive | 38 |
| Unknown | 23 |
| Suspect | 0 |
| Dead | 0 |

## Stability window

The score is based on measured HTTPS/TLS checks within the configured calendar-day window. SKIPPED observations are excluded.

Measured hosts: **61**
Average stability: **62.3%**

## Current HTTPS/TLS failures

| Type | Hosts |
|---|---:|
| TIMEOUT | 23 |

### Failure details

| Hostname | State | Since | Observations | Last error | IPv4 | Stability | Samples |
|---|---|---|---:|---|---|---:|---:|
| `francischong.hades-api.grok-sandbox.com` | unknown | `2026-08-21T10:45:25Z` | 1 | TIMEOUT | 35.199.56.148 | 0.0 | 1 |
| `fvugwdk3.email.grok.com` | unknown | `2026-08-21T10:45:25Z` | 1 | TIMEOUT | 137.22.248.76 | 0.0 | 1 |
| `gix.hades-api.grok-sandbox.com` | unknown | `2026-08-21T10:45:25Z` | 1 | TIMEOUT | 34.23.245.206 | 0.0 | 1 |
| `grok-chat.hades-api.grok-sandbox.com` | unknown | `2026-08-21T10:45:25Z` | 1 | TIMEOUT | 35.245.167.101 | 0.0 | 1 |
| `grok-code-wild.hades-api.grok-sandbox.com` | unknown | `2026-08-21T10:45:25Z` | 1 | TIMEOUT | 8.234.156.60 | 0.0 | 1 |
| `grok-code-xai.hades-api.grok-sandbox.com` | unknown | `2026-08-21T10:45:25Z` | 1 | TIMEOUT | 34.48.102.92 | 0.0 | 1 |
| `hades-grok-chat.api.gcp.grok-sandbox.com` | unknown | `2026-08-21T10:45:25Z` | 1 | TIMEOUT | 35.245.167.101 | 0.0 | 1 |
| `hades-grok-code-wild.api.gcp.grok-sandbox.com` | unknown | `2026-08-21T10:45:25Z` | 1 | TIMEOUT | 8.234.156.60 | 0.0 | 1 |
| `hades-grok-code-xai.api.gcp.grok-sandbox.com` | unknown | `2026-08-21T10:45:25Z` | 1 | TIMEOUT | 34.48.102.92 | 0.0 | 1 |
| `hades-ikruk.api.gcp.grok-sandbox.com` | unknown | `2026-08-21T10:45:25Z` | 1 | TIMEOUT | 35.246.102.53 | 0.0 | 1 |
| `hades-st.api.gcp.grok-sandbox.com` | unknown | `2026-08-21T10:45:25Z` | 1 | TIMEOUT | 34.145.172.50 | 0.0 | 1 |
| `hades-staging.api.gcp.grok-sandbox.com` | unknown | `2026-08-21T10:45:25Z` | 1 | TIMEOUT | 34.150.166.149 | 0.0 | 1 |
| `ikruk.hades-api.grok-sandbox.com` | unknown | `2026-08-21T10:45:25Z` | 1 | TIMEOUT | 35.246.102.53 | 0.0 | 1 |
| `mh.hades-api.grok-sandbox.com` | unknown | `2026-08-21T10:45:25Z` | 1 | TIMEOUT | 35.227.115.226 | 0.0 | 1 |
| `nxat9edg.email.grok.com` | unknown | `2026-08-21T10:45:25Z` | 1 | TIMEOUT | 137.22.224.203 | 0.0 | 1 |
| `sip.staging.voice.x.ai` | unknown | `2026-08-21T10:45:25Z` | 1 | TIMEOUT | 34.11.90.42 | 0.0 | 1 |
| `sip.voice.x.ai` | unknown | `2026-08-21T10:45:25Z` | 1 | TIMEOUT | 8.228.120.166 | 0.0 | 1 |
| `st.hades-api.grok-sandbox.com` | unknown | `2026-08-21T10:45:25Z` | 1 | TIMEOUT | 34.145.172.50 | 0.0 | 1 |
| `staging.hades-api.grok-sandbox.com` | unknown | `2026-08-21T10:45:25Z` | 1 | TIMEOUT | 34.150.166.149 | 0.0 | 1 |
| `tool-calling.hades-api.grok-sandbox.com` | unknown | `2026-08-21T10:45:25Z` | 1 | TIMEOUT | 35.245.67.216 | 0.0 | 1 |
| `us-east-1-raw.api.x.ai` | unknown | `2026-08-21T10:45:25Z` | 1 | TIMEOUT | 100.55.179.147, 32.199.64.239, 44.214.176.4 | 0.0 | 1 |
| `us-south-1-pltr.api.x.ai` | unknown | `2026-08-21T10:45:25Z` | 1 | TIMEOUT | 199.16.156.221 | 0.0 | 1 |
| `us-west-1-raw.api.x.ai` | unknown | `2026-08-21T10:45:25Z` | 1 | TIMEOUT | 199.16.156.218 | 0.0 | 1 |

## Discovery

Discovery state updated: `2026-08-21T10:45:25Z`

## Notes

- Public active DNS file: `Grok_DNS`.
- DNS lifecycle is time-based and does not depend on how many times per day the workflow runs.
- HTTPS/TLS health is observational and never removes a hostname from the public DNS file.
