# EventPlanner
Design and implementation of Event Planner App 

WEEK 1:
•	 Android Project.
We have decided that our project implementation will be codded with Java on Android Studio Platform.
•	 Github setup for project synchronization between members.
•	 Login design and implementation connected to our project database.
Firebase Authentication.

WEEK 2:
•	 Getting Vendors information from the database and display it in the Home interface.
The first class to be invoked (MainActivity class) will acts as a loading screen performing different queries to the project database to get data about the Vendors
this is essential for upcoming functionalities. see more at: Get data with Cloud Firestore.
•	 initial workflow skeleton between Interfaces.
Deciding class hierarchies and objectives.
Interface	Objective	Progress
MainActivity class	Loading Vendors and Venues data	
AddBudget class	creating new Budget	
HomeActivity class	Users main interface with the system	
Search class	Searching (filters) of venues	
Add vendor class	To add  vendor	
Delete vendor class	To delete vendor	
Add venue class	To add  venue	
SignUpFragment class	Regestring and authenticating user with the project database	
SignIn class	Authenticating user with the project database	
Delete venue	To delete venue	
User class	Object-oriented class containing user data	
vendor class	Object-oriented class containing vendors data	
Venues class	Object-oriented class containing venues data	

WEEK 3:
 Home interface GUI design and implementation.
1.	Implementing a dynamic list with RecyclerView, to View the Vendor's registered sections in cards. see more at: Create dynamic lists with RecyclerView.
