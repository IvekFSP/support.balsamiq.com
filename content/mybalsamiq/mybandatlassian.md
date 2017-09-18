---
title: Can I Use myBalsamiq with Atlassian JIRA or Confluence?
date: '2015-05-09T14:46:35.000+00:00'
weight: 70
menu: "menumybalsamiq"
product: "myBalsamiq FAQs"
draft: ''
---

We sell plugins for Atlassian [Confluence Cloud](https://marketplace.atlassian.com/plugins/com.balsamiq.mockups.confluence/cloud/overview), [Confluence Server](https://marketplace.atlassian.com/plugins/com.balsamiq.confluence.plugins.mockups/server/overview), [JIRA Cloud](https://marketplace.atlassian.com/plugins/com.balsamiq.mockups.jira/cloud/overview) and [JIRA Server](https://marketplace.atlassian.com/plugins/com.balsamiq.jira.plugins.mockups/server/overview), however you may already use and like our web application [myBalsamiq](https://balsamiq.com/products/mockups/mybalsamiq).

While we don't have a specific integration between Confluence or JIRA and myBalsamiq, you will be able to add links to your wireframes in myBalsamiq to Confluence pages or JIRA issues.

What you'll want to do is grab an [Image Permalink](https://docs.balsamiq.com/mybalsamiq/mockup/#mockup-description-permalink-download) from myBalsamiq once you've created a wireframe.

![](https://media.balsamiq.com/img/support/docs/myb/image-permalink.png)

Then insert it as follows:

**For Confluence:**

1.  Select Insert > Image
2.  Choose "From the Web"
3.  Paste the permalink from myBalsamiq

**For JIRA:**

You can use the following special markdown syntax to insert the image in the description or a comment: `![image link]!` For example: `!https://mockupstogo.mybalsamiq.com/mockups/1176404.png!`

You won't be able to edit the wireframes directly in JIRA or Confluence as you can with our plugin versions, however if you make changes to the original wireframe in myBalsamiq, the changes will be reflected in Confluence and JIRA when the page refreshes.
