# Simple Steganography

## Summary
Extract hidden data from an image using steganography tools.

## Tools Used
- `exiftool`
- `strings`
- `grep`
- `steghide`
- Base64 decode

## Key Commands
- `exiftool image.jpg` — check metadata, nothing flag-related
- `strings image.jpg | grep ctf` — no direct flag found
- `steghide extract -sf image.jpg` — extracted `raw.txt`
- `cat raw.txt` — base64 string found
- Decode base64 to get the flag

## Observations
- Metadata hinted at "myadmin" but no flag there.
- Steghide successfully extracted a hidden file.
- Flag encoded in base64 inside the extracted text.

## Flag
Decoded from base64 in extracted file.
