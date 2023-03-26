# 325BotReport3
Group 5's Bot for Progress Report 3!

## Current Commands

- /settemplate : This command will set the templates for all the courses 
- /createsemester : This will create a new semester 
- /addcourse : This commands allows you to add a course to an existing semesters 
- /launchsemester : This command will initialize all the categories and channels for a given semester 
- /endsemester : Archives all categories and channels for a given semester Takes everyone with a student role and changes a to veteran role
- /deletesemester : This commands will delete all channels and categories related to a given semester
- /infosemester : Reads all .json categories under /data/semester and prints out current semester list
- /help : Will list all current commands and give information on how to use them
- /create-role : Using this command will take a current role and copy it with its permissions new student and veteran role, assigning it a color from color.json file which will only use each color once 
- /reactionroles : Creates a message students can react to that will give them a specific role
- /duplicate : It takes a category and makes a new category with a new name given by the user and copy all channels and messages within channel into new channel 
- /ping : This command will send a simple message reply of "Pong!"

## Installation Instructions

To install the bot, clone the repository, create a .env file in the root of
the project. The .env file must have three lines, containing the bot's token,
the Discord server's ID, and the bot's profile ID. Ex:

Line 1: TOKEN=(Bot token)

Line 2: CLIENTID=(Bot profile ID)

Line 3: GUILDID=(Server ID)

Invite the bot to your server, deploy the slash commands by running "node deploy-commands.js", then run the bot using "node ." and set the class template and optional channels template with /settemplate.
Now the bot is set up!
