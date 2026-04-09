## 📌 Project: Calculator Testing 

**Module:** Basic Arithmetic Operations  
**Author:** ANKITA GUPTA  
**Date:** 09/04/2026  

---

# Calculator Test Cases

## TC-01: Addition of two numbers
- Test Case ID: TC-01
- Description: Verify addition of two numbers
- Preconditions: Calculator is open
- Test Steps:
  1. Enter 2
  2. Press +
  3. Enter 3
  4. Press =
- Expected Result: Result should be 5

---

## TC-02: Multiplication of numbers
- Test Case ID: TC-02
- Description: Verify multiplication operation
- Preconditions: Calculator is open
- Test Steps:
  1. Enter 4
  2. Press ×
  3. Enter 5
  4. Press =
- Expected Result: Result should be 20

---

## TC-03: Subtraction of numbers
- Test Case ID: TC-03
- Description: Verify subtraction operation
- Preconditions: Calculator is open
- Test Steps:
  1. Enter 10
  2. Press -
  3. Enter 4
  4. Press =
- Expected Result: Result should be 6

---

## TC-04: Division of numbers
- Test Case ID: TC-04
- Description: Verify division operation
- Preconditions: Calculator is open
- Test Steps:
  1. Enter 8
  2. Press ÷
  3. Enter 2
  4. Press =
- Expected Result: Result should be 4

---

## TC-05: Decimal addition
- Test Case ID: TC-05
- Description: Verify decimal number addition
- Preconditions: Calculator is open
- Test Steps:
  1. Enter 2.5
  2. Press +
  3. Enter 1.5
  4. Press =
- Expected Result: Result should be 4.0

---

## TC-06: Negative number handling
- Test Case ID: TC-06
- Description: Verify calculation with negative numbers
- Preconditions: Calculator is open
- Test Steps:
  1. Enter -5
  2. Press +
  3. Enter 3
  4. Press =
- Expected Result: Result should be -2

---

## TC-07: Division by zero
- Test Case ID: TC-07
- Description: Verify division by zero
- Preconditions: Calculator is open
- Test Steps:
  1. Enter 5
  2. Press ÷
  3. Enter 0
  4. Press =
- Expected Result: Error message should be displayed

---

## TC-08: Multiple operations (BODMAS)
- Test Case ID: TC-08
- Description: Verify operator precedence
- Preconditions: Calculator is open
- Test Steps:
  1. Enter 2 + 3 × 2
  2. Press =
- Expected Result: Result should be 8

---

## TC-09: Clear button (CE)
- Test Case ID: TC-09
- Description: Verify clear function
- Preconditions: Calculator has input
- Test Steps:
  1. Enter 123
  2. Press CE
- Expected Result: Display resets to 0

---

## TC-10: Backspace button
- Test Case ID: TC-10
- Description: Verify backspace functionality
- Preconditions: Calculator has input
- Test Steps:
  1. Enter 123
  2. Press ←
- Expected Result: Last digit removed (12)

---

## TC-11: Multiple operator clicks
- Test Case ID: TC-11
- Description: Verify behavior on multiple operator inputs
- Preconditions: Calculator is open
- Test Steps:
  1. Enter 5
  2. Press + + +
  3. Enter 3
  4. Press =
- Expected Result: System should ignore extra operators or show error

---

## TC-12: Equal without input
- Test Case ID: TC-12
- Description: Press equal without entering values
- Preconditions: Calculator is open
- Test Steps:
  1. Press =
- Expected Result: Should show 0 or no change

---

## TC-13: Large number calculation
- Test Case ID: TC-13
- Description: Verify large number handling
- Preconditions: Calculator is open
- Test Steps:
  1. Enter 999999
  2. Press +
  3. Enter 1
  4. Press =
- Expected Result: Result should be 1000000

---

## TC-14: Percentage function
- Test Case ID: TC-14
- Description: Verify percentage calculation
- Preconditions: Calculator is open
- Test Steps:
  1. Enter 50
  2. Press %
- Expected Result: Result should be 0.5

---

## TC-15: Continuous calculation
- Test Case ID: TC-15
- Description: Verify continuous operations
- Preconditions: Calculator is open
- Test Steps:
  1. Enter 2 + 3
  2. Press =
  3. Press + 2
  4. Press =
- Expected Result: Result should be 7
