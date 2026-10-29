# Test Cases: Sidharth Nair
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

**Test ID:** SN-01
**Written by:** Sidharth Nair
**Title:** Votes boundary <0
**Traces to:**  app/app.js/app.js -->  Line 128
**Test type:**Integration
**Preconditions:**There must be a costume preexisting in the webapp, you must not have used all of your votes beforehand. If that is the case, reset the demo.
**Test data:** Navigate to the "Vote" heading, then use all of your votes. You will notice that you are only stopped from voting once your votes hit -1, 

**Steps:**
1. Navigate to "vote" heading, ensuring there are preexisting example costumes and you have not used all of your votes
2. Click "vote" on whichever costume you like until the system prevents you from voting.
3. Notice that the system stops you at -1 votes remaining, not 0 votes remaining.

**Expected result:** Votes remaining: 0
**Actual result:** Votes remaining: -1
**Status:** Fail
**Severity:** Minor, though everyone is granted an extra vote, EVERYONE is granted that extra vote, keeping the same results as if the system is not broken.
**V or V:** Verification, you are building the correct system, but building incorrectly.

---

**Test ID:**
**Written by:**
**Title:**
**Traces to:**
**Test type:**
**Preconditions:**
**Test data:**

**Steps:**
1.
2.
3.

**Expected result:**
**Actual result:**
**Status:**
**Severity:**
**V or V:**

---
