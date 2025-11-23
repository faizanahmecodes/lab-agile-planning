---
name: User Story
about: This is for user stories
title: ''
labels: ''
assignees: ''

---

**As a** *registered user*
**I need** *to log in to the system using my email and password*
**So that** *I can access my personalized dashboard and services*

---

### **Details and Assumptions**

* The user already has a registered account.
* The login requires a valid email and password.
* Incorrect credentials will show an error message.
* System must be available 24/7.
* Password should be stored securely (hashed).

---

### **Acceptance Criteria**

```gherkin
Given the user is on the login page
When the user enters a valid email and valid password
Then the system should log the user in and redirect to the dashboard
```
