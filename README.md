# Bamboo.Service

## About
Service file for running Atlassian Bamboo as a Service in Mac


## Usage
In Terminal, go to ~/Library/LaunchAgents.

Create a plist file:

```
sudo nano ~/Library/LaunchAgents/com.atlassian.bamboo.plist
```

Copy the content of com.atlassian.bamboo.plist file in Nano editor.

Save the file.

RUN:

```
launchctl load ~/Library/LaunchAgents/com.atlassian.bamboo.plist
```

RUN:

```
launchctl start com.atlassian.bamboo
```

To stop the service Run:

```
launchctl stop com.atlassian.bamboo
```

To unload the launch agent:

```
launchctl unload ~/Library/LaunchAgents/com.atlassian.bamboo.plist

```

# Bamboo Continuous Integration for DevOps Developers

[![Bamboo CI](https://img-c.udemycdn.com/course/750x422/1520666_9f95_7.jpg)](https://www.udemy.com/course/bamboo-continuous-integration-for-devops-developers/?referralCode=3019D7872D03BEE6CB5E)

This repository contains resources related to the Udemy course on Bamboo Continuous Integration for DevOps Developers. 

Course Link: [Bamboo Continuous Integration for DevOps Developers](https://www.udemy.com/course/bamboo-continuous-integration-for-devops-developers/?referralCode=3019D7872D03BEE6CB5E)


## More Free Courses on YouTube

[![YouTube](https://img.shields.io/badge/YouTube-Subscribe-red?style=flat&logo=youtube)](http://www.youtube.com/@FreeTechnologyLectures)

Subscribe to the Free Technology and Technology Management Courses channel for free lectures about Coding, DevOps, and Technology Management. [Here is the link to the YouTube channel](http://www.youtube.com/@FreeTechnologyLectures).


