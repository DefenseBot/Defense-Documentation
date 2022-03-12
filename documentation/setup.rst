Setup Defense
==========

Setting up Defense can be completed in 3 very simple steps.
----------

1) Invite Defense To Your Server
-----
You can invite Defense via the invite link `here <https://discord.com/api/oauth2/authorize?client_id=944634451927908433&permissions=8&scope=bot%20applications.commands>`_. You will be prompted to Select A Server to add it to, then acknowledge that by inviting Defense you are giving it Administrator Permissions and the ability to make Application Commands in yor server.

**Note:** You must have the Administrator Permission, Manage Server Permission, or be the Server Owner to invite Defense.

2) Adjust Integrated Role Position
-----
For Defense to act upon malicious users it's highest role must be higher then the users higher role. This means that if a user had a higher role then Defense and triggered the Anti-Nuke, Defense would not act upon the user. It must also be known that any users above Defense are able to kick/ban Defense, making your server vulnerable to any attacks on it.

3) Invoke The Setup Command
-----
The Setup command integrated into Defense makes it extremely easy to setup Defense for your server, and be ready for any attacks. To quickly setup Defense for your server, invoke ``/setup``. Note: You must have Administrator Permissions to invoke this command. The setup command will start a process which will check **2** things. If any of the checks fail, then Defense will cancel the process and notify you.

- Verify that it has **Administrator Permission**

- Verify that it's highest role is in the top **3** roles in the server.

If both of these checks pass, then Defense will find/create a logchannel, then update it's database accordingly. Finally, the process will finish and you will be notified of its status.

**Note:** If steps **1)** and **2)** where done correctly, then the setup process will run smoothly.
