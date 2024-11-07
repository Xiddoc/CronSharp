# CronSharp
Cross-platform scheduled event library written in C#.

## Features
- Super lightweight: there is no running service, timer, or process during the inactivity period. Under the hood, it uses Task Scheduler (Windows) and cron jobs (Linux).
