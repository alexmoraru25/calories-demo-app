Task functionalities

Users should be able to manage food entries
● A user should be able to add a new food entry
● Food entry should contain the following information:
○ Date/time when the food was taken
○ Food/product name (i.e. Milk, banana, hamburger)
○ Calorie value (numeric value)
● The first screen a user should see is the list of existing food entries
Calorie limit warning per day
● The daily threshold limit of calories should be 2.100.
○ Ensure the users can see for which day they reached that limit. Also, ensure it
is easy to change that limit in the code, per user. You don’t have to create an
interface for this purpose.

Admin role with a simple reporting
● Implement an admin role
● Admin can see a screen with all added food entries of all users and manage existing
food entries (read, update, create, delete)
● Admin should also see the report screen with the following information
○ Number of added entries in the last 7 days vs. added entries the week before
that. Please Include the current day in those stats
○ The average number of calories added per user for the last 7 days
○ A regular user should not be able to access this reporting screen or access its
data

User authentication/authorization
● Please use a token authentication method. You don’t have to implement a signup
and login process. You can manage everything using a predefined user-specific token
in the backend, however, ensure the token can be changed easily during your next
interview

For each food entry, allow the user to pick a meal per each entry
● Users should be able to add a predefined meal for each food entry
● Ensure meal can be changed dynamically e.g. it means you can rename existing meal
in one place it is updated for each food entry tagged with that meal
● Ensure a user can add a maximum number of food entries per specific meal, e.g. 3
food entries for breakfast, 5 for lunch, 2 for dinner, etc.
