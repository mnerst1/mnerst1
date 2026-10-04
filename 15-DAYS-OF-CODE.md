# 15 Days of Code — Project Journal

I build practical projects across Android, web, desktop and Python, then return to improve their reliability and usability.

**Progress: 13 / 15 projects completed.** This journal brings together the first thirteen projects of the **15 Days of Code** challenge, from a Python password generator to a local Windows developer workspace.

| Day | Project | Focus |
|---|---|---|
| 001 | [Password Generator](https://github.com/mnerst1/Password-Generator) | Python, cryptographically secure passwords and multilingual controls |
| 002 | [Multilingual WPF Calculator](https://github.com/mnerst1/Multilingual-WPF-Calculator) | C#, .NET, WPF and a multilingual desktop calculator |
| 003 | [StudyFlow](https://github.com/mnerst1/StudyFlow-Android) | Kotlin, Android and study task planning |
| 004 | [Text Analyzer](https://github.com/mnerst1/Text-Analyzer-Python) | UTF-8 text, word frequencies, statistics and search |
| 005 | [TaskFlow](https://github.com/mnerst1/TaskFlow-HTML) | HTML, CSS, JavaScript, task management and local JSON backups |
| 006 | [Expense Tracker](https://github.com/mnerst1/Expense-Tracker-SQLite) | Python, persistent SQLite storage and spending statistics |
| 007 | [Stellar Log](https://github.com/mnerst1/Stellar-Log-Android) | Kotlin, Compose, Room and an offline stargazing journal |
| 008 | [Neon Survivor](https://github.com/mnerst1/Neon-Survivor-Android) | Kotlin, Android, arena survival, upgrades and achievements |
| 009 | [BugTrack](https://github.com/mnerst1/BugTrack-PHP) | PHP, MySQL, issue tracking, Kanban boards and team roles |
| 010 | [LinkPulse](https://github.com/mnerst1/LinkPulse-TypeScript-API) | TypeScript REST API, short URLs and click analytics |
| 011 | [UniFlow](https://github.com/mnerst1/UniFlow-Android) | Kotlin, Compose and a university assistant |
| 012 | [FinCore](https://github.com/mnerst1/FinCore) | Next.js, TypeScript, PostgreSQL, Prisma and personal finance |
| 013 | [DevDock](https://github.com/mnerst1/DevDock) | Python, PySide6 / Qt 6, SQLite, Git CLI and a Windows developer workspace |

## Day 013 — DevDock

DevDock is a local Windows workspace for managing development projects:

- Project discovery for Git, Node.js/Next.js, Python, PHP/Composer, Gradle/Kotlin and Docker.
- Workspace overview, search, favorites, tags and a Ctrl+K command palette.
- Git status, fetch, fast-forward pull, clean-tree branch switching, commit history and file diffs.
- TODO/FIXME/HACK scanning, source statistics and explained offline project health checks.
- Custom commands with live stdout/stderr and confirmed stopping of DevDock-owned process trees.
- Local port monitoring with PID, process name and ownership; external processes remain read-only.
- Autosaved project notes, snippets, recent activity and SQLite backups.
- English, Russian and Kazakh interfaces; Light, Dark and System themes, four appearance styles and custom accent colors.

Built with Python 3.12+, PySide6 / Qt 6, SQLite, Git CLI and psutil. Developed in VS Code without Visual Studio or external API keys. The Windows onedir executable is packaged with PyInstaller; optional Inno Setup configuration is included.

Version 1.0.0 passed 30 automated tests, and the packaged Windows executable completed a smoke launch with exit code 0. Installer compilation, signing and clean-machine validation remain follow-up tasks.

[Source, screenshots and setup instructions](https://github.com/mnerst1/DevDock#readme) · [Download v1.0.0](https://github.com/mnerst1/DevDock/releases/tag/v1.0.0)

## Day 012 — FinCore

FinCore is a self-hosted personal finance web app:

- Accounts, income, expenses, transfers and category trees.
- Monthly budgets, savings goals, debts and recurring payments.
- Net worth, cash flow, spending breakdown and monthly trends.
- Calendar, in-app reminders, activity history and local receipts.
- CSV import/export and JSON financial backups with receipts.
- Secure sessions, profile settings and one-click demo login.
- Fifteen interface locales, including complete English, Russian and Kazakh dictionaries; Arabic RTL.
- Light, Dark and System themes, five visual styles, accent colors and a collapsible sidebar.

Built with TypeScript, Next.js App Router, PostgreSQL, Prisma, Tailwind CSS, Radix UI, Recharts and Motion. Runs locally with Node.js and Docker Compose, without external API keys.

[Source, screenshots and setup instructions](https://github.com/mnerst1/FinCore#readme)

## Day 011 — UniFlow

UniFlow brings student planning into one Android app:

- Dashboard and weekly timetable.
- Subjects, teachers, assignments and deadlines.
- Calendar, exams, grades, GPA and attendance.
- Notes, search, settings and persistent local data.
- English, Қазақша and Русский interfaces; Light, Dark and System themes.

Built with Kotlin, Jetpack Compose, Material 3, Room, Coroutines/Flow, Navigation Compose, DataStore and WorkManager.

[Source and screenshots](https://github.com/mnerst1/UniFlow-Android#readme) · [Releases](https://github.com/mnerst1/UniFlow-Android/releases)

## Maintenance matters too

The challenge includes returning to earlier projects: fixing edge cases, adding regression tests, improving documentation and keeping each change independently understandable.

## Қазақша

Бұл — 15 Days of Code челленджінің жоба журналы. 15 жобаның 13-і дайын, кестеде 001–013 күндерінің барлық жобалары берілген. Соңғы жоба — DevDock: жобалар, Git репозиторийлері, командалар, TODO маркерлері, порттар, жазбалар және код үзінділерін басқаруға арналған жергілікті Windows қолданбасы. Python, PySide6 / Qt 6 және SQLite арқылы жасалған; қазақша, орысша және ағылшынша интерфейсі бар.

## Русский

Это журнал челленджа 15 Days of Code. Готово 13 из 15 проектов; в таблице собраны все дни с 001 по 013. Последний проект — DevDock: локальное Windows-приложение для управления проектами, Git-репозиториями, командами, TODO, портами, заметками и сниппетами. Создано на Python, PySide6 / Qt 6 и SQLite; интерфейс доступен на английском, русском и казахском.
