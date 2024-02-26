# Tickets worked by date
```dataview
LIST 
	rows.file.link
FROM 
	!"_templates" 
SORT 
	file.ctime ASC
GROUP BY 
	file.cday AS Day
```
# Notes by Ticket
```dataview
task
from !"_templates" 
where meta(section).subpath = "Notes"
group by file.link 
```
# Requirements by Ticket
```dataview
task
from !"_templates" 
where meta(section).subpath = "Requirements"
group by file.link 
```

