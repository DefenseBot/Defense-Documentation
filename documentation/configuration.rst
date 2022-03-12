Defense Configuration
==========

Defense Anti-Nuke Modules
----------

- Anti-Channels

- Anti-Roles

- Anti-Kick

- Anti-Ban

- Anti-Bot

What Is The Configuration?
----------

The configuration is the current Anti-Nuke settings for the guild. For each module, Defense will display its status, wheather if it is enabled or disabled, its threshold, and its per. To view the server configuration, invoke ``/settings``. 

**Note:** Only the Server Owner can view the configuration.

Editing The Configuration
-----------

Toggling Modules
-----

Toggling modules gives the ability to disable any Anti-Event, irregardless if they are whitelisted or not.

To toggle a module, invoke ``/config toggle MODULE``. This will toggle the event to the opposite of its current status, and update the database accordingly.


**Note:** Only the person who can toggle the config is the Server Owner

Setting Thresholds & Secomds
-----

Settings thresholds and seconds gives the ability to change how fast Defense acts upon the user for a x amount of seconds.

The easiest way of understanding the thresholds ad seconds is like a command cooldown. Given the example of a threshold of **2** and a rate of **25**. You will be able to use the command a maximum of 2 times per every 25 seconds. If you surpass the limit, and try to invoke the command for the third time in the 25 second time slot, you will be given an on cooldown error.

Defense's Anti-Nuke works similarly. If a config for Anti-Channels is set to a threshold of **1**, at a rate of **50**, a user will be allowed to make **1** channel every **50** seconds, however in each 50 second time slot, if the user passes the liit of **1**, and makes a 2nd channel, the Anti-Nuke will be triggered.

TO edit a threshold and rate, invoke ``/config set MODULE RATE PER``. This will edit the configuration immediately, and will update the database accordingly.
