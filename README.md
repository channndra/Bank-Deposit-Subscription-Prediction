## Data Fields

1. **age**: Numeric value representing age.
2. **job**: Type of job (Categorical: 'admin.', 'blue-collar', 'entrepreneur', 'housemaid', 'management', 'retired', 'self-employed', 'services', 'student', 'technician', 'unemployed', 'unknown').
3. **marital**: Marital status (Categorical: 'divorced', 'married', 'single', 'unknown'; Note: 'divorced' means divorced or widowed).
4. **education**: Education level (Categorical: 'basic.4y', 'basic.6y', 'basic.9y', 'high.school', 'illiterate', 'professional.course', 'university.degree', 'unknown').
5. **default**: Has credit in default? (Categorical: 'no', 'yes', 'unknown').
6. **housing**: Has housing loan? (Categorical: 'no', 'yes', 'unknown').
7. **loan**: Has personal loan? (Categorical: 'no', 'yes', 'unknown').

### Related to Last Contact of the Current Campaign

8. **contact**: Contact communication type (Categorical: 'cellular', 'telephone').
9. **month**: Last contact month of the year (Categorical: 'jan', 'feb', 'mar', ..., 'nov', 'dec').
10. **day_of_week**: Last contact day of the week (Categorical: 'mon', 'tue', 'wed', 'thu', 'fri').
11. **duration**: Last contact duration in seconds (Numeric).

### Other Attributes

12. **campaign**: Number of contacts performed during this campaign and for this client (Numeric).
13. **pdays**: Number of days that passed by after the client was last contacted from a previous campaign (Numeric; 999 means client was not previously contacted).
14. **previous**: Number of contacts performed before this campaign and for this client (Numeric).
15. **poutcome**: Outcome of the previous marketing campaign (Categorical: 'failure', 'nonexistent', 'success').

### Social and Economic Context Attributes

16. **emp.var.rate**: Employment variation rate - quarterly indicator (Numeric).
17. **cons.price.idx**: Consumer price index - monthly indicator (Numeric).
18. **cons.conf.idx**: Consumer confidence index - monthly indicator (Numeric).
19. **euribor3m**: Euribor 3-month rate - daily indicator (Numeric).
20. **nr.employed**: Number of employees - quarterly indicator (Numeric).

### Output Variable (desired target):

21. Has the client subscribed a term deposit? (binary: '1','0')
