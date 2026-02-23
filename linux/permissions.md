# Linux File Permissions

Linux follows a three-level permission model:

- User (Owner)
- Group
- Others

Each file and directory has permission settings that control access.

---

## Permission Values

| Symbol | Meaning | Value |
|--------|----------|--------|
| r      | Read     | 4      |
| w      | Write    | 2      |
| x      | Execute  | 1      |

Permissions are calculated by adding values.

Example:

7 = 4 + 2 + 1 (rwx)  
5 = 4 + 0 + 1 (r-x)  
6 = 4 + 2 + 0 (rw-)

---

## Numeric Permission Example

`chmod 755 file.txt`

- Owner → rwx (7)
- Group → r-x (5)
- Others → r-x (5)

---

## Important Commands

- `ls -l` : View permissions
- `chmod` : Change permissions
- `chown` : Change ownership
- `groups` : Show group membership

---

## Why "Permission Denied" Happens

- No execute permission on directory
- No read permission on file
- Wrong ownership
- Missing sudo privileges
