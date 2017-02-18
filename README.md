# CalenderSync

Calender Sync is a project that works towards providing push notification updates whenever an event in users google account changes. 
It also has a file called CalenderData.js, it can be called using, 
                [sudo] node CalenderData.js
This code calls for an Oauth authentication for the first time, once an authentication has been donem the token is stored and need not be link-authenticated the next time. (Token Authentication still carried in background).

The second part involves a push-notifier. Which displays the push request whenever generated. Both can be integrated to refresh the Calender Data whenever a push notification is recieved.

The push notifier is hosted on heroku hosting platform at, https://evening-chamber-31050.herokuapp.com/view . A set of events would be made available to the reviewers to modify and their subsequent push changes would be visible at this link.
