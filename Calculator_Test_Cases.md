# Calculator Application - Test Cases

## Test Case 1: Add two positive integers
**Severity:** Major

**Priority:** High

**Preconditions:**
Calculator app is open and on the main screen

**Test Steps:**
1. Enter 5
2. Press +
3. Enter 10
4. Press =

**Expected Result:**
Display shows 15

---
## Test Case 2: Subtract smaller number from larger
**Severity:** Major

**Priority:** Medium

**Preconditions:**
Calculator is ready to use

**Test Steps:**
1. Enter 10
2. Press -
3. Enter 5
4. Press =

**Expected Result:**
Display shows 5

---
## Test Case 3: Multiply decimal numbers
**Severity:** Major

**Priority:** Medium

**Preconditions:**
Calculator is functional

**Test Steps:**
1. Enter 2.5
2. Press ×
3. Enter 4.2
4. Press =

**Expected Result:**
Display shows 10.5

---
## Test Case 4: Divide valid numbers
**Severity:** Major

**Priority:** High

**Preconditions:**
Calculator is open

**Test Steps:**
1. Enter 20
2. Press ÷
3. Enter 5
4. Press =

**Expected Result:**
Display shows 4

---
## Test Case 5: Division by zero
**Severity:** Critical

**Priority:** High

**Preconditions:**
Calculator is ready

**Test Steps:**
1. Enter 8
2. Press ÷
3. Enter 0
4. Press =

**Expected Result:**
Display shows an error (e.g., 'Cannot divide by zero')

---
## Test Case 6: Enter non-numeric character
**Severity:** Minor

**Priority:** Low

**Preconditions:**
Calculator input screen is active

**Test Steps:**
1. Enter @

**Expected Result:**
Display shows input error or ignores the character

---
## Test Case 7: BODMAS order calculation
**Severity:** Major

**Priority:** Medium

**Preconditions:**
Calculator supports combined operations

**Test Steps:**
1. Enter 2 + 3 × 4
2. Press =

**Expected Result:**
Display shows 14

---
## Test Case 8: Subtract larger from smaller
**Severity:** Major

**Priority:** Medium

**Preconditions:**
Calculator is on main input screen

**Test Steps:**
1. Enter 5
2. Press -
3. Enter 10
4. Press =

**Expected Result:**
Display shows -5

---
## Test Case 9: Multiply any number with zero
**Severity:** Minor

**Priority:** Low

**Preconditions:**
Calculator is working

**Test Steps:**
1. Enter 25
2. Press ×
3. Enter 0
4. Press =

**Expected Result:**
Display shows 0

---
## Test Case 10: Add positive and negative number
**Severity:** Major

**Priority:** Medium

**Preconditions:**
Calculator accepts negative numbers

**Test Steps:**
1. Enter 15
2. Press +
3. Enter -5
4. Press =

**Expected Result:**
Display shows 10

---
