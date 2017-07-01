# main-project-angular

Final Project for the Front End Web Dev course at Acagild

Used angular cli for creating and running the app (use ng serve and go to localhost:4200 to see app running)

Event Scheduler:

Used in-memory web api. It intercepts Angular Http requests that would otherwise go to the remote server via the Angular XHRBackend service

Main page has a list of current events

Can choose to see list of current events or a list of archived events

Each event displays information about the event

User can upvote or downvite an event

User can also cancel an event and doing so removes the event from the list and moves it to the archive page

User can edit the event and that takes them to the edit page

User can edit the event info and click the update button. Or, go back

User can add a new event. Basic form validation implemented. Adding the event will add it to the current event list

Archived events page has list of events past the current date and also a list of cancelled events
