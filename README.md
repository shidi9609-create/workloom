# Workloom

**A local-first desktop workspace for tasks, daily work journals, reflection, reporting, and personal cloud sync.**

Workloom was originally designed around human resources workflows, including recruitment, training,
employee relations, and performance management. Its labels are fully editable, so the same workflow
can be adapted for e-commerce operations, software development, sales, administration, marketing,
and other professional roles.

[中文介绍](#中文介绍)

## Features

- Create, edit, complete, postpone, and categorize tasks
- Customize professional labels for different roles and industries
- Record daily accomplishments, next steps, notes, and reflections
- Manage weekly focus items and monthly goals
- Review work through weekly, monthly, calendar, and dashboard views
- Mark calendar dates with colors for reminders
- Export work reports to Word or PDF
- Store data locally in SQLite with automatic backups
- Sync between computers through a local OneDrive, WPS, Baidu Netdisk, or similar sync folder
- Choose from green, gray, blue, and rose interface themes

## Designed for Different Roles

Workloom starts with HR-oriented labels, but you can edit them from the Settings page.

| Role | Example Labels |
| --- | --- |
| Human Resources | Recruitment, Training, Employee Relations, Compensation & Performance |
| E-commerce Operations | Products, Creators, Advertising, Orders, Customer Service |
| Software Development | Features, Bugs, Reviews, Releases, Technical Debt |
| Sales | Leads, Follow-ups, Proposals, Contracts, Revenue |
| Marketing | Campaigns, Content, Channels, Events, Analytics |

## Download

Download the latest Windows version from [GitHub Releases](https://github.com/shidi9609-create/workloom/releases/latest).

- Version: `v0.3.3`
- Platform: Windows x64
- File: `Workloom-v0.3.3-windows-x64.exe`
- SHA-256: `DA92DC46F562252C3D56B2EA64D7BE89491C32C9F64C2A6CE639C1261EA8D013`

> The executable is currently unsigned. Windows may display a security warning. Download it only
> from this repository's Releases page and verify the SHA-256 checksum.

## Local-First Data and Privacy

Workloom stores tasks, journals, reflections, and settings locally on your device. Personal cloud
sync works through a folder selected by the user. Workloom does not require cloud account passwords,
remote API keys, or a hosted Workloom account.

See [PRIVACY.md](PRIVACY.md) and [SECURITY.md](SECURITY.md) for details.

## Technology

- Tauri 2
- React
- Rust
- SQLite

This repository currently serves as the binary release and product documentation repository.
It does not contain the complete maintainable source project.

## License

No open-source license is currently granted. All rights reserved.

---

## 中文介绍

Workloom 是一款本地优先的 Windows 工作记录与效率管理应用，可集中管理 Todo、日报、
每周重点、反思记录、月度目标和工作看板。

Workloom 最初围绕人力资源工作场景设计，预设了招聘、培训、员工关系、薪酬绩效等标签。
所有标签都可以在设置中自由修改，因此同样适用于电商运营、研发、销售、市场、行政等职业。

主要功能包括：

- 自定义职业标签与 Todo 分类
- 日报、明日计划、备注与反思记录
- 本周重点、月度目标、日历和分类看板
- Word / PDF 工作报告导出
- 本地 SQLite 数据存储与自动备份
- 通过个人云盘本地同步文件夹在不同电脑间同步

