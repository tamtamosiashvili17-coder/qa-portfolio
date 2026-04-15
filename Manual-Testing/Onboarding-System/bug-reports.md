# 🐞 Bug Reports – Onboarding System Testing

## 🐞 Bug 1 – Sorting functionality not working

**Title:** Sorting does not work on onboarding table (Start Date / Status)

**Description:** Sorting buttons are not functioning when clicked.

**Steps to Reproduce:**
1. Open onboarding page
2. Click on sorting buttons (Start Date / Status)

**Actual Result:**
Sorting does not change.

**Expected Result:**
Table data should be sorted accordingly.


---

## 🐞 Bug 2 – Status changes despite user selecting “No”

**Title:** Status changes even when user selects “No” in confirmation popup

**Description:** System ignores user confirmation choice.

**Steps to Reproduce:**
1. Change applicant status
2. In confirmation popup, select “No”

**Actual Result:**
Status is still changed.

**Expected Result:**
Status should remain unchanged.


---

## 🐞 Bug 3 – Validation messages not localized

**Title:** Validation messages appear in English on Georgian version

**Description:** Required field validation is not translated.

**Steps to Reproduce:**
1. Switch system language to Georgian
2. Leave required fields empty
3. Submit form

**Actual Result:**
Validation messages appear in English.

**Expected Result:**
Messages should appear in Georgian.


---

## 🐞 Bug 4 – Text truncation in filter fields

**Title:** Long values are cut off in Position and Responsible Person filters

**Description:** Text is not fully visible.

**Steps to Reproduce:**
1. Open filters
2. Select Position / Responsible Person with long name

**Actual Result:**
Text is truncated.

**Expected Result:**
Full text should be visible.


---

## 🐞 Bug 5 – Confirmation popup missing on delete action

**Title:** Confirmation popup does not appear when deleting task

**Description:** System performs delete without confirmation.

**Steps to Reproduce:**
1. Click delete task

**Actual Result:**
No confirmation popup appears.

**Expected Result:**
Confirmation popup should be displayed.


---

## 🐞 Bug 6 – Onboarding popup not triggered

**Title:** Onboarding start popup does not appear after assigning hired status

**Description:** Popup is not triggered under expected conditions.

**Steps to Reproduce:**
1. Open applicant page
2. Assign “Hired” status

**Actual Result:**
Popup does not appear.

**Expected Result:**
Onboarding popup should be displayed.


---

## 🐞 Bug 7 – UI icon misalignment

**Title:** Arrow icon incorrectly placed in “New Onboarding Task” section

**Description:** UI element does not match design.

**Steps to Reproduce:**
1. Open New Onboarding Task section

**Actual Result:**
Icon is misaligned.

**Expected Result:**
Icon should match design layout.
