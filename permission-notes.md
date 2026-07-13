# Linux Permissions Notes

## Initial Observations

- Reviewed existing file permissions using `ls -l`.
- Verified the project directory structure.

## Permission Changes

- Applied `755` to `scripts/backup.sh`.
- Applied `644` to `documents/report.txt`.
- Applied `600` to `private/passwords.txt`.

## Verification

Confirmed all permission changes using `ls -l`.

## Key Takeaways

- Executable scripts require execute permissions.
- Shared documents commonly use `644`.
- Sensitive files should be restricted with `600`.