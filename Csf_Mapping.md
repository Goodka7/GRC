# CSF 2.0 Core Function Mapping – NovaCore Technologies

This section maps NovaCore’s current practices against the NIST Cybersecurity Framework 2.0 core functions.

## GOVERN
| Category | Pass/Fail | Notes |
|----------|-----------|-------|
| Risk Management Strategy | ❌ Fail | No formalized governance body or risk framework exists. |
| Policy Development | ✅ Pass | Security policy exists but lacks executive ownership. |
| Governance Roles & Responsibility | ❌ Fail | Cybersecurity roles not clearly assigned at exec level. |

## IDENTIFY
| Category | Pass/Fail | Notes |
|----------|-----------|-------|
| Asset Management | ❌ Fail | Partial inventory; no tagging of critical assets. |
| Risk Assessment | ✅ Pass | Conducted annually, but not tied to business impact. |
| Supply Chain Risk Management | ❌ Fail | No structured vendor risk rating. |

## PROTECT
| Category | Pass/Fail | Notes |
|----------|-----------|-------|
| Identity Management & Access Control | ✅ Pass | MFA and RBAC implemented across core systems. |
| Awareness & Training | ❌ Fail | Only annual compliance training; lacks phishing simulations. |
| Data Security | ❌ Fail | DLP not deployed. Encryption inconsistent across environments. |

## DETECT
| Category | Pass/Fail | Notes |
|----------|-----------|-------|
| Anomalies & Events | ✅ Pass | Azure Sentinel collects logs from key systems. |
| Continuous Monitoring | ❌ Fail | Limited visibility into endpoints and third-party tools. |

## RESPOND
| Category | Pass/Fail | Notes |
|----------|-----------|-------|
| Response Planning | ❌ Fail | IR plan exists but not practiced. No RACI chart. |
| Analysis & Mitigation | ✅ Pass | SOC performs triage but lacks root cause focus. |

## RECOVER
| Category | Pass/Fail | Notes |
|----------|-----------|-------|
| Recovery Planning | ❌ Fail | No Business Continuity or Disaster Recovery test performed. |
| Communications | ✅ Pass | Legal and PR teams have breach notification templates. |

---

**Next**: See [`Gap Analysis`](https://github.com/Goodka7/GRC/blob/main/Gap_Analysis.md) to view tier ratings, maturity levels, and prioritized gaps.
