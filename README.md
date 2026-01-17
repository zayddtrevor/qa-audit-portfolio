# qa-audit-portfolio
A Quality Assurance (QA) portfolio featuring end-to-end functional testing, detailed bug reporting, and comprehensive test case suites for web applications.

# ISP Customer Portal – QA Test Plan

## 1. Project Overview
This test plan documents the Quality Assurance (QA) strategy for an **ISP Customer Portal**.  
The portal allows customers to log in, view billing information, and submit technical support requests.

The goal of this test plan is to ensure the system is **functional, user-friendly, responsive, and stable** across multiple environments.

---

## 2. Testing Scope

### In-Scope Testing
- Functional Testing
  - Login authentication
  - Billing access and payment actions
  - Technical support ticket submission
- UI/UX Testing
  - Button visibility and usability
  - Form input clarity
  - Error message display
- Responsiveness Testing
  - Desktop (Laptop/PC)
  - Mobile (Android screen sizes)

### Out-of-Scope Testing
- Backend load testing
- Security penetration testing
- Payment gateway integration testing

---

## 3. Test Environment

| Component | Details |
|--------|--------|
| Operating Systems | Windows 11 |
| Browsers | Google Chrome, Mozilla Firefox |
| Mobile Devices | Android (Chrome) |
| Network | Standard broadband connection |

---

## 4. Tools Used
- **Chrome DevTools** – UI inspection, responsiveness, and console error checking
- **Lighthouse** – Performance and accessibility evaluation
- **Manual Testing** – Functional and exploratory testing

---

## 5. Test Case Matrix

| Test Case ID | Feature | Test Steps | Expected Result | Status |
|------------|--------|-----------|----------------|--------|
| TC-01 | Login | Enter valid username and password → Click Login | User is redirected to dashboard | Pass |
| TC-02 | Login Validation | Enter valid username and invalid password | Error message displayed | Pass |
| TC-03 | Support Ticket | Submit a ticket with issue type "No Connection" | Ticket submitted successfully | Pass |
| TC-04 | Billing | Click "Pay Bill" button | User redirected to payment page | Pass |
| TC-05 | Mobile UI | Open portal on Android screen | Layout adjusts correctly | Pass |
| TC-06 | Form Validation | Submit empty support form | Error message displayed | Fail |
| TC-07 | Mobile Billing | Tap "Pay Bill" on mobile | Button is clickable | Fail |

---

## 6. Test Summary
- Majority of core features function as expected.
- Issues identified include form validation gaps and mobile responsiveness defects.
- Bug reports are documented separately for tracking and resolution.

---

## 7. Conclusion
The ISP Customer Portal meets functional requirements but requires improvements in **mobile responsiveness** and **input validation**.  
These findings will help guide future development and QA cycles.
