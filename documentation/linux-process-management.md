# Linux Process Management

## Overview
A process is a running instance of a program.

Linux administrators monitor and manage processes to maintain system performance and resource availability.

## Essential Commands

### Display Running Processes
```bash
ps aux
```

### Display Processes in Real Time
```bash
top
```

### Search for a Process
```bash
pgrep processname
```

### Display Process Information
```bash
ps -p PID -f
```

### Terminate a Process
```bash
kill PID
```

### Forcefully Terminate a Process
```bash
kill -9 PID
```

Use forceful termination only when necessary because it does not allow the process to clean up normally.

## Process Identification
Each running process has a Process ID (PID).

The PID helps administrators identify and manage individual processes.

## Troubleshooting High Resource Usage
1. Open `top`.
2. Identify processes consuming excessive CPU or memory.
3. Investigate the affected application.
4. Determine whether the usage is expected.
5. Apply an appropriate resolution.
6. Verify system performance.

## Relevance to IT Support
Process management helps diagnose slow systems, unresponsive applications, and excessive resource utilization.
