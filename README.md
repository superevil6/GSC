# GSC
* This demo allows for realtime editing and communication with Google's Sheet API V4, and lets you edit and retrieve spreadsheet values, as
apply mathamatic equations between two cells onto a third cell. API calls are made in JSON format and submit/retrieve all values at once
to limit API calls. A standard user can make 100 api calls for every 100 seconds, so the JSON file format helps prevent going over.
* There are two HTML events that trigger refreshing the values, and one that submits the values. 
* This demo has been set up to utilize my Google account, and has access to my Google Sheet for testing.
***The sheet is public and able to be modified by anyone.***

To set up your own spreadsheet on a seperate account, please use the following instructions:

1.  You will need a spreadsheet that you want to edit: 
on line 134:
        spreadsheetId: '13_cISxvrM-IaaMfg5SEHefNsuI6F4n5UBhpXAhOLqfw',
        
        please replace the code on line 134 and 222 with the code of the spreadsheet you would like to edit.
replace the url segment above with the url segment of the document you'd like to edit. Your URL for the spread sheet should be similar to this:
https://docs.google.com/spreadsheets/d/13_cISxvrM-IaaMfg5SEHefNsuI6F4n5UBhpXAhOLqfw/edit#gid=0
                                       ^^^ ^^^ ^^^ ^^^ ^^^ ^^^^ ^^^^ ^^^^ ^^^^ ^^^^ - use this.
                                       
2. You'll need a google developer account:
https://console.developers.google.com/
A. From there create a new project by selecting the dropdown arrow in the topbar located to the left of the "Google APIS" logo.

B. After creating a new project, in the left side bar of the same page, select the credentials tab located at the bottom of the list.

C .Select the blue "Create Credentials" button and select a new OAuth client ID.

D. When prompted for an application type select "Web Application", and put in any name you'd like.

E. For the sake of this demo Authorized JavaScript origins is: 

  http://localhost:8000

Do feel free to use your own server or domain.

F. You will be given a "Client ID" similar to this: 458700823337-cr4ektitets0uhfj1tfl4ua8e4ak3rb5.apps.googleusercontent.com

please replace the code on line 42 with the code that you are presented from Google.

3. Run a server (I have used a local Python server.) and you should now have access to the basic calculator.

Have fun! 

