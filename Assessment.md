# Assessment & Information Gathering

## Step 1: Initial Assessment

### 1.1 Documentation Review
NovaCore’s existing cybersecurity documentation was collected and analyzed:
- Cybersecurity policy v1.2
- Incident response SOP
- Past penetration testing reports
- Vendor risk review forms

### 1.2 Stakeholder Interviews
We conducted structured interviews with:
- CTO (Cybersecurity Budget, Strategic Vision)
- IT Security Team Lead (Infrastructure Details)
- SOC Analysts (Incident Trends)
- GRC Manager (Policy Compliance)

### 1.3 Current Cybersecurity Posture
| Component | Status |
|-----------|--------|
| Risk Management Strategy | Ad-hoc (in development) |
| Key Asset Inventory | Incomplete |
| Security Roles Defined | Partially defined |
| Data Classification | Exists, not fully implemented |
| Logging & Monitoring | Implemented for critical systems only |

---

## Step 2: Identify and Define Scope

### 2.1 Systems in Scope
- Customer Data Platform
- Internal HRMS
- Azure Cloud Infrastructure
- GitHub CI/CD pipeline

### 2.2 Critical Data Types
- Customer PII (SSN, email, address)
- Employee records
- Transaction logs
- Source code & build secrets

---

## Step 3: High-Level Observations

- Lack of formal governance structure
- Detection capabilities exist but lack integration with response
- No formal Business Continuity Plan (BCP)
- Gaps in vendor oversight and contract language

> This foundational assessment supports our subsequent CSF mapping and tier analysis.

---

**Next**: See [`CSF_Mapping.md`](./CSF_Mapping.md) for mapping current practices to NIST CSF Core Functions.

