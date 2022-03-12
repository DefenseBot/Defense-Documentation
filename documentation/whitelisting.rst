Defense Whitelisting
==========

What Is The Whitelist?
-----
Whitelisting is a feature that allows the Server Owner to specify users they want Defense to ignore. If a user is whitelisted and triggers the Anti-Nuke, Defense will not act upon the user. This is meant to give the Server Owner an ability to specify "trusted" users. The whitelist will be created whenever Defense joins a server with **2** users in it. The Server Owner and Defense. The Server Owner is the only person who can view/edit the whitelist, making it an extremely dangerous to whitelist someone.

Viewing The Whitelist
----------
To view the whitelist, invoke `/whitelisted`. This will send a formatted list of the users currently whitelisted for the server.

**Note:** Only the server owner can use the command. It will send the list of users as an "Ephemeral Message", meaning that only the guild owner can see it. This feature was added to make sure that malicious users cannot target whitelsited users, attempting to take their account/receive info on the server to plan an attack.

Editing The Whitelist
----------

Adding To Whitelist
-----
To add a user to the whitelist, invoke `/whitelist add USER`. This will add the user to the server whitelist, and will update the database accordingly. The USER argument can take an object, meaning you can pass in any of the following:

- @Wumpus

- Wumpus#1000

- 425092601463921328

**Note:** As soon as a user is whitelisted, Defense will ignore **any** and **all** actions by the user. This is a **dangerous** permission to grant.

Removing From Whitelist
-----
To remove a user from the whitelist, invoke `/whitelist remove USER`. This will remove the user from the server whitelist, and will update the database accordingly. The USER argument can take an object, meaning you can pass in any of the following:

- @Wumpus

- Wumpus#1000

- 425092601463921328

**Note:** As soon as a user is removed from the whitelist, Defense will listen to all actions by the user, and will take action if they trigger an Anti-Event.

**Also:** If a whitelisted user leaves for any reason, Defense will automatically handle removing them from the whitelist, and will update the database accordingly.
