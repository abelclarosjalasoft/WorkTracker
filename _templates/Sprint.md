---
tags:
  - sprint
---

```jira-search
type: table
query: project = 'AAA' AND Sprint= 1234 AND status != 'Removed' ORDER BY key 
limit: 50
columns: KEY, SUMMARY, ASSIGNEE, STATUS, NOTES.Status
account: my.account
```
