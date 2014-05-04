tomcat-says
===========

This is a simple script that notifies users when deployments happen as well as the startup time for a Tomcat instance.
This is meant for Mac OS X only.

When audio is on it will have **voice-based** info.
When audio is muted it will **show notifications** instead.
 
Examples
-------
This first example reads the log and gives the start-up time, in minutes & seconds for the Tomcat instance.
>./bin/catalina.sh start | tail -f logs/catalina.out | tomcatSays

This next example will also describe when each application is being deployed.
>./bin/catalina.sh start | tail -f logs/catalina.out | tomcatSays -v

Suggestions?
-----------
Should the script do more, do less?  Feel free to share insights & improvements!

License
----

MIT
