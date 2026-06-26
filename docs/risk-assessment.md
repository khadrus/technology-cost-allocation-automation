# Risk Assessment

## Overview

Before automation, the technology cost allocation process relied heavily on manual activities, spreadsheet manipulation, and analyst interpretation.

This assessment identifies the primary risks associated with the original process and the controls introduced through automation.

---

# Risk Assessment Matrix

| Risk ID | Risk Description                            | Likelihood (Before) | Impact (Before) | Risk Level (Before) | Mitigation Implemented                    | Residual Risk |
| ------- | ------------------------------------------- | ------------------- | --------------- | ------------------- | ----------------------------------------- | ------------- |
| R-01    | Incorrect cost allocation to business units | High                | High            | High                | Automated allocation logic                | Low           |
| R-02    | Human calculation errors                    | High                | Medium          | High                | Automated calculations                    | Low           |
| R-03    | Billing discrepancies                       | Medium              | High            | High                | Automated validation and reconciliation   | Low           |
| R-04    | Inconsistent inventory information          | Medium              | High            | High                | Data consolidation and standardization    | Medium        |
| R-05    | Delayed invoice validation                  | High                | Medium          | High                | Automated processing workflow             | Low           |
| R-06    | Missing asset assignments                   | Medium              | Medium          | Medium              | Automated matching and exception handling | Low           |
| R-07    | Lack of traceability                        | Medium              | High            | High                | Consolidated reporting and audit support  | Low           |
| R-08    | Dependency on individual knowledge          | High                | Medium          | High                | Standardized and repeatable process       | Low           |

---

# Risk Analysis

## R-01 Incorrect Cost Allocation

### Description

Technology-related expenses could be assigned to the wrong cost center due to manual review and interpretation.

### Potential Impact

* Financial inaccuracies.
* Budget distortions.
* Incorrect departmental chargebacks.

### Mitigation

Automated allocation based on predefined relationships between users, assets, and cost centers.

---

## R-02 Human Calculation Errors

### Description

Manual calculations increased the probability of mathematical errors during invoice processing.

### Potential Impact

* Incorrect invoice validation.
* Cost distribution errors.
* Rework and investigation efforts.

### Mitigation

Automated allocation calculations performed by VBA logic.

---

## R-03 Billing Discrepancies

### Description

Differences between supplier invoices and internal allocations could remain undetected.

### Potential Impact

* Overbilling.
* Financial losses.
* Vendor disputes.

### Mitigation

Automated pre-invoice generation and allocation validation.

---

## R-04 Inconsistent Inventory Information

### Description

Technology inventories maintained in different sources could contain discrepancies.

### Potential Impact

* Incorrect license allocation.
* Missing assets.
* Inaccurate reporting.

### Mitigation

Centralized consolidation of inventory information and standardization controls.

---

## R-05 Delayed Invoice Validation

### Description

Manual processing required significant analyst effort and extended review cycles.

### Potential Impact

* Delayed approvals.
* Delayed payments.
* Operational inefficiencies.

### Mitigation

Automation reduced processing time from approximately 60 minutes to 10 minutes.

---

## R-06 Missing Asset Assignments

### Description

Assets or licenses without valid ownership information could remain unassigned.

### Potential Impact

* Cost allocation gaps.
* Incomplete reporting.
* Governance issues.

### Mitigation

Default allocation rules and exception handling mechanisms.

---

## R-07 Lack of Traceability

### Description

Manual processes limited the ability to track allocation decisions and review historical records.

### Potential Impact

* Audit challenges.
* Reduced transparency.
* Increased investigation time.

### Mitigation

Automated reporting and consolidated allocation outputs.

---

## R-08 Dependency on Individual Knowledge

### Description

The process relied heavily on analyst experience and undocumented operational knowledge.

### Potential Impact

* Operational disruption.
* Knowledge loss.
* Inconsistent execution.

### Mitigation

Standardized automation workflow and documented allocation methodology.

---

# Governance Benefits

The implementation contributed to:

* Improved operational governance.
* Enhanced financial transparency.
* Stronger allocation controls.
* Increased process repeatability.
* Better support for audit and compliance activities.

---

# Overall Risk Reduction

The automation significantly reduced operational and financial risks associated with technology cost allocation activities while improving control effectiveness and process consistency.
