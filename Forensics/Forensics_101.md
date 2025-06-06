# Forensics 101

## Summary
Extract meaningful data from large noisy binary files.

## Tools Used
- `exiftool`
- `strings`
- `less`
- `binwalk` (attempted)

## Key Commands
- `strings file | less` — skimmed large output
- `binwalk file` — no useful info found

## Observations
- The flag was buried in the large string output.
- Needed to carefully read/skimming the strings output to find the flag.

## Flag
Found by reading the large strings output carefully.