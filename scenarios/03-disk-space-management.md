# Scenario 3: Disk Space Management

## Problem Description
A Linux system reports low disk space, potentially affecting applications and system operations.

## Symptoms
- Applications cannot save files.
- System reports insufficient storage.
- Logs or temporary files consume significant space.
- System operations fail.

## Possible Causes
- Large log files.
- Accumulated temporary files.
- Large user files.
- Unnecessary application data.
- Expanding system backups.

## Diagnostic Procedure
1. Run `df -h` to inspect filesystem usage.
2. Use `du -sh` to inspect directory sizes.
3. Identify unusually large files and directories.
4. Review log and temporary file growth.
5. Determine which files can safely be archived or removed.

## Possible Resolutions
- Archive approved files.
- Remove unnecessary files after verification.
- Apply approved log rotation procedures.
- Escalate storage capacity issues.

## Verification
Run `df -h` again and confirm sufficient storage is available.

## Security Considerations
Never delete system files or logs without understanding their purpose and obtaining appropriate authorization.

## Status
Documentation prepared. Practical testing pending.
