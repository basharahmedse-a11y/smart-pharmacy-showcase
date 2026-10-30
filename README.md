# Smart Pharmacy Management System (showcase)

> Delivered as a guided graduation project; the source code is private. This repository describes what it does.

A web system for running a pharmacy that checks every drug combination at the point of sale and forecasts what to reorder.

**Status:** delivered, final polish.

## Features
- **Drug-interaction check at sale time:** every pair in the cart is checked against ~160,000 known interactions (DDInter). Dangerous combinations are blocked until the pharmacist writes a reason, and every override lands in a manager report.
- **Invoices** in USD and Yemeni rial (Sana'a and Aden rates), with QR codes and dosage notes
- **Stock:** low-stock and near-expiry alerts, catalogue import from Excel/CSV with preview
- **Forecasting:** a separate Python service predicts demand and suggests reorder quantities
- **Bridge** to the pharmacy's legacy accounting system through file import/export
- **Roles:** manager and pharmacist; accounts created by the manager only

## Delivery
- 11 sprints, each with an execution log, technical explanation and a student guide
- Deployment and operations guide, manual test protocol

## Stack
Laravel 13 · PHP 8.4 · MySQL · Python (Flask, waitress)

---
Built by **Bashar Ahmed Abdullah** · [BashX](https://YOUR-DOMAIN)
