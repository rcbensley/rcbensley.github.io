# Database Adminstration

What follows is my rough guide to being an effective DBA be it as a contractor or within an organisation.
Any working professional should be able to communicate change, of which database systems are the epitome.
They are networked services which communicate between systems and processes, and will undergo several changes during their lifespan.

## Communicate
Measuring change with issue tracking, documentation, and version control. Not only to look back on what you or your team, are currently achieveing, but also to be better prepared for the next challenge.

* Backups. What? Where? How freuently? Have they been tested?
* Is there a change management system? Database code control? If not, make one to track your own issues and related changes.
* Using the Issues/Worklog created as part of the previous point, link it to a exisint documentation solution or your own.
* Who can access the database? Why? Document access of users, software, and services such as backups and monitoring.

## Change
* Maintenance windows. When can a change be made? Are you in sync with other systems being change? Is there CI/CD?
* Communicating change. Who needs to know what has happened? Are you responding to change from another team's request? Or are you making an improvement?
* Backup system schemas, DDL and users, NOW! Before you make changes. You can at least establish a base line for rollbacks.
* Rollbacks! No matter how small the change, have a prepared and practised rollback procedure for what you are about to do.