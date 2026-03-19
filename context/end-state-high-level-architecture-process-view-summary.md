# End State High Level Architecture (Process View)

## Purpose
Target process and application landscape for end-state SAP architecture.

## Core Systems
- S/4HANA (core ERP)
- MDG (master data governance)
- Ariba (procurement)
- Adobe Commerce (frontend)

## Key Integrations
- Adobe Commerce → S/4HANA : Customer orders
- Ariba → MDG : Supplier data
- MDG → S/4HANA : Master data distribution

## Data Domains
- Customer
- Supplier
- Product
- Pricing
- Finance
- Order
- Inventory

## Architecture Pattern
- Likely point-to-point integrations
- No clearly defined central integration layer

## Key Observations
- Multiple integration paths across systems
- No standardised integration architecture
- Data ownership unclear across domains

## Risks / Gaps
- Duplicate data flows across systems
- Lack of governance and ownership
- Potential inconsistency in master data

## KDD Relevance
- Impacted areas: Master Data, Integration, Process Ownership
- Missing KDDs: Integration standards, data ownership model
- Ownership gaps: unclear accountability across domains

## Notes for Leadership (VP Level)
- Current architecture shows fragmentation and lack of standardisation
- Risk of data inconsistency and duplication across regions
- Requires central integration strategy and governance model


- 