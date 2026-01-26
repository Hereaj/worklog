# Week 32 (January 19–January 25, 2026)

## Overview
- Bypassed payment features for check/ACH and online options, upgraded the catalog image upload experience, separated storage by environment for media and invoices, refactored redundant catalog/vendor day/payment code, completed the login recovery flow, and refined vendor day status automation plus delivery-to-payment alignment.

## Day-by-Day Summary
- **Mon:** Off.
- **Tue:** Bypassed the payment feature with check/ACH and online payment options.
- **Wed:** Enhanced the catalog frontend with an Amazon-style image upload flow.
- **Thu:** Separated app storage for images, PDFs, and invoices between production and development environments.
- **Fri:** Refactored and unified redundant catalog, vendor day, and payment logic across `/components` and `/app`, and finished the login recovery flow (forgot password and find password).
- **Sat:**
  - Objectives: add time-based automation management for vendor day and stronger status control tied to time and user action.
  - Solutions: let retailer users mark "confirmed" or "modified" instances as "completed"; if they do not, automatically switch them to "completed" after the end time passes; unify the "rejected" status into "canceled" and remove "rejected".
- **Sun:** Enhanced the payment flow by creating a delivery, updating the payment instance for the delivery, and syncing the payment status to the delivery status with a 1:1 mapping for new instances (falling back to the legacy flow for older deliveries).
