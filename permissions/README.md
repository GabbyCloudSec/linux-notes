# File Permissions

## View Permissions

```bash
ls -l
```

Example:

```text
-rwxr-xr-x 1 user user 4096 Jun 25 file.txt
```

## Change Permissions

```bash
chmod 755 file.txt
```

```bash
chmod 644 file.txt
```

## Change Ownership

```bash
chown user:user file.txt
```

## Numeric Permissions

| Number | Permission |
|----------|------------|
| 7 | rwx |
| 6 | rw- |
| 5 | r-x |
| 4 | r-- |
| 0 | --- |

## Common Permission Modes

| Mode | Description |
|--------|-------------|
| 755 | Owner has full access, others can read and execute |
| 700 | Owner has full access only |
| 644 | Owner can read and write, others can read |
| 600 | Owner can read and write only |

## Notes

File permissions determine who can read, write, and execute files and directories. Understanding permissions is essential for Linux administration and system security.

Linux permissions determine who can read, write, and execute files and directories.
````
