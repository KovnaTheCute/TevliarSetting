# 🏆 Tevliar Achievements Dashboard

## 📊 Total Progress

```dataviewjs
// Gather all tasks in the achievements folder
const tasks = dv.pages('"Tevliar Setting/Achievements/Achievement List"')
    .file.tasks;

const total = tasks.length;
const completed = tasks.filter(t => t.completed).length;
const percent = Math.round((completed / total) * 100);

dv.header(3, "Achievement Progress");
dv.paragraph(`Unlocked: ${completed} / Total: ${total} (${percent}%)`);
```