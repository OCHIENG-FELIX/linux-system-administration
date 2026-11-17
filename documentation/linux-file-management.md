# Linux File Management

## Overview
Linux provides commands for creating, copying, moving, viewing, and deleting files and directories.

## Essential Commands

### Create a Directory
```bash
mkdir projects
```

### Create an Empty File
```bash
touch notes.txt
```

### Copy a File
```bash
cp notes.txt backup.txt
```

### Move or Rename a File
```bash
mv notes.txt documents/
```

### Remove a File
```bash
rm notes.txt
```

### Remove an Empty Directory
```bash
rmdir projects
```

### Display File Contents
```bash
cat notes.txt
```

### View Long Files
```bash
less notes.txt
```

### Search for Text
```bash
grep "error" system.log
```

### Find Files
```bash
find /home -name "notes.txt"
```

## Important Considerations
- Confirm the current directory before modifying files.
- Verify file paths before deleting content.
- Avoid destructive commands unless necessary.
- Use elevated privileges only when authorized.
- Maintain backups of important files.

## Relevance to IT Support
File management is essential when organizing user files, reviewing logs, managing system configuration, and performing routine administration.
