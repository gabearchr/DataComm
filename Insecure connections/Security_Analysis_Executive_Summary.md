# Insecure Connections - Customer Prioritization Summary

## Repository Overview
- **Repository:** gabearchr/DataComm
- **Analysis Date:** June 2, 2026
- **Focus Area:** FTP Customer Migration Prioritization

---

## Executive Summary

This document prioritizes external customers using insecure FTP connections for migration to secure protocols (SFTP/FTPS). The prioritization framework evaluates risk level, compliance exposure, and business impact to determine migration sequence.

### Data Sources Analyzed

| File Name | Size | Purpose |
|-----------|------|---------|
| Active FTP external customer DCR.xlsx | 364 KB | Document Control Record for external customer FTP connections - PRIMARY SOURCE FOR CUSTOMER PRIORITIZATION |
| EXPD host FTP active account full list.xlsx | 16 KB | Internal FTP account inventory (secondary priority) |

---

## Customer Prioritization Framework

### Tier 1: CRITICAL (Migrate 0-30 days)
**Characteristics:**
- Regulated industries (Finance, Healthcare, Government)
- PII or sensitive personal data
- High transaction volume or business-critical processes
- Existing compliance audit findings
- Customer contracts with specific security requirements

**Action:** Immediate customer contact and migration planning

### Tier 2: HIGH (Migrate 30-90 days)
**Characteristics:**
- Moderate data sensitivity (internal confidential, operational data)
- Medium transaction volume
- Upcoming compliance deadlines (within 6 months)
- Industry standards require encryption (e.g., retail, manufacturing)

**Action:** Develop detailed migration plans and test SFTP infrastructure

### Tier 3: MEDIUM (Migrate 90-180 days)
**Characteristics:**
- Non-critical data transfers
- Low transaction volume
- No immediate compliance requirements
- Legacy integrations with limited business impact

**Action:** Schedule migration in planned maintenance windows

---

## Migration Priority Factors

| Factor | Weight | Assessment Criteria |
|--------|--------|---------------------|
| **Regulatory Compliance** | 35% | HIPAA, PCI-DSS, SOC2, GDPR, FINRA requirements |
| **Data Sensitivity** | 25% | PII, financial data, trade secrets, confidential info |
| **Business Criticality** | 20% | Transaction volume, revenue impact, operational dependency |
| **Contractual Requirements** | 15% | SLA terms, security clauses, audit requirements |
| **Technical Complexity** | 5% | System integration complexity, migration effort |

---

## Required Information for Customer Prioritization

To complete the prioritization analysis, we need to extract the following from **Active FTP external customer DCR.xlsx**:

### Customer Data Fields Needed:
- [ ] Customer Name/ID
- [ ] Industry Sector
- [ ] Data Classification (Public/Internal/Confidential/Restricted)
- [ ] PII Indicator (Yes/No)
- [ ] Annual Transaction Volume
- [ ] Business Criticality Rating
- [ ] Regulatory Compliance Requirements
- [ ] Contract Security Terms
- [ ] Last Security Audit Date
- [ ] Known Compliance Violations

---

## Recommended Next Steps

### Phase 1: Data Extraction (Days 1-5)
1. **Extract customer data** from Active FTP external customer DCR.xlsx
2. **Classify each customer** by industry and data type
3. **Identify compliance requirements** for each customer
4. **Score customers** using prioritization framework

### Phase 2: Customer Ranking (Days 5-7)
1. **Apply weighting formula** to determine priority score
2. **Group customers** into Tier 1, 2, and 3
3. **Create migration timeline** with specific dates
4. **Assign owners** for each customer migration

### Phase 3: Execution Planning (Days 7-14)
1. **Tier 1 Customers:** Schedule immediate customer kickoff meetings
2. **Tier 2 Customers:** Develop SFTP infrastructure and testing plan
3. **Tier 3 Customers:** Add to quarterly migration schedule

---

## Key Metrics to Track

| Metric | Target | Frequency |
|--------|--------|-----------|
| Customers Migrated | 100% | Monthly |
| FTP Connections Eliminated | 100% by 180 days | Monthly |
| Compliance Violations Resolved | 100% | Monthly |
| Migration Success Rate | >95% | Per migration |
| Average Migration Time per Customer | <7 days | Per migration |

---

## Risk Mitigation

**For Tier 1 Customers (High-Risk):**
- Establish escalation procedures with executive stakeholder
- Plan 24/7 support during migration windows
- Conduct pre-migration compliance audit
- Schedule post-migration verification

**For Tier 2 Customers (Medium-Risk):**
- Coordinate with operations team for system changes
- Plan testing with sample data before production cutover
- Establish rollback procedures

**For Tier 3 Customers (Low-Risk):**
- Schedule during maintenance windows
- Use standard migration playbook
- Monitor for issues post-migration

---

## Critical Success Factors

1. **Executive Sponsorship:** Secure C-level support for migration initiative
2. **Customer Communication:** Clear, transparent messaging about timeline and support
3. **Technical Readiness:** SFTP infrastructure tested and operational before customer migrations
4. **Team Coordination:** Dedicated migration team with clear ownership
5. **Compliance Alignment:** Legal/Compliance review of all customer requirements

---

## Deliverables

This prioritization framework requires the actual customer data from **Active FTP external customer DCR.xlsx** to be populated. Once extracted, the following will be created:

- [ ] **Prioritized Customer List** (with risk scores)
- [ ] **Migration Timeline** (with specific dates per customer)
- [ ] **Customer Communication Plan** (with talking points)
- [ ] **Technical Migration Runbook** (with SFTP implementation steps)
- [ ] **Executive Dashboard** (tracking migration progress)

---

**Document Created:** June 2, 2026  
**Status:** Framework Ready - Awaiting Customer Data Extraction  
**Next Action:** Extract and classify customers from DCR spreadsheet
