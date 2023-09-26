## Que
```dataviewjs
dv.taskList(dv.pages().file.tasks 
  .where(t => !t.completed)
  .where(t => t.text.includes("Wed 27.9 - 23")))
```





## Log
