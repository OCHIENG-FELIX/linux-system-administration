# Linux File Permissions

## Overview
Linux permissions control who can read, write, or execute files and directories.

## Permission Types

| Permission | Symbol | Meaning |
|---|---|---|
| Read | r | View file contents |
| Write | w | Modify file contents |
| Execute | x | Execute a file or access a directory |

## Permission Categories
- Owner: The user who owns the file.
- Group: Users belonging to the assigned group.
- Others: All other users.

## Viewing Permissions
```bash
ls -l
```

Example:

```text
-rwxr-xr-- 1 user staff 1200 notes.sh
```

This indicates:
- Owner: Read, write, execute.
- Group: Read and execute.
- Others: Read only.

## Changing Permissions

### Symbolic Method
```bash
chmod u+x script.sh
```

### Numeric Method
```bash
chmod 755 script.sh
```

Common permission values:
- 644: Owner can read/write; group and others can read.
- 755: Owner has full permissions; group and others can read and execute.
- 700: Owner has full permissions; others have no permissions.

## Changing Ownership
```bash
sudo chown username:groupname notes.txt
```

## Important Security Considerations
- Avoid granting unnecessary permissions.
- Do not use `chmod 777` as a routine fix.
- Protect sensitive configuration files.
- Verify ownership before changing permissions.

## Relevance to IT Support
Understanding permissions helps resolve access-denied errors and maintain secure access to system resources.
