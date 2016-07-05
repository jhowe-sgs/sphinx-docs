Provisioning
============

The generally workflow of deployment happens over the summer break, where servers are upgdraded and new OS's are deployed.

Mac OS X provisioning is pretty fast ( hours ), whereas Windows is slower ( day ).

**Mac OS X**

- Push thin image with Deploy Studio
- Configure munki settings
- Download software, apple updates from munki server
- Bind to AD and configure user(s)

**Windows**

- Install thin Mac OS X
- Configure Boot Camp
- Install Windows 8.1
- Activate Windows
- Install all Upstream Updates
- Install Software
- Bind to AD and configure user(s)