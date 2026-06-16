# 🏢 ERP QA Testing Project - Odoo

> Comprehensive manual testing project for enterprise ERP system covering Sales, Inventory, and CRM modules.

## 📋 Project Overview

This project demonstrates end-to-end manual QA testing of **Odoo ERP**, a leading open-source enterprise resource planning system. The testing covers critical business workflows across multiple integrated modules.

**Application:** [Odoo Online Demo](https://odoo.com/trial)  
**Testing Period:** 02/06/2026-16/06/2026 
**Tester:** H.M. Ghilmaan Shahzad

## 🎯 Objectives

- Validate core ERP functionality across Sales, Inventory, and CRM modules
- Test inter-module integration and data flow
- Identify defects in business-critical workflows
- Ensure data integrity and calculation accuracy
- Verify user experience and interface consistency

## 📦 Modules Tested

| Module | Test Cases | Coverage | Status |
|--------|-----------|----------|--------|
| **Sales** | 10 | Quotation → Order → Invoice | ✅ Complete |
| **Inventory** | 10 | Product Management → Stock → Delivery | ✅ Complete |
| **CRM** | 10 | Lead → Opportunity → Conversion | ✅ Complete |
| **Integration** | 3 | Sales ↔ Inventory Data Flow | ✅ Complete |

## 📁 Project Structure
ERP-QA-Testing-Project/
│
├── 📄 Test_Plan.md # Testing strategy and scope
├── Test_Summary.md # Execution metrics and findings
│
├── 📂 Test_Cases/
│ ├── Sales_Module.csv # 10 sales test cases
│ ├── Inventory_Module.csv # 10 inventory test cases
│ └── CRM_Module.csv # 10 CRM test cases
│
├── 📄 RTM.csv # Requirements traceability matrix
│
├── 📂 Bug_Reports/
│ ├── BUG-ERP-001.md # Inventory sync issue
│ ├── BUG-ERP-002.md # Calculation error
│ └── BUG-ERP-003.md # UI/UX issue
│
└── 📂 Screenshots/ # Visual evidence

## 🧪 Testing Approach

### Test Types
- ✅ **Functional Testing** - Feature validation
- ✅ **Integration Testing** - Multi-module workflows
- ✅ **End-to-End Testing** - Complete business processes
- ✅ **Data Validation** - Accuracy and integrity checks
- ✅ **UI/UX Testing** - Usability and consistency

### Test Techniques
- Positive and negative testing
- Boundary value analysis
- Error handling validation
- Workflow testing
- Data-driven testing

## 📊 Key Metrics

| Metric | Result |
|--------|--------|
| **Total Test Cases** | 30 |
| **Executed** | 30 (100%) |
| **Passed** | 26 (87%) |
| **Failed** | 3 (10%) |
| **Blocked** | 1 (3%) |
| **Defects Logged** | 3 |
| **Requirements Coverage** | 100% |

## 🐛 Critical Findings

### High Severity Issues
1. **BUG-ERP-001:** Inventory quantity not syncing after sales order confirmation
   - Impact: Risk of overselling, data inconsistency
   - Status: Open

2. **BUG-ERP-002:** Discount calculation rounding errors
   - Impact: Financial accuracy concerns
   - Status: Open

### Recommendations
- Fix critical integration bugs before production
- Implement automated regression tests for sales-inventory flow
- Add real-time stock validation

## 🛠️ Tools & Technologies

- **Application:** Odoo 17.0 ERP
- **Test Management:** CSV/Excel
- **Defect Tracking:** Markdown documentation
- **Browser:** Chrome 120+
- **Platform:** Odoo Online Demo

## 📈 Skills Demonstrated

✅ ERP system testing  
✅ Multi-module integration testing  
✅ Complex workflow validation  
✅ Test case design and execution  
✅ Defect management and reporting  
✅ Requirements traceability  
✅ Test documentation  
✅ Data integrity validation  

## 🚀 How to Review This Project

1. **Start with** `Test_Plan.md` - Understand scope and approach
2. **Review** `Test_Cases/` - See test design methodology
3. **Check** `RTM.csv` - Verify coverage and traceability
4. **Examine** `Bug_Reports/` - Review defect documentation quality
5. **Read** `Test_Summary.md` - Understand findings and recommendations

## 💡 Key Learnings

- ERP systems require understanding of business processes across departments
- Integration testing is critical - modules don't work in isolation
- Data integrity is paramount in enterprise systems
- Complex workflows need end-to-end validation
- Cross-module dependencies must be thoroughly tested

## 📞 Contact

**Tester:** H.M. Ghilmaan Shahzad  
**Email:** Ghilmaanshahzad@gmail.com  
**LinkedIn:** linkedin.com/in/mohammad-ghilmaan-73568311a/  
**GitHub:** https://github.com/MohammadGhilmaan?tab=repositories

---

*This project demonstrates practical QA testing skills on enterprise-level software. All testing was performed on Odoo's public demo environment.*
