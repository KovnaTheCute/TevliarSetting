# 🏆 Achievements Dashboard

## 📊 Total Progress

```dataview
TABLE
  length(filter(rows, (r) => r.completed)) AS "Unlocked",
  length(rows) AS "Total",
  round((length(filter(rows, (r) => r.completed)) / length(rows)) * 100, 1) AS "% Completed"
FROM "Tevliar Setting/Achievements/Achievement List/Achievement Query"
WHERE type = "task"
TASK
FROM "Tevliar Setting/Achievements/Achievement List/Achievement Query"
WHERE category = "Starter"
