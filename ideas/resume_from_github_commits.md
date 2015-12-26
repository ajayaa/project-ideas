Create a resume from github public commits. Could be a command line tool.

Extension
=========
Create a resume service. Users should be able to register using their github username. 
Expose apis which is publicly consumable. Put a good rate limiter, otherwise be ready
to be demolished. :)

Otherwise it should be simple enough to put basic auth in your app. Whenver someone
signs up using their github, keep the username same as the github username and generate
a random and easy password and give it to the user.
