# BUG-ERP-001: Product Quantity Not Updating After Sales Order

**Module:** Inventory → Sales Integration  
**Severity:** High  
**Priority:** High  
**Status:** Open  
**Reported by:** [Your Name]  
**Date:** [Today's Date]  
**Environment:** Odoo 17.0 Online Demo, Chrome 120

## Steps to Reproduce
1. Login to Odoo demo
2. Go to Inventory → Products
3. Create product "Test Item" with quantity: 10
4. Go to Sales → Create new quotation
5. Add "Test Item" with quantity: 5
6. Confirm sales order
7. Go back to Inventory → Products
8. Check quantity of "Test Item"

## Expected Result
Product quantity should decrease from 10 to 5 after sales order confirmation

## Actual Result
Product quantity still shows 10 (not updated)

## Evidence
![Screenshot](../Screenshots/bug-erp-001-quantity.png)

## Impact
- Inventory data inaccurate
- Risk of overselling products
- Affects stock management and reordering

## Reproducibility
✅ 100% (tested 3 times, same result)

## Workaround
Manually update inventory quantity after each sale

## Suggested Fix
Ensure delivery order validation triggers inventory update