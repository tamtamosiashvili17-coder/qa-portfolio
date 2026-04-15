# 🐞 Bug Reports – Hiring Manager Module Testing

## 🐞 Bug 1 – AI agent enabled for Hiring Manager

**Title:** AI agent is enabled for Hiring Manager although it should always remain disabled

**Description:** The system allows the AI agent option to remain active for Hiring Manager users, which violates the expected business rule.

**Steps to Reproduce:**
1. Open Hiring Manager related settings or profile
2. Check AI agent status

**Actual Result:**  
AI agent is enabled.

**Expected Result:**  
AI agent should always be disabled for Hiring Manager users.

---

## 🐞 Bug 2 – Comment can be added despite restricted access

**Title:** User can add comments even when access is restricted

**Description:** The system allows commenting functionality although the user has restricted access.

**Steps to Reproduce:**
1. Open candidate or related page with restricted access
2. Try to add a comment

**Actual Result:**  
Comment can be added.

**Expected Result:**  
Commenting should be blocked when access is restricted.

---

## 🐞 Bug 3 – Edit action remains blocked even when access is granted

**Title:** Edit action is blocked even after access is granted

**Description:** The system does not enable edit functionality even though user access has already been opened.

**Steps to Reproduce:**
1. Grant access to Hiring Manager
2. Open candidate actions
3. Try to use edit action

**Actual Result:**  
Edit action remains blocked.

**Expected Result:**  
Edit action should become available after access is granted.

---

## 🐞 Bug 4 – Delete document action unavailable

**Title:** Document cannot be deleted because delete button is missing

**Description:** In candidate profile, uploaded documents cannot be removed because the delete action is not visible.

**Steps to Reproduce:**
1. Open candidate profile
2. Go to uploaded documents section
3. Try to delete a document

**Actual Result:**  
Delete button is not visible.

**Expected Result:**  
Delete button should be displayed and allow document removal.

---

## 🐞 Bug 5 – Incorrect validation message when adding Hiring Manager

**Title:** Incorrect validation message appears when adding Hiring Manager

**Description:** Validation feedback does not match the actual input issue.

**Steps to Reproduce:**
1. Open Add New Hiring Manager form
2. Enter invalid or incomplete data
3. Submit the form

**Actual Result:**  
Incorrect validation message is displayed.

**Expected Result:**  
Validation message should accurately describe the input error.

---

## 🐞 Bug 6 – Success message shown after selecting “No” in resend confirmation

**Title:** Success message is displayed even when user selects “No” in resend confirmation popup

**Description:** The system shows a success message although the action is cancelled by the user.

**Steps to Reproduce:**
1. Click Resend button
2. In confirmation popup, select “No”

**Actual Result:**  
System displays a success message saying the email was sent.

**Expected Result:**  
No success message should appear because the action was cancelled.
