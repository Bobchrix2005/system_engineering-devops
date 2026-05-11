# 0x05-processes_and_signals

This project introduces Linux process management and signals using Bash scripts.

## Files

| File | Description |
|------|-------------|
| 0-what-is-my-pid | Displays the PID of the current script |
| 1-list_your_processes | Lists all running processes |
| 2-show_your_bash_pid | Displays lines containing bash |
| 3-show_your_bash_pid_made_easy | Displays PID and process name for bash |
| 4-to_infinity_and_beyond | Infinite loop displaying a message every 2 seconds |
| 5-dont_stop_me_now | Stops the 4-to_infinity_and_beyond process using kill |
| 6-stop_me_if_you_can | Stops the 4-to_infinity_and_beyond process without kill or killall |
| 7-highlander | Infinite loop that handles SIGTERM |
| 67-stop_me_if_you_can | Sends SIGTERM to 7-highlander |
| 8-beheaded_process | Kills 7-highlander using SIGKILL |

## Requirements

- Ubuntu/Linux environment
- Bash shell
- All scripts must be executable

## Make scripts executable

```bash
chmod +x *
