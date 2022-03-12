Defense Logging
==========

What Is Logging?
----------

Logging is one of Defense's great features. Upon an Anti-Event being triggered, and a Defense acting upon a malicious user, Defense will also log the event. Defense will send an embed with various information on the event, and also attempt to send the same embed to the server owner. Defense will also occasionally use the logging feature to send important announcements. This will be minimal, should receive 1-2 every 3 months.

How To Setup Logging
----------

Setup Command
-----

In the setup process which can be invoked by ``/setup``, Defense will automatically make and set a logchannel.

Logging Command
-----

To set a logchannel, invoke ``/logchannel #CHANNEL``. This will set the logging channel and update the database accordingly.

TO view the current logchannel, invoke ``/loghannel``.
