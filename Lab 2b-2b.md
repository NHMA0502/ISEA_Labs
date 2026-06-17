# AWK Beginner's Guide

 Basic Syntax, Field References, Common Examples, Example Data and Special Blocks

<img width="956" height="632" alt="Screenshot 2026-06-17 130344" src="https://github.com/user-attachments/assets/928527c3-7d58-4978-a47a-7bdff6e8189c" />

Field Separator, Pass Variable to AWK, Quick Inline Test and Apache Log Example

<img width="660" height="681" alt="Screenshot 2026-06-17 130757" src="https://github.com/user-attachments/assets/0f2b567c-6076-4943-bbb5-545a23c64942" />

My Apache Log Example does not display the IP address

<img width="1036" height="96" alt="Screenshot 2026-06-17 130915" src="https://github.com/user-attachments/assets/50bb7c2c-fe6d-4e64-8b7d-07303c02dcb8" />

Chatgpt to find out the problem and show that Apache access log is empty.

Checking if the file is empty and indeed it's empty

<img width="798" height="308" alt="Screenshot 2026-06-17 131426" src="https://github.com/user-attachments/assets/89be172b-a165-4a66-bd00-a51a7e305ccf" />

Generate some web traffic

<img width="915" height="282" alt="Screenshot 2026-06-17 131801" src="https://github.com/user-attachments/assets/d631f575-9db3-4ac0-a4e6-737ecf7033fe" />

After generating some web traffic, then try to access the log 

<img width="1581" height="205" alt="Screenshot 2026-06-17 131740" src="https://github.com/user-attachments/assets/7b53cecf-f12e-44cb-b3fb-4041c3645e1e" />

-> awk '{ print $1, $9 } ' /var/log/apache2/access.log extracts the client IP address and the HTTP status code from the Apache access log.
This makes it easier to analyze who access the web server and whether each request was successful or returned another status. 

# Scripting to Extract only failed requests

I would need to create scripts hence in the first line the output stated as command not found.

<img width="657" height="468" alt="Screenshot 2026-06-17 133756" src="https://github.com/user-attachments/assets/4ff7a411-a87b-4c2a-bd74-024daf3bf81f" />

<img width="1742" height="496" alt="Screenshot 2026-06-17 134552" src="https://github.com/user-attachments/assets/9cdf7d84-df4b-449e-ae2e-f9be6e18bb67" />






