````markdown
# File Permissions

## View Permissions

```bash
ls -l
```

## Change Permissions

```bash
chmod 755 file.txt
```

## Change Ownership

```bash
chown user:user file.txt
```

## Numeric Permissions

| Number | Meaning |
|----------|---------|
| 7 | rwx |
| 6 | rw- |
| 5 | r-x |
| 4 | r-- |

## Notes

Linux permissions determine who can read, write, and execute files and directories.
````
