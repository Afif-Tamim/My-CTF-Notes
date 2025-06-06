# red

## Summary
Extract data from PNG image using specialized stego tools.

## Tools Used
- `exiftool`
- `binwalk`
- `zsteg`
- `CyberChef`

## Key Commands
- `binwalk red.png` — found compressed file inside
- `zsteg red.png` — extracted base64 string
- Decoded base64 with CyberChef to get flag

## Observations
- `steghide` unsupported for PNG files.
- Needed to use `binwalk` and `zsteg` for PNG stego.

## Flag
Decoded from base64 string extracted by `zsteg`.