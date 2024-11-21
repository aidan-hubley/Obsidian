# Anti-Rootkits
- How do you know your computer doesn't have rootkit right now?
- Signature
	- Discernable pattern

# Linux Logging
- /var/log
- syslog-ng, rsyslog, journald
- Log Types
	- System Logs - Health and Operation of the System
	- Application Logs - Specific applications
	- Security Logs - Security related events
- Log Viewing
- Log Permissions

## Logging Levels
- Debug, Info, Notice, Warning, Error, Critical
- Set by the application
- Cat /proc/sys/kernel/printk
	- To level the levels of warning severity

## Windows 