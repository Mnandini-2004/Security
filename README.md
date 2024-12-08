# Security
Log Analysis
This project involves creating a Python script to analyze web server log files for security and traffic insights. The script will process a log file containing entries about web requests and extract key information like the frequency of requests from different IP addresses, the most accessed resources, and any suspicious activity, such as repeated failed login attempts.

Key Features:
Request Analysis: Count the number of requests made by each IP address and display them in descending order.
Resource Usage: Identify the most frequently accessed endpoint, such as specific pages or resources on the server.
Suspicious Activity Detection: Flag IP addresses showing signs of potential brute force attacks by tracking repeated failed login attempts.
Results Summary: Present the findings both in the terminal and save them into a well-structured CSV file for later reference.
