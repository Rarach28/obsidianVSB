## Que
```dataviewjs
dv.taskList(dv.pages().file.tasks 
  .where(t => !t.completed)
  .where(t => t.text.includes("Thu 28.9 - 23")))
```





## Log
