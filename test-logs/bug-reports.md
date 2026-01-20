# Bug Reports – StageLink QA Audit

This document contains documented issues identified during manual Quality Assurance testing of the StageLink web platform.  
Each bug includes severity classification, reproduction steps, and expected versus actual behavior.

---

## BUG-01: Mobile Navigation Menu Overlaps Content

**Severity:** High  
**Environment:** Mobile (iPhone 14 Pro Max – Chrome DevTools)

### Steps to Reproduce
1. Open StageLink in mobile view.
2. Tap the hamburger menu icon.
3. Attempt to navigate through menu options.

### Expected Result
Navigation menu should open cleanly without blocking or overlapping page content.

### Actual Result
Menu overlaps content, causing difficulty in navigation and poor user experience.

### Impact
Affects mobile usability and may prevent users from accessing key features.

---

## BUG-02: Favorites Button Placement Causes User Confusion

**Severity:** Medium  
**Environment:** Desktop – Chrome

### Steps to Reproduce
1. Log in as an audience user.
2. Browse available events.
3. Attempt to locate the Favorites feature.

### Expected Result
Favorites option should be easily discoverable and accessible.

### Actual Result
Favorites button placement is not intuitive, leading to user confusion.

### Impact
Reduces usability and may discourage user engagement.

---

## BUG-03: Password Validation Rules Not Clearly Communicated

**Severity:** Medium  
**Environment:** Desktop – Chrome

### Steps to Reproduce
1. Attempt to create a new account.
2. Enter a password that does not meet requirements.
3. Submit the registration form.

### Expected Result
Clear password requirements should be displayed before submission.

### Actual Result
Password requirements are unclear, resulting in failed submissions without proper guidance.

### Impact
Increases user friction during account creation.

---

## BUG-04: Inconsistent Button Styling Across Pages

**Severity:** Low  
**Environment:** Desktop and Mobile – Chrome

### Steps to Reproduce
1. Navigate through different pages of the platform.
2. Observe action buttons such as "Submit", "Next", or "Confirm".

### Expected Result
Buttons should follow consistent styling across all pages.

### Actual Result
Button styles vary between pages, affecting visual consistency.

### Impact
Impacts UI consistency but does not block functionality.

---

## 📝 Notes

All issues were identified through manual exploratory and functional testing.  
Severity levels were assigned based on user impact and business risk.
