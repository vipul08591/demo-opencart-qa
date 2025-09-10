# Test Plan – Demo OpenCart eCommerce

**Project:** Demo OpenCart eCommerce  
**QA Engineer:** Vipul  
**Date:** 2025-09-10  

---

## 1. Introduction

This test plan outlines the testing strategy for the Demo OpenCart eCommerce site. The purpose is to ensure that the website functions correctly, provides a seamless user experience, and meets the quality standards for eCommerce operations.  

---

## 2. Objectives

- Verify the functional correctness of the OpenCart demo site.  
- Identify and report bugs, errors, and inconsistencies.  
- Ensure usability and responsiveness across devices.  
- Validate core workflows: product search, cart, checkout, and admin operations.  
- Provide a reference for future QA activities on similar projects.  

---

## 3. Scope

### In Scope
- Product catalog (listing, details, images).  
- Shopping cart functionality.  
- Checkout process and order placement.  
- User registration and login.  
- Admin panel operations (add/edit/delete products).  
- Search and filter functionalities.  
- UI/UX testing on desktop and mobile.  

### Out of Scope
- Payment gateway integration (if not available in demo).  
- Third-party plugin testing (unless included in demo).  
- Load or performance testing.  

---

## 4. Test Strategy

- **Manual Testing:** All primary workflows will be manually tested.  
- **Exploratory Testing:** Random navigation and edge-case scenarios will be explored.  
- **Regression Testing:** Re-testing critical workflows after bug fixes.  
- **Cross-Browser Testing:** Testing on Chrome, Firefox, and Edge.  
- **Responsive Testing:** Testing on mobile and tablet screens.  

---

## 5. Test Environment

- **Local Environment:** Apache / XAMPP, PHP 7.x+, MySQL 5.x+  
- **Browsers:** Chrome (latest), Firefox (latest), Edge (latest)  
- **Devices:** Desktop, Laptop, Mobile (iOS and Android)  
- **Tools:**  
  - Postman (if APIs are tested)  
  - Browser DevTools (for debugging UI issues)  
  - Markdown for documentation and GitHub for reporting  

---

## 6. Test Items

- Home page and navigation menu  
- Product categories and product pages  
- Product search and filter  
- Shopping cart and checkout process  
- User login, registration, and password recovery  
- Newsletter subscription  
- Admin panel functionalities (product management, order management)  
- Currency switcher  
- Responsiveness and layout  

---

## 7. Test Approach

1. **Identify test scenarios** for each module.  
2. **Create test cases** with detailed steps and expected results.  
3. **Execute test cases** in the test environment.  
4. **Log defects** with severity and reproducible steps.  
5. **Retest** after fixes and verify resolved defects.  
6. **Compile QA report** summarizing test results, defect counts, and observations.  

---

## 8. Roles and Responsibilities

- **QA Engineer (Vipul):**  
  - Prepare test plan, test cases, and test data  
  - Execute tests and log defects  
  - Retest resolved issues  
  - Generate QA summary report  

- **Developer / Admin:**  
  - Provide access to the demo OpenCart site and admin panel  
  - Fix defects reported by QA  

---

## 9. Deliverables

- Test Plan (`Test_Plan.md`)  
- Test Cases (`Test_Cases.md`)  
- Bug Reports (`bug-reports.md`)  
- Test Data (sample users/products)  
- QA Summary Report (`QA_Report.md`)  

---

## 10. Entry and Exit Criteria

**Entry Criteria:**  
- Demo OpenCart site is deployed locally or on a test server.  
- Test environment is configured with required software.  
- Test data is prepared and ready.  

**Exit Criteria:**  
- All planned test cases executed.  
- All critical and high severity bugs reported.  
- QA summary report completed and reviewed.  

---

## 11. Risks and Mitigation

| Risk | Impact | Mitigation |
|------|--------|------------|
| Missing test data | Medium | Prepare sample users/products in advance |
| Demo site downtime | High | Maintain backup copy and local deployment |
| Browser incompatibility | Medium | Test on multiple browsers and note issues |
| Time constraints | High | Prioritize critical workflows and regressions |

---

## 12. Approval

- QA Engineer: Vipul  
- Date: 2025-09-10  

---

*End of Test Plan*
