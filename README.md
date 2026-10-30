# linux-log-analysis-practice
Hands-on Linux log analysis practice for L1 Application and Production Support.

# Linux Log Analysis Practice

## Day 1 – L1 Application / Production Support

### About this project
This project contains my beginner-level hands-on practice in Linux log analysis. I used a sample application log file to investigate application errors, warnings, failed logins, payment issues, and HTTP 500 errors.

### Objective
To develop practical Linux command-line skills used in L1 Application Support and Production Support roles.

### Tools and commands practiced
- `grep` – Search for specific log entries.
- `awk` – Filter records, extract fields, and count entries.
- `sed` – Replace text in command output.
- Pipes (`|`) – Combine Linux commands.
- Basic log investigation and troubleshooting.

### Tasks completed
1. Filtered ERROR entries.
2. Counted ERROR and WARN entries.
3. Identified failed login attempts.
4. Extracted usernames and timestamps.
5. Investigated payment-related entries.
6. Identified HTTP 500 server errors.
7. Counted errors by user.
8. Created modified log output without changing the original file.
9. Investigated whether a failed payment was successful on a later attempt.

### Key findings
- Total ERROR entries: 9
- Total WARN entries: 6
- HTTP 500 errors: 3
- Rahul's payment failed at 09:43:29 and a later payment entry showed status 200 at 09:44:46.

### What I learned
- How to search and filter application logs using Linux.
- How to extract useful information from log files.
- How to count and investigate errors.
- How to correlate events using timestamps, usernames, and actions.
- How basic Linux commands support application troubleshooting.

### Practice level
Beginner – L1 Application / Production Support

### Next step
Continue with Day 2 log investigation and gradually improve Linux command-line skills.

---
This is a personal learning project using simulated application log data. It does not contain actual company production logs.
