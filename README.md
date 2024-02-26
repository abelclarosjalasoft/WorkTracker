Two plugins are used:
- [Dataview](https://github.com/blacksmithgu/obsidian-dataview)
- [Jira-Issue](https://github.com/marc0l92/obsidian-jira-issue)
Dataview plugin does not need configuration for this tool.
# jira-issue Setup

1. Login to Jira in a web browser
2. Go to https://id.atlassian.com/manage-profile/security/api-tokens
3. Create an API token and copy it.
4. In the jira-issue plugin configuration menu fill the following inputs
	1. Alias: Insert the alias for the user, this will be used in the requests
	2. Host: Insert URL from the company's Atlassian server
	3. Authentication Type: Jira Cloud
	4. Email: The email your user is registered to Jira server
	5. API Token: Token from step 3
	6. Priority: Default (1), unless you are using more than one account
	7. Color band: Default
	8. Click on the Test Connection button to verify you are correctly logged in to Jira
