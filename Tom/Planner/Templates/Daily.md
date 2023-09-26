### Timetable 
![[Rozvrh]]
## Que
```dataviewjs
dv.taskList(dv.pages().file.tasks 
  .where(t => !t.completed)
  .where(t => t.text.includes("{{date:ddd D.M - gg}}")))
```

## Log
