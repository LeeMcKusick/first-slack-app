# first-slack-app

This is a Slack bot built from the Salesforce Trailhead module on building a basic Slack app:

https://trailhead.salesforce.com/content/learn/projects/build-slack-bot/

This bot tracks when a new user joins the Slack workspace ("team_join" event), and sends them 2 messages:
One is a simple welcome message, the other is about the Code of Conduct, with a button for them to click that they accept the COC.

When they cick the button, it triggers an API event that tracks the event in a mock DB (JSON file). 
