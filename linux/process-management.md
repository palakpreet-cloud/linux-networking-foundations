# Linux Process Management

A process is a running instance of a program. Managing processes is important in Linux servers and cloud environments.

---

## Viewing Running Processes

- `ps` → Shows running processes
- `ps aux` → Detailed process list
- `top` → Real-time monitoring
- `jobs` → Shows background jobs

---

## Running a Process in Background

Command:
sleep 200 &

The `&` runs the process in background.
The system assigns a Process ID (PID).

---

## Finding a Process

Command:
ps aux | grep sleep

This displays the sleep process along with its PID.

---

## Killing a Process

To stop a process:
kill PID

Replace PID with the actual process ID.

Force kill:
kill -9 PID

---

## Importance of Process Management

- Monitor system performance
- Stop unwanted programs
- Manage server applications
- Troubleshoot system issues
