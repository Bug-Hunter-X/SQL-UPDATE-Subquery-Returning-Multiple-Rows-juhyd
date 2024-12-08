# SQL UPDATE Subquery Multiple Rows Bug

This repository demonstrates a common error in SQL: using a subquery in an UPDATE statement's SET clause that returns more than one row.  This typically leads to syntax errors or unpredictable results, depending on the database system.

The `bug.sql` file contains the erroneous SQL code. The `bugSolution.sql` file shows the corrected approach using a JOIN.