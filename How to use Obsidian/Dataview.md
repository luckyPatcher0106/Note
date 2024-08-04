- First, i create a person: [[Faker]] and [[Showmaker]]
- now, i want query the infomation of Faker, using the dataview
### Query
```dataview
Table Name, Born, Position, Company
Where Type = "Person"
SORT file.name ASC
```
### List
```dataview
LIST Company
WHERE type = "Person" and Job = "LOL esport player"
```
### Table
```dataview
TABLE Company as Location
WHERE Type = "Person" and Job = "LOL esport player"
```
```dataview
TABLE Company as Location 
WHERE contains(tag, "T1")
```
### Task in dataview
```dataview
TASK WHERE !complete
```
### Calendar
```dataview
CALENDAR file.mtime from #DK 
```
```dataview 
CALENDAR file.mtime from #hashtag 
```
