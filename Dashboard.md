---
banner: "![[greg-rakozy-oMpAz-DN-9I-unsplash.jpg]]"
banner_y: 0.904
banner_icon: 🦎
---

## ![[fire.gif]]Todo Items
```dataview
TASK
FROM #todo/work AND -#example 
WHERE !completed AND !person-name
GROUP BY category
SORT priority
```
```dataview
TASK
FROM #todo/work AND -#example 
WHERE !completed AND person-name
GROUP BY person-name
SORT priority
```
### ![[light_bulb.gif]]1:1's 
```dataview
LIST from "Work/Meetings/People"
```
### Meetings
```dataview
LIST meeting-date from "Work/Meetings" and -"Work/Meetings/People"
SORT "meeting-date" DESC
LIMIT 10
```
### Scratch Pad
