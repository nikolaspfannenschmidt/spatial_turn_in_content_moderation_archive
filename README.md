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

- **Coding Table (PDF, 4.82 MB)**
  [Download from Github Repository](https://github.com/nikolaspfannenschmidt/spatial_turn_in_content_moderation_archive/blob/main/Coding%20Table%20TaSiSXR.pdf)

- **VRChat Policy Archive (WACZ, 11.1 MB)**  
  [Download from GitHub Releases](https://github.com/nikolaspfannenschmidt/spatial_turn_in_content_moderation_archive/releases/download/v1.0/vrchat_110625.wacz)

- **Meta Horizon Worlds Policy Archive (WACZ, 92.1 MB)**  
  [Download from GitHub Releases](https://github.com/nikolaspfannenschmidt/spatial_turn_in_content_moderation_archive/releases/download/v1.0/meta-horizon-worlds_110625.wacz)

Both platform archive files can be downloaded from this public GitHub repository
in an industry-standard web archive format (WACZ) for viewing in the interactive
webpage player **ReplayWeb.page** (https://replayweb.page).

---

## Exceptions and alternative archiving

Two VRChat Help Center pages could repeatedly not be reliably archived as WACZ using
Webrecorder-based capture due to technical restrictions of the hosting setup, which
prevented generating a stable, complete capture.

These pages are therefore documented via the **Internet Archive Wayback Machine**
as an alternative archival source:

- **Safety Resources For Players (VRChat Help Center, published 05/28/2025, accessed 08/10/2025)**  
  Source: https://help.vrchat.com/hc/en-us/articles/33302819755539-Safety-Resources-For-Players  
  Wayback snapshot: https://web.archive.org/web/20250810213246/https://help.vrchat.com/hc/en-us/articles/33302819755539-Safety-Resources-For-Players

- **Safety Resources For Parents (VRChat Help Center, published 09/11/2024, accessed 08/10/2025)**  
  Source: https://help.vrchat.com/hc/en-us/articles/33301610887443-Safety-Resources-For-Parents  
  Wayback snapshot: https://web.archive.org/web/20250810225708/https://help.vrchat.com/hc/en-us/articles/33301610887443-Safety-Resources-For-Parents

---

## Verification

Verify the integrity of the downloadable WACZ files.

### Expected SHA-256 checksums

| Platform | File name | SHA-256 checksum |
|---|---|---|
| **VRChat** | `vrchat_110625.wacz` | `3bddaf202644c8fdef172127868d1feda3ff52dc6a4f600d99faf6ef7c0023df` |
| **Meta Horizon Worlds** | `meta-horizon-worlds_110625.wacz` | `80da55cec8fd2770c496f1aa54076d6f84867c037e622d686b2b265e4d14d93c` |


# macOS / Linux / Windows
Use the following commands to verify the file integrity:

## macOS / Linux
shasum -a 256 vrchat_1110625.wacz
shasum -a 256 meta-horizon-worlds_110625.wacz

## or using sha256sum
sha256sum vrchat_110625.wacz
sha256sum meta-horizon-worlds_110625.wacz

## Windows (PowerShell)
Get-FileHash .\vrchat_110625.wacz -Algorithm SHA256
Get-FileHash .\meta-horizon-worlds_110625.wacz -Algorithm SHA256
