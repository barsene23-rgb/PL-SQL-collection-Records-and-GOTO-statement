# PL-SQL-collection-Records-and-GOTO-statement
## Business Problem
Our company needs an automated system to calculate monthly attendance bonuses for employees. Currently, HR manually reviews attendance records and calculates bonuses, which is time-consuming and error-prone.

🎯 System Requirements
The system must:

Process multiple employees simultaneously
Track daily attendance for each employee (Present/Absent)
Calculate bonuses based on attendance performance:

Perfect Attendance (0 absences) → $500 bonus
Good Attendance (1-2 absences) → $300 bonus
Average Attendance (3-5 absences) → $100 bonus
Poor Attendance (6+ absences) → No bonus


Handle special cases such as critical absences that require immediate attention


💡 PL/SQL Features Utilized
Collections

Store multiple days of attendance data for each employee
Use nested tables or VARRAYs to manage daily attendance records

Records

Create custom data structures to group related employee information
Combine employee ID, name, absence count, and bonus amount in a single unit

GOTO Statements

Skip processing for employees with poor attendance
Jump to special handling routines for critical cases
Control flow for exception scenarios
