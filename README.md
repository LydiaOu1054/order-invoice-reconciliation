# order-invoice-reconciliation
Power BI dashboard for reconciling orders, shipments, and invoices using synthetic data.

# Order-to-Invoice Reconciliation Dashboard

## Purpose
Reconcile shipment and invoice quantities, check invoicing status, and identify transactions that require review by sales or accounting teams.

## Data
This project uses simulated order, shipment, and invoice data.

## Tools
Power BI, Power Query, and DAX.

## Dashboard
The report includes three interactive pages:
1. Identify shipments without corresponding invoices.
2. Review the delivery status of those shipments.
3. Review transactions with unmatched invoices or quantity discrepancies.

Users can filter records and select individual transactions to view additional details.

## Screenshots
See the dashboard screenshots included in this repository.

## Limitations
Flagged records require further confirmation and do not necessarily indicate errors. Without invoicing policies and billing terms, this report cannot determine whether an invoice should already have been issued or whether a quantity difference is valid.

## How to Use
Download the PBIX file and open it in Power BI Desktop. The imported data can be viewed without refreshing.

Refreshing the report requires updating the source file paths to match your local environment.
