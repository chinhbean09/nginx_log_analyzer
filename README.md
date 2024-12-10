# Nginx Log Analyzer
The project from: https://roadmap.sh/projects/nginx-log-analyser
A simple Bash script to analyze Nginx access logs and extract useful insights.

## Features

This script provides:
- **Top 5 IP addresses** with the most requests.
- **Top 5 most requested paths**.
- **Top 5 response status codes**.
- **Top 5 user agents**.

## Requirements

- A Unix-based system (Linux or macOS) with Bash.
- The following commands installed:
  - `awk`
  - `sort`
  - `uniq`
  - `head`
- Nginx access log file in the **common log format**.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/nginx-log-analyzer.git
   cd nginx-log-analyzer
   ```
2. Make the script executable
  ```bash
  chmod +x nginx_log_analyzer.sh
  ```
## Usage
Run the script with your Nginx log file as an argument:
 ```bash
./nginx_log_analyzer.sh <nginx_access_log>
  ```

