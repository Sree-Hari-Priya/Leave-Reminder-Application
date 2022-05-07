## Leave Reminder Application
CS5704 Software Engineering Final Project

#### <ins>Description:<ins>

- This application simplifies the process of monitoring leaves during the COVID-19 epidemic for employees. It recalls and encourages users to take breaks from work to maintain their mental health and well-being. This program assists the user by displaying the number of leaves in a calendar year as well as the remaining leaves. The user can keep track of the leaves more easily this way. By presenting the leaves on the website, the user may quickly schedule the leaves without having to travel all the way to the calendar. We can retain the mental health of the user by keeping track of leaves and maintaining a minimum of two leaves every month.
 

  
#### 1. Running of the code and it's implementation is provided in src/README.md
  
#### 2. Running of Test cases and examples is provided in test/README.md 

#### 3. Use cases and test cases are mentioned and well documented in test/testing document
  
 
<ins>Project Group Members:<ins>

1.Sree Hari Priya - GitHub(Sree-Hari-Priya)

2.Nihitha Veeramachineni - GitHub(nihitha13) 

3.Sai Asrith Atukuri - GitHub(asrith27) 

4.Sindhu Vyshnavi Samala - GitHub(sindhuvyshnavisamala)
 
 
### <ins>Use cases<ins>
 - This application has four use cases and all the use cases are running as expected. The expected and actual outcomes of these use cases are mentioned in the document in test/testing document:
 
 1. **Succesful Login:** First use case is the login of the portal. That is whenever a user open the website they shoudl be able to see the sign in with google button.After the button is clicked, the user should be able to login to their profile page.
 2. **Schedule leave:** A user should be able to schedule a leave without getting an error on clicking the schedule button and the scheduled leave should be available on the upcomings column on successful addition of the leave.
 3. **Notification alert:** when the current month is not scheduled with any leaves then the alert should say no leaves scheduled for the month. If one leave scheduled then it should say one more leave remaining for this month. If two leaves are scheduled then the notification should be disappeared.
 4. **Redirect to calendar:** On successful addition of teh leave on the upcoming events coulumn. Whenever a leave is clicked it should redirect to the google calendar.
 
- As this application doesn't have any heavy javascript code unlike other general websites unittest cases can be generalised and run along with the execution.
  
