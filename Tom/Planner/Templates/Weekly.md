### Timetable 
![[Rozvrh]]
## Que
```dataviewjs
dv.taskList(dv.pages().file.tasks
  .where(t => !t.completed)
  .where(t => t.text.match(/[A-Za-z]{3} \d+\.\d+ - \d+/))
)
```





## Log
