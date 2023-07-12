# Bamboo.Service
Service file for running Atlassian Bamboo as a Service in Mac

In Terminal go to ~/Library/LaunchAgents.

Create a plist file:

sudo nano ~/Library/LaunchAgents/com.atlassian.bamboo.plist

Copy the content of com.atlassian.bamboo.plist file in Nano editor.

Save the file.

RUN:
launchctl load ~/Library/LaunchAgents/com.atlassian.bamboo.plist


RUN:
launchctl start com.atlassian.bamboo

To stop the service Run:
launchctl stop com.atlassian.bamboo

To unload the launch agent:
launchctl unload ~/Library/LaunchAgents/com.atlassian.bamboo.plist


