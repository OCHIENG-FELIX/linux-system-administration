# Scenario 4: Process Management

## Problem Description
A Linux system becomes slow because one or more processes may be consuming excessive resources.

## Symptoms
- Applications respond slowly.
- CPU utilization is unusually high.
- Memory usage is excessive.
- System becomes unresponsive.

## Possible Causes
- Resource-intensive applications.
- Unresponsive processes.
- Too many running applications.
- Software defects.

## Diagnostic Procedure
1. Run `top`.
2. Inspect CPU and memory utilization.
3. Identify processes consuming excessive resources.
4. Record the process ID.
5. Investigate the application before terminating it.

## Possible Resolutions
- Close unnecessary applications through normal procedures.
- Restart an affected service if authorized.
- Terminate a confirmed unresponsive process using an appropriate signal.
- Escalate persistent application or system issues.

## Verification
Monitor CPU and memory usage after the corrective action.

## Important Considerations
Do not terminate critical system processes without understanding their purpose.

## Status
Documentation prepared. Practical testing pending.
