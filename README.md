# Archived Policy Pages from VRChat and Meta Horizon Worlds

This repository exists solely for scholarly documentation and analysis of
publicly accessible platform policies.

## Legal Notice
The texts and materials contained within the archived web pages originate from
VRChat Inc. and Meta Platforms Inc. and remain under copyright
and usage rights.

The archived contents are provided for non-commercial scholarly analysis only,
in accordance with § 60c UrhG for scientific purposes.

The repository itself (structure, file organization, metadata) is provided
without its own license and may be used only within the scope of academic
research, citation, and documentation.

No commercial use. No redistribution of the archived contents outside academic scholarship.

---

## Download

- **VRChat Policy Archive (WACZ, 11.1 MB)**  
  [Download from GitHub Releases](https://github.com/nikolaspfannenschmidt/spatial_turn_in_content_moderation_archive/releases/download/v1.0/vrchat_120125.wacz)

- **Meta Horizon Worlds Policy Archive (WACZ, 92.1 MB)**  
  [Download from GitHub Releases](https://github.com/nikolaspfannenschmidt/spatial_turn_in_content_moderation_archive/releases/download/v1.0/meta-horizon-worlds_120125.wacz)

Both platform archive files can be downloaded from this public GitHub repository
in an industry-standard web archive format (WACZ) for viewing in the interactive
webpage player **ReplayWeb.page** (https://replayweb.page).

---

## Exceptions and alternative archiving

Two VRChat Help Center pages could not be reliably archived as WACZ using
Webrecorder-based capture due to technical restrictions of the hosting setup
(e.g., JavaScript-dependent delivery and restrictive security policies), which
prevented generating a stable, complete capture.

These pages are therefore documented via the **Internet Archive Wayback Machine**
as an alternative archival source:

- **Safety Resources For Players (VRChat Help Center)**  
  Source: https://help.vrchat.com/hc/en-us/articles/33302819755539-Safety-Resources-For-Players  
  Wayback snapshot: https://web.archive.org/web/20250810213246/https://help.vrchat.com/hc/en-us/articles/33302819755539-Safety-Resources-For-Players

- **Safety Resources For Parents (VRChat Help Center)**  
  Source: https://help.vrchat.com/hc/en-us/articles/33301610887443-Safety-Resources-For-Parents  
  Wayback snapshot: https://web.archive.org/web/20250810225708/https://help.vrchat.com/hc/en-us/articles/33301610887443-Safety-Resources-For-Parents

---

## Verification

Verify the integrity of the downloadable WACZ files.

### Expected SHA-256 checksums

| Platform | File name | SHA-256 checksum |
|---|---|---|
| **VRChat** | `vrchat_120125.wacz` | `3bddaf202644c8fdef172127868d1feda3ff52dc6a4f600d99faf6ef7c0023df` |
| **Meta Horizon Worlds** | `meta-horizon-worlds_120125.wacz` | `80da55cec8fd2770c496f1aa54076d6f84867c037e622d686b2b265e4d14d93c` |


## macOS / Linux / Windows
Use the following commands to verify the file integrity:

# macOS / Linux
shasum -a 256 vrchat_120125.wacz
shasum -a 256 meta-horizon-worlds_120125.wacz

# or using sha256sum
sha256sum vrchat_120125.wacz
sha256sum meta-horizon-worlds_120125.wacz

# Windows (PowerShell)
Get-FileHash .\vrchat_120125.wacz -Algorithm SHA256
Get-FileHash .\meta-horizon-worlds_120125.wacz -Algorithm SHA256
