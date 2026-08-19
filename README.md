# KANAD Extracted Datasets: India Code & Ministry Hierarchy

This repository contains the structured datasets extracted, normalized, and reconciled from India Code (`https://www.indiacode.nic.in/`).

## Repository Structure

```text
KANADFiles/
├── README.md
├── india_code/
│   ├── manifests/
│   │   ├── india_code_master_manifest.csv    # Complete Inventory manifest (79,000+ legal documents)
│   │   └── all_india_code_pdfs.csv            # Bitstream and PDF document inventory
│   └── reports/
│       └── live_progress.md                   # Real-time crawl progress counters
└── ministries/
    ├── manifests/
    │   └── ministry_department_hierarchy.csv # Complete Ministry -> Department mapping with document counts
    └── reports/
        ├── ministry_coverage.csv             # Coverage metrics per Ministry (135 Ministries)
        ├── department_coverage.csv           # Coverage metrics per Department (1,101 Departments)
        ├── ministry_reconciliation.csv       # Reconciliation log for unassigned/orphan entities
        └── ministry_department_report.md     # Summary statistics report
```

## Dataset Summary

- **Total Source Records**: 79,200+
- **Ministries Discovered**: 135
- **Departments Discovered**: 1,101
- **Documents Assigned to Ministry**: 74,414
- **Documents Assigned to Department**: 65,234
