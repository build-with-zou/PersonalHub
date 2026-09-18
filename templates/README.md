# 私有状态模板

本目录中的模板可以公开提交，但由模板生成的个人状态必须保持私有。在 PersonalHub 内创建个人文件时，统一使用 `.local.md` 后缀；`introduction/`、`reminders/` 和 `worklog/` 中的内容由整目录忽略规则保护。

复制模板前先确认目标文件不存在，避免覆盖已有状态。

| 模板 | 推荐目标 | 用途 |
|---|---|---|
| `profile.md` | `PROFILE.local.md` | 稳定背景、学习和协作偏好 |
| `goals.md` | `GOALS.local.md` | 长期方向与阶段目标 |
| `dashboard.md` | `DASHBOARD.local.md` | 当前重点、期限、阻塞和暂停项 |
| `paths.md` | `PATHS.local.md` | 本机资料路径和私有链接索引 |
| `inbox.md` | `INBOX.local.md` | 尚未讨论或承诺的想法 |
| `area-status.md` | `areas/<领域>/STATUS.local.md` | 领域任务、进度、阻塞和下一步 |
| `knowledge-state.md` | `areas/<领域>/KNOWLEDGE.local.md` | 概念证据、误区和下一次验证 |
| `introduction.md` | `introduction/YYYY-MM-DDINTRODUCTION.local.md` | 阶段原始自述 |
| `daily-log.md` | `reviews/YYYY-Www-daily.local.md` | 一周的每日滚动记录 |
| `weekly-review.md` | `reviews/YYYY-Www.local.md` | 周复盘与下周取舍 |
| `worklog.md` | `worklog/YYYY-MM.local.md` | 重要协作结果与验证 |
| `learning-session.md` | 课程原目录中的学习记录，或 PersonalHub 内的 `*.local.md` | 一次较完整的教学或练习过程 |

模板中的空白表示未知。AI 不应替学习者填写未经确认的事实，也不应把愿望、计划或已阅读内容写成已完成和已掌握。
