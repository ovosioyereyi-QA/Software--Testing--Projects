# Bug Report

## Bug ID
BUG-002

## Title
Products with zero stock remain available for purchase.

## Module
Product Listing

## Severity
High

## Priority
High

## Environment
- Application: Web
- Browser: Google Chrome
- Operating System: Windows 11

## Preconditions
- A product has a stock quantity of 0.

## Steps to Reproduce
1. Open the application.
2. Navigate to the product listing page.
3. Locate a product with zero stock.
4. Observe the product availability.

## Expected Result
Products with zero stock should display **Out of Stock** or be unavailable for purchase.

## Actual Result
Products with zero stock remain available, allowing customers to attempt a purchase.

## Impact
Customers may attempt to purchase unavailable products, leading to failed orders and a poor user experience.

## Status
Open

## Reported By
Ovosi Oyereyi
