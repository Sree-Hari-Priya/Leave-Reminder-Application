## <ins>How to run the program:<ins>

### <ins>Prerequisites:<ins>
1. The system should have VScode IDE installed.
2. To clone the repository from github, git should be installed on your system.
3. Must have one google account assosiated with their gmail.

### <ins>Steps:<ins>

#### <ins>Setting up the code:<ins>
1. First the project should be cloned from Github. This can be done using the git init that is downloaded on you system.
2. After doing git init in the particular folder, we have to clone the project using git clone command in the terminal.
3. Now the folder is created in the mentioned path.
4. Open vscode and navigate to the folder created from above.
5. You will be able to see the folder structure as it is present in the github.

#### <ins>Running the code from integrated terminal:<ins>
1. Open terminal from the IDE and navigate to the /src folder using cd / command.
2. Now run the server using the command **python -m http.server 8000.**
3. Now the server is running on your localhost
4. Open your browser and start localhost 8000 port by entering **http://localhost:8000/**

#### <ins>Running the website:<ins>
1. Once you open the localhost:8000 on your browser then you'll be seeing the website poped up.
2. And on the website you can see the option to sign in using google.
3. After you click on that you'll be seeing a google account management pop up saying we have to suthorise the application to use our google calendar.
4. Once the authorisation is done you'll be seeing the user profile page.
  
#### <ins>Profile page usage:<ins>
1. Once you are navigated into the profile page. You can see all the notifications about leaves remaining for a month.
2. On the left panel you can see the upcoming leaves and on the right side you have a provision to schedule a leave.
3. Once we click on a leave link it is redirected to the google calendar showing the leave scheduled in your calendar.
4. If both the leaves for the given month are scheduled the notification alert is disappeared.
  
  
  
