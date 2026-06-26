# AS-IS Process Architecture

## Overview

This diagram represents the original manual process used to validate technology-related invoices and allocate costs across organizational cost centers.

The workflow required significant analyst intervention and depended on multiple spreadsheets, manual validations, and repetitive calculations.

---

# High-Level Process Flow

```text
Technology Service Provider
            │
            ▼
     Supplier Invoice
            │
            ▼
      Analyst Review
            │
            ▼
  Technology Inventory File
            │
            ▼
   User Assignment Review
            │
            ▼
   Cost Center Spreadsheet
            │
            ▼
 Manual Cost Allocation
            │
            ▼
 Manual Calculations
            │
            ▼
 Prefactura Preparation
            │
            ▼
 Financial Validation
```

---

# Process Description

## Step 1 – Invoice Reception

The analyst receives invoices associated with:

* Sophos Advanced Protection
* Sophos Encryption
* Sophos Email Security
* COVE Backup
* RMM Services
* Professional Services
* Leased Technology Assets

---

## Step 2 – Inventory Validation

The analyst manually reviews inventory records to identify:

* Active licenses
* Assigned users
* Active assets

---

## Step 3 – Cost Center Identification

User information is manually matched against organizational cost center records.

---

## Step 4 – Cost Allocation

Technology expenses are manually distributed among business units based on inventory ownership and allocation criteria.

---

## Step 5 – Calculation and Validation

The analyst performs manual calculations and validates totals against supplier invoices.

---

## Step 6 – Prefactura Generation

A pre-invoice document is generated for review before final validation.

---

# Challenges Identified

### Operational Challenges

* Time-consuming process.
* Multiple spreadsheet dependencies.
* Repetitive activities.

### Financial Challenges

* Allocation inaccuracies.
* Billing discrepancies.
* Manual calculations.

### Governance Challenges

* Limited traceability.
* High dependency on analyst knowledge.
* Inconsistent execution.

---

# Key Risks

| Risk                      | Impact |
| ------------------------- | ------ |
| Human Error               | High   |
| Incorrect Cost Allocation | High   |
| Billing Discrepancies     | High   |
| Inventory Inconsistencies | Medium |
| Delayed Processing        | High   |
| Limited Auditability      | Medium |

---

# Summary

The original process was functional but highly dependent on manual effort, creating operational inefficiencies and increasing the likelihood of allocation errors, reporting inconsistencies, and governance challenges.
