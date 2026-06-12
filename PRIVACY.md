# Privacy

Workloom is designed as a local-first application.

- Tasks, journals, reflections, and settings are stored in a local SQLite database.
- Personal cloud sync works through a OneDrive, WPS, Baidu Netdisk, or similar local sync folder
  selected by the user.
- Workloom does not require cloud account passwords, remote API keys, or a hosted Workloom account.

Before publishing or committing files, make sure they do not include:

- `*.db`, `*.db-wal`, or `*.db-shm`
- The `backups/` directory
- `.env` or token files
- Exported daily, weekly, or monthly reports
- Configuration files containing personal paths or personal information

