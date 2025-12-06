# Blue Team Guide: Platform Security Controls 🔵

This guide outlines key controls defenders should implement to secure firmware.

## Core Principles
- Establish **root of trust** in firmware.
- Reduce attack surface by disabling unnecessary features.
- Monitor and measure firmware integrity.

## Security Controls
1. **UEFI Secure Boot** → Only trusted bootloaders.
2. **Intel Boot Guard** → CPU verifies BIOS authenticity.
3. **TPM Integration** → Store and verify measurements.
4. **Firmware Update Policy** → Use vendor-signed updates only.
5. **Monitoring Tools** → Deploy Chipsec or vendor tools for integrity checking.

## Defensive Operations
- Automate firmware compliance checks.
- Maintain inventory of firmware versions.
- Validate supply chain firmware integrity
