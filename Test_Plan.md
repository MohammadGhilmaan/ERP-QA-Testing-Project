# Test Plan: Odoo ERP System

**Project:** ERP QA Testing Practice  
**Application:** Odoo Online Demo (https://odoo.com)  
**Tester:** Ghilmaan Shahzad  
**Date:** 16-06-2026  
**Version:** Odoo 17.0 (Demo)

## 1\. Objective

Validate core ERP modules (Sales, Inventory, CRM) for functionality, data integrity, and inter-module integration.

## 2\. Scope

### ✅ In Scope:

* **Sales Module:** Quotation → Order → Invoice flow
* **Inventory Module:** Product creation, stock management, delivery
* **CRM Module:** Lead management, opportunity tracking
* **User Management:** Login, roles, permissions
* **Integration:** Sales → Inventory data flow
* **Reports:** Sales reports, inventory reports

### ❌ Out of Scope:

* Accounting module (requires paid plan)
* Manufacturing module
* Performance testing
* Security penetration testing
* Mobile app testing

## 3\. Test Approach

* Manual functional testing
* End-to-end workflow testing
* Integration testing between modules
* Data validation
* UI/UX consistency checks

## 4\. Test Environment

* **Application:** Odoo Online Demo
* **Browser:** Chrome 120+
* **OS:** Windows 10/11
* **Access:** Demo credentials provided by Odoo

## 5\. Entry Criteria

* \[ ] Odoo demo instance active
* \[ ] Login credentials received
* \[ ] All modules accessible
* \[ ] Test data prepared

## 6\. Exit Criteria

* \[ ] 100% planned test cases executed
* \[ ] ≥90% pass rate
* \[ ] All Critical/High bugs documented
* \[ ] Test summary report completed
* \[ ] RTM updated with coverage

## 7\. Deliverables

* Test Plan
* Test Cases (3 modules)
* Requirements Traceability Matrix (RTM)
* Bug Reports with evidence
* Test Summary Report
* GitHub repository

## 8\. Risks \& Mitigation

|Risk|Mitigation|
|-|-|
|Demo expires|Complete testing within 24 hours|
|Limited features|Focus on available modules only|
|No database access|Test via UI only, validate visible data|

## 9\. Schedule

* Day 1: Setup, Test Planning, Sales Module Testing
* Day 2: Inventory \& CRM Testing, Bug Logging, Documentation

