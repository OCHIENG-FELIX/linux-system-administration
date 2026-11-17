# Linux User Management

## Overview
Linux supports multiple user accounts, allowing different individuals and services to access system resources according to assigned permissions.

## Important Concepts

### Root User
The root account has administrative privileges across the system.

### Standard User
A standard user has limited permissions and normally cannot perform administrative tasks without authorization.

### Groups
Groups allow administrators to assign permissions to multiple users collectively.

## Essential Commands

### Display Current User
```bash
whoami
```

### Display Logged-In Users
```bash
who
```

### Create a User
```bash
sudo adduser username
```

### Modify a User
```bash
sudo usermod -aG groupname username
```

### Change a Password
```bash
sudo passwd username
```

### Delete a User
```bash
sudo deluser username
```

### Display User Groups
```bash
groups username
```

## Administrative Considerations
- Verify the identity and authorization of account requesters.
- Apply the principle of least privilege.
- Avoid sharing user accounts.
- Remove or disable accounts according to organizational policy.
- Never disclose passwords.

## Relevance to IT Support
User management is important when onboarding employees, managing access, resetting passwords, and maintaining system security.
