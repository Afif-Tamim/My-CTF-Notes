# DISKO 1

## Summary
Forensics on disk image to extract hidden data.

## Tools Used
- `exiftool`
- `strings`
- `grep`

## Key Commands
- `strings disk.img | grep "flag"` — used grep to filter strings

## Observations
- Grep helped narrow down useful strings in large output.

## Flag
Found within strings output filtered by grep.
