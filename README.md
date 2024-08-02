THIS IS MY SECOND READ ME MAKING IT VISIBLE
-----------------------------------------------
Q1. What is Logging?
Logging is the process of recording information about the operation of a software application. This information,
typically stored in log files or systems, can include messages, errors, warnings, and other data generated by the application as it runs.
 Logs help developers and administrators understand the application's behavior, troubleshoot issues, and monitor performance.

Q2. Why Logging is Important
Logging is important for several reasons:

-Debugging and Troubleshooting:
Logs provide insights into what the application was doing at the time of an error or unexpected behavior. 
This makes it easier to diagnose and fix problems.

-Monitoring and Performance:
By analyzing logs, you can monitor the application's performance, track resource usage,
and identify bottlenecks or inefficiencies.

-Security:
Logs can record access attempts, changes in application state, and other security-related events.
This helps in detecting and investigating potential security breaches.

-Audit Trails:
Logging provides a record of system activity that can be useful for auditing purposes. 
This is crucial for compliance with regulatory standards.

-Understanding Application Behavior:
Logs offer insights into how the application is used and how it behaves under different conditions. 
This information can be used for improving functionality and user experience.

-Historical Data:
Logs can provide historical data that can be useful for analyzing trends, performing long-term diagnostics, 
and understanding the application's evolution over time.

Q3. Understanding Logging Levels
Logging levels (or log levels) indicate the severity or importance of the log message. Different logging frameworks
and tools might use slightly different levels, but common ones include:

DEBUG:
Purpose: To provide detailed information, typically used during development and debugging.
Example: Method entry and exit points, variable values.

INFO:
Purpose: To convey general information about the application's state or progress.
Example: Successful completion of a task, system startup.

WARN:
Purpose: To indicate a potential issue that doesn’t necessarily cause immediate problems but may require attention.
Example: Deprecated API usage, minor configuration issues.

ERROR:
Purpose: To report errors that have caused a failure or disruption in functionality.
Example: Exception stack traces, failed database queries.

FATAL (or CRITICAL):
Purpose: To signal severe errors that cause the application to terminate or require immediate attention.
Example: Out of memory errors, critical system failures.

TRACE (less common):
Purpose: To provide extremely detailed information, often including fine-grained data about the application's behavior.
Example: Detailed execution path information, low-level debug data.