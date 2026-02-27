# ASD Blueprint Configuration Tool for Windows 365

An interactive, self-contained tool that maps ASD Essential Eight controls to Microsoft Intune policies for Windows 365 Cloud PCs. Select your target maturity level, review configurations, and download importable JSON policy packages.

**[Open the Tool →](https://sumitsadhu.github.io/w365-asd-blueprint/)**

## Features

- **76 policies** mapped across all 8 Essential Eight pillars + W365-specific + ISM controls
- **One-click ML1/ML2/ML3 presets** with ISM control traceability (67/79/89 ISM controls)
- **9 importable JSON policies** (362 settings) — all tenant-tested with 100% import success
- **Conflict detection** — prevents selecting policies with overlapping settingDefinitionIds
- **W365-optimized** — pre-built ACSC Windows Hardening variant (RDP enabled, physical device settings removed)
- **Scenario presets** — Corporate, Contractor/BYOD, Jump Host, Secure Enclave
- **Deployment checklist** with phased rollout guidance
- **PowerShell bulk import script** included in ZIP download
- **CSV export** for audit and compliance documentation
- **Zero dependencies** — single HTML file, works offline

## JSON Policies (Tenant-Tested)

| Policy | Settings | Source | Status |
|--------|----------|--------|--------|
| ACSC Windows Hardening (W365) | 220 | ACSC GitHub (modified) | ✅ Imported |
| ACSC Office Hardening | 82 | ACSC GitHub | ✅ Imported |
| ACSC Macros Trusted Publishers | 58 | ACSC GitHub | ✅ Imported |
| Disable All VBA Macros | 40 | ACSC GitHub | ✅ Imported |
| ACSC Edge Hardening | 12 | ACSC GitHub | ✅ Imported |
| ACSC ASR Rules (5 rules) | 1 (grouped) | Tenant-exported | ✅ Imported |
| Advanced Audit Policy | 3 | Validated | ✅ Imported |
| Defender Network Protection | 1 | Validated | ✅ Imported |
| Defender AV Configuration | 3 | Validated | ✅ Imported |

## Data Sources

- [Microsoft ACSC Intune Hardening Guidelines](https://github.com/microsoft/Intune-ACSC-Windows-Hardening-Guidelines) — official policy JSON files
- [ASD Essential Eight Maturity Model](https://www.cyber.gov.au/resources-business-and-government/essential-cyber-security/essential-eight/essential-eight-maturity-model)
- [Australian Information Security Manual (ISM)](https://www.cyber.gov.au/resources-business-and-government/essential-cyber-security/ism)

## Disclaimer

This tool is an **unofficial community resource**. It is **not affiliated with, endorsed by, or a product of Microsoft, the Australian Signals Directorate (ASD), or the Australian Cyber Security Centre (ACSC)**.

Use of these configurations does **not** constitute or guarantee compliance with the ASD Essential Eight, the Information Security Manual (ISM), or any other regulatory framework. Compliance requires formal assessment by an IRAP assessor or equivalent.

All configurations **must** be tested in a non-production environment before deployment. The deploying organisation assumes all risk.

## Author

**Sumit Sadhu**

## License

MIT
