# Lab 2

1. Create an empty project
2. Define data type (typescript interface) for student record with the following fields: firstName, lastName, personalNumber, GPA(optional), status (can be active, suspended, or terminated)
3. Define data type (typescript interface) for lecturer record with the following fields: firstName, lastName, personalNumber, position (can be professor, associate professor, or invited lecturer
4. Refactor existing interfaces to reduce code duplication (use inheritance).
5. Generate empty student list component using ng cli
6. Add property to the component class that will hold students' list
7. Initialize stundent list in component constructor
8. Add code for displaying the student list as a table to the component template. (use either div or table tags)
9. Display student list in app component template using student list component
11. Add a click handler to table column headers for sorting the list. Clicking the column header sorts the list in ascending order. Clicking again sorts the list in the opposite order. The sorting column header should have either a + sign for ascending order or a - sign for descending order (e. g., first name column header text becomes first name+ or first name-)
12. Add a button for randomly shuffling the list.
