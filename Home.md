---
tags: [index]
---

# Work Vault

## Quick Links
- [[Daily]]
- [[Meetings]]
- [[Projects]]
- [[People]]
- [[Inbox]]

## Recent Meetings
```dataview
TABLE date, project
FROM "Meetings"
SORT date DESC
LIMIT 5
```

## Active Projects
```dataview
TABLE status
FROM "Projects"
WHERE status = "active"
SORT file.name ASC
```

## Upcoming Action Items
```dataview
TASK
FROM "Meetings"
WHERE !completed
LIMIT 10
```
