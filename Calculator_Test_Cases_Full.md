# 🧪 Calculator Application – Full Test Suite (30 Cases)

### ✅ TC001: Add two positive integers
**Preconditions:** Calculator app is open

**Test Steps:**
1. Enter 5
2. Press +
3. Enter 10
4. Press =

**Expected Results:** Display shows 15

---
### ✅ TC002: Add positive and negative integer
**Preconditions:** Calculator is on main screen

**Test Steps:**
1. Enter 15
2. Press +
3. Enter -5
4. Press =

**Expected Results:** Display shows 10

---
### ✅ TC003: Add two negative integers
**Preconditions:** Calculator ready for input

**Test Steps:**
1. Enter -3
2. Press +
3. Enter -7
4. Press =

**Expected Results:** Display shows -10

---
### ✅ TC004: Subtract smaller number from larger
**Preconditions:** Calculator is working

**Test Steps:**
1. Enter 10
2. Press -
3. Enter 5
4. Press =

**Expected Results:** Display shows 5

---
### ✅ TC005: Subtract larger from smaller
**Preconditions:** Calculator is operational

**Test Steps:**
1. Enter 5
2. Press -
3. Enter 10
4. Press =

**Expected Results:** Display shows -5

---
### ✅ TC006: Multiply two positive integers
**Preconditions:** Calculator input screen is active

**Test Steps:**
1. Enter 4
2. Press ×
3. Enter 6
4. Press =

**Expected Results:** Display shows 24

---
### ✅ TC007: Multiply by zero
**Preconditions:** Calculator app is open

**Test Steps:**
1. Enter 25
2. Press ×
3. Enter 0
4. Press =

**Expected Results:** Display shows 0

---
### ✅ TC008: Multiply negative and positive numbers
**Preconditions:** Calculator is running

**Test Steps:**
1. Enter -2
2. Press ×
3. Enter 4
4. Press =

**Expected Results:** Display shows -8

---
### ✅ TC009: Divide valid numbers
**Preconditions:** Calculator is ready

**Test Steps:**
1. Enter 20
2. Press ÷
3. Enter 5
4. Press =

**Expected Results:** Display shows 4

---
### ✅ TC010: Division by zero
**Preconditions:** Calculator is powered on

**Test Steps:**
1. Enter 8
2. Press ÷
3. Enter 0
4. Press =

**Expected Results:** Display shows error message

---
### ✅ TC011: Add two decimal numbers
**Preconditions:** Calculator supports decimals

**Test Steps:**
1. Enter 2.5
2. Press +
3. Enter 3.7
4. Press =

**Expected Results:** Display shows 6.2

---
### ✅ TC012: Subtract decimal from integer
**Preconditions:** Calculator is functional

**Test Steps:**
1. Enter 10
2. Press -
3. Enter 3.2
4. Press =

**Expected Results:** Display shows 6.8

---
### ✅ TC013: Multiply decimals
**Preconditions:** Calculator is ready

**Test Steps:**
1. Enter 2.5
2. Press ×
3. Enter 4.2
4. Press =

**Expected Results:** Display shows 10.5

---
### ✅ TC014: Divide decimal by integer
**Preconditions:** Calculator allows decimals

**Test Steps:**
1. Enter 5.5
2. Press ÷
3. Enter 2
4. Press =

**Expected Results:** Display shows 2.75

---
### ✅ TC015: Enter non-numeric character
**Preconditions:** Calculator accepts input

**Test Steps:**
1. Enter @

**Expected Results:** Display shows error or ignores character

---
### ✅ TC016: BODMAS operation with + and ×
**Preconditions:** Calculator supports order of operations

**Test Steps:**
1. Enter 2 + 3 × 4
2. Press =

**Expected Results:** Display shows 14

---
### ✅ TC017: Long expression input
**Preconditions:** Calculator supports multiple operations

**Test Steps:**
1. Enter 1 + 2 - 3 + 4 × 2 ÷ 2
2. Press =

**Expected Results:** Display shows 6

---
### ✅ TC018: Use of parentheses (if supported)
**Preconditions:** Calculator supports parentheses

**Test Steps:**
1. Enter (2 + 3) × 4
2. Press =

**Expected Results:** Display shows 20

---
### ✅ TC019: Clear button functionality
**Preconditions:** Calculator has 'C' or 'AC' button

**Test Steps:**
1. Enter 5
2. Press +
3. Press C

**Expected Results:** Clears the current input

---
### ✅ TC020: Multiple equals press
**Preconditions:** Calculator supports repeated '='

**Test Steps:**
1. Enter 2
2. Press +
3. Enter 2
4. Press =
5. Press = again

**Expected Results:** Display shows 6

---
### ✅ TC021: Max digits allowed in input
**Preconditions:** Calculator has input limit

**Test Steps:**
1. Enter 9999999999

**Expected Results:** Display shows all digits or gives error after limit

---
### ✅ TC022: Float rounding precision
**Preconditions:** Calculator supports floating point

**Test Steps:**
1. Enter 10 ÷ 3
2. Press =

**Expected Results:** Display shows 3.333... (based on precision)

---
### ✅ TC023: Use of backspace during input
**Preconditions:** Backspace/delete key is present

**Test Steps:**
1. Enter 123
2. Press backspace

**Expected Results:** Display shows 12

---
### ✅ TC024: Multiple operators pressed
**Preconditions:** Calculator app is running

**Test Steps:**
1. Enter 5
2. Press +
3. Press + again
4. Enter 3
5. Press =

**Expected Results:** Ignores second + or throws error

---
### ✅ TC025: Divide by a negative number
**Preconditions:** Calculator supports negative values

**Test Steps:**
1. Enter 20
2. Press ÷
3. Enter -5
4. Press =

**Expected Results:** Display shows -4

---
### ✅ TC026: Invalid expression format
**Preconditions:** Calculator parses expressions

**Test Steps:**
1. Enter + 5 - 2
2. Press =

**Expected Results:** Error or ignores invalid sequence

---
### ✅ TC027: Leading zeros in input
**Preconditions:** Calculator is working

**Test Steps:**
1. Enter 00023
2. Press +
3. Enter 07
4. Press =

**Expected Results:** Display shows 30

---
### ✅ TC028: Pressing operator after result
**Preconditions:** Result is already calculated

**Test Steps:**
1. Enter 5 + 5 =
2. Press +
3. Enter 10
4. Press =

**Expected Results:** Display shows 20

---
### ✅ TC029: Zero as first input
**Preconditions:** Calculator is ready

**Test Steps:**
1. Enter 0
2. Press +
3. Enter 5
4. Press =

**Expected Results:** Display shows 5

---
### ✅ TC030: Press equals without expression
**Preconditions:** Calculator is idle

**Test Steps:**
1. Press =

**Expected Results:** Display shows 0 or no action

---
