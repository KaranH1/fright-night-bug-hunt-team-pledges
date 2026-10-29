# Test Cases: [Nhan N]

**Team number:** [XX]

<!--
HOW TO USE THIS FILE
1. Copy this file. Name the copy with your first name and last initial, like  maria-g.md
2. Leave TEMPLATE.md untouched for your teammates.
3. Write at least ONE failing test case. More is better.
4. Copy the block between the lines for each new test case.
5. Test IDs: use your initials plus a number, like  MG-01, MG-02. This keeps IDs unique across your team.
6. See docs/TESTING_FIELD_GUIDE.md for the sample test case TC-00.
-->

---

**Test ID:** TC-01
**Written by:** Nhan Nguyen
**Title:** Username requirements are ignored
**Traces to:** REQ-01
**Test type:** Boundary Value
**Preconditions:** Account with certain name must have not been created already
**Test data:** Username and password can just be aaaa (below the minimum requirement)

**Steps:**
1. Press log in / register
2. In the Username and password section type aaaa for both
3. Press create account

**Expected result:** Username and password needs to be unique and at least 8 letters
**Actual result:** Account created you can log in now
**Status:** Fail
**Severity:** Major 
**V or V:** Verification Fail only

---

**Test ID:** TC-02
**Written by:** Nhan Nguyen
**Title:** All API keys and admin password/username are not in an env file (public)
**Traces to:** NFR-03
**Test type:** Security
**Preconditions:** Demo loads correctly
**Test data:** API keys, admin username and password are in the source code

**Steps:**
1. Clone repo from github 
2. Open Config.js file
3. Read api keys and admin accounts

**Expected result:** Hidden inside an env file
**Actual result:** Public within source files 
**Status:** Fail
**Severity:** Critical
**V or V:** Verification

---
