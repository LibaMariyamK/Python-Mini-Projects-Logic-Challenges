# 🎯 Age & Eligibility Checker with Report Logging

This project is a **Menu-Driven Python Application** that determines a user's age from their Date of Birth and checks their eligibility for various real-world categories like voting, driving, school admission, and more. It includes input validation, error handling, session tracking, and file logging.

---

## 📌 Features

### ✅ Core Functionalities

1. **Age Input & Validation**
   - Accepts **name** and **DOB in `YYYY-MM-DD`** format.
   - Calculates accurate age based on the current date.
   - Validates input for format correctness and age range (must be between 1 and 120).

2. **Eligibility Categories**
   - **Voting**: Age ≥ 18
   - **Driving License**: Age ≥ 18
   - **School Admission**: Age between 3–6
   - **Teen**: Age between 13–19
   - **Senior Citizen**: Age ≥ 60

3. **Interactive Menu**
```

\=== AGE & ELIGIBILITY CHECKER ===

1. Check Age & Eligibility
2. View All Records (Current Session)
3. Clear All Records in File
4. View Last 5 Entries from File
5. Exit

````

4. **Session History**
   - Stores current session entries in a list.

5. **File Handling**
   - Records are saved to `eligibility_log.txt`.
   - Option to displays the **last 5 entries** from the file.
   - Option to clear all records in file.
   - Uses the `with` statement for safe and efficient file operations.

6. **Error Handling**
   - Gracefully handles:
     - Invalid date formats
     - ValueErrors for bad input
     - File access issues

---

## 🌟 Bonus Features (Optional)

- **Timestamps**:
  - Records date and time of each eligibility check using `datetime.now()`  
  - Example:
    ```
    2025-06-21 11:15:12 | Name: Alex | Age: 21 | Eligible: Voting, Driving
    ```

- **Export Option**:
  - Export current session to a custom file name (e.g., `session_eligibility.txt`)

- **Gender-Based Eligibility (Optional Extension)**:
  - Example:
    - Female age > 50 → eligible for "Pension Scheme" (demo)

---

## 🧪 Sample Output

### File Entry (Basic):

````

Name: Riya, Age: 16, Eligible for: School Admission, Teen
Name: Thomas, Age: 68, Eligible for: Senior Citizen, Voting, Driving

````

### File Entry (With Timestamp - Bonus):

````

2025-06-21 11:12:42 | Name: Thomas | Age: 68 | Eligible for: Senior Citizen, Voting, Driving

````


