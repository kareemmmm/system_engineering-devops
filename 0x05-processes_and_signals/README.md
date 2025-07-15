# 0x05. Processes and Signals

## Description

This project is part of the ALX System Engineering & DevOps track. It introduces and explores **process management**, **signals**, and **process control** in a Unix-based system using Bash scripts.

We cover topics such as:
- Getting process IDs (PIDs)
- Listing running processes
- Filtering processes (e.g., bash)
- Sending signals like `SIGTERM`
- Writing infinite loops
- Signal handling using `trap`

---

## Tasks

| File Name | Description |
|-----------|-------------|
| `0-what-is-my-pid` | Displays the script’s own PID |
| `1-list_your_processes` | Lists all running processes in a user-oriented format |
| `2-show_your_bash_pid` | Displays processes containing the word "bash" (using `ps`) |
| `3-show_your_bash_pid_made_easy` | Displays PIDs and names of bash-related processes (no `ps`) |
| `4-to_infinity_and_beyond` | Infinite loop printing a message every 2 seconds |
| `5-dont_stop_me_now` | Kills the `4-to_infinity_and_beyond` process |
| `6-stop_me_if_you_can` | Stops the infinite loop **without** using `kill` |
| `7-highlander` | Handles `SIGTERM` signal and prints "I am invincible!!!" |
| `67-stop_me_if_you_can` | Sends `SIGTERM` to `7-highlander` |
| `8-beheaded_process` | Kills the `7-highlander` process |

---

## How to Run

1. Make sure the scripts are executable:

```bash
chmod +x <filename>
