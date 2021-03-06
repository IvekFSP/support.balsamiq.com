---
title: How to Use Both the Confluence Server and Jira Server Plugins and Manage My Users
  via LDAP
date: '2015-05-09T14:46:35.000+00:00'
weight: 100
menu:
  menuplugins:
    weight: 100
draft: ''

---

This article is for IT administrators whose companies:

*   bought both Balsamiq Mockups for Confluence Server and Balsamiq Mockups for Jira Server
*   do not use the built-in user management of Confluence and Jira

## How Does Plugin Authentication Work in General?

As specified in our [Confluence Server Admin Guide](https://docs.balsamiq.com/confluence/server/mockups2/admin-guide/#selecting-mockup-editors) and in our [Mockups for Jira Server Admin Guide](https://docs.balsamiq.com/jira/server/mockups2/admin-guide/#selecting-mockup-editors) the plugin looks for a user group called _balsamiq-mockups-editors_ to decide which users should have access to create and edit mockups.

## What If I Want My Jira Server Editor Group and My Confluence Server Editor Group to Be Separate?

Say you bought a 10-editor license of Mockups for Confluence Server and a 3-editor license of Mockups for Jira Server.

If you added your 10 wiki editors to the balsamiq-mockups-editors group, the Jira Server plugin would complain that you're going over your 3-user limit.

There is a solution to this tricky problem!

1.  Delete the _balsamiq-mockups-editors_ group
2.  Create a new _balsamiq-mockups-editors-confluence_ group and add your chosen wiki editors to it
3.  Create a new _balsamiq-mockups-editors-jira_ group and add your chosen bug tracker editors to it

That's it! Each plugin will now look at its own group, and live happily ever after. :)
