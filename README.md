currently there is not really any documentation.
This project is written in multiple languages, included but not limited to PHP, Smarty, javascript, css, html and SQL.
It is meant to be a complete webpage, and will be improved apon reguraly by me personally, 
if other people also decide to work on it, then it will also be accepted, providing it keeps to the standards i am using already, 
otherwise i'd accept the changes but make modifications to them in order for it to keep the standards, 
however if too much work is required to make it live up to my standards i will see no other action than to reject the pull request.

Standards required for this project.

Every single page needs to use the smarty templating engine and use the templates already in place.
Line length is max 160 characters, i will not be counting characters, but if it is too large edits will be required.
All database calls go through the database class, if changes are needed in the class for it to work, then make the changes there as well then.
All database calls should use the bind statements if there is any user input, no exceptions. i want SQL injections to be the last thing on my mind.
Any userdata printed out should be filtered so it does not load javascript files etc, this means no html input, this can be allowed on administration pages.