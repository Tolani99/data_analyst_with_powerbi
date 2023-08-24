Steps Involved
1. In the Business Establishment by Age table, create a new measure
called Employees per Firm, as the sum of Number of Employees divided by the sum ofNumber of Firms.
2. Create a quick measure
  - Use Average per category as the Calculation the sum of Number of employees
    from Business Establishment by Age as the Base value, and Establishment age 
    code from Establishment Age Code as the Category.
  - Call this new measure
    Average Number of Employees by Age

3. Create a new page called Jobs
   - Add a Table visual, with the following columns:
     Geographic Area Name, Year, Employees per Firm and Average Number of 
     Employees by Age from the Business Establihsment by Age table
