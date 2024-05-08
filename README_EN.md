<p align="center">
<img src="https://hits.seeyoufarm.com/api/count/keep/badge.svg?url=https%3A%2F%2Fip.check.place&count_bg=%2379C83D&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=runs&edge_flat=false"/> 
<img src="https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Fxykt%2FIPQuality&count_bg=%233DC8C0&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=visits&edge_flat=false"/> 
<a href="/LICENSE"><img src="https://img.shields.io/badge/License-AGPL%20v3-blue.svg" alt="license" /></a>  
</p>

## IP Quality Check Script  -  [IP质量体检脚本 (中文)](https://github.com/xykt/IPQuality/blob/main/README.md)

**Supported OS/Platform: Ubuntu | Debian | Linux Mint | Fedora | Red Hat Enterprise Linux (RHEL) | CentOS | Arch Linux | Manjaro | Alpine Linux**

- Bilingual support in English and Chinese
- Supports dual-stack queries for IPv4/IPv6
- Beautifully formatted, intuitive display, optimized for single-screen multi-terminal display, facilitating screenshot sharing
- Six modules: Basic Information, IP Type, Risk Score, Risk Factors, Streaming Media Unlocking, and Post Office Check
- Basic data sourced from the *Maxmind* database
- Risk information integrated from multiple databases: *IPinfo / ipregistry / ipapi / AbuseIPDB / IP2LOCATION / IPQS / DB-IP / SCAMALYTICS / IPWHOIS*
- Streaming and AI service providers' unlocking and type detection: *TikTok / Disney+ / Netflix / Youtube / AmazonPrimeVideo / Spotify / ChatGPT*
- Connectivity tests for multiple email providers: *Gmail / Outlook / Yahoo / Apple / QQ / Mail.ru / AOL / GMX / Mail.com / 163 / Sohu / Sina*
- Over 400 IP address blacklist database checks

##### Screenshots
![Screenshot](https://raw.githubusercontent.com/xykt/IPQuality/main/img/en_ipv4.png)

## How to Use

##### Default dual-stack test:
````bash
bash <(curl -Ls IP.Check.Place)
````

##### IPv4 only test:
````bash
bash <(curl -Ls IP.Check.Place) -4
````

##### IPv6 only test:
````bash
bash <(curl -Ls IP.Check.Place) -6
````

##### Set script language to English:
````bash
bash <(curl -Ls IP.Check.Place) -l en
````

## Script Updates

2024/05/08 00:00 Script released

## Script Contributions

**Acknowledgments:**

- Thanks to [lmc999](https://github.com/lmc999/RegionRestrictionCheck) for portions of the original streaming media unlocking script referenced in this script.

- Thanks to [spiritLHLS](https://github.com/spiritLHLS/ecs) for portions of the integration monster review script referenced in this script.

**Contributors:**

<a href="https://github.com/xykt"><img src="https://avatars.githubusercontent.com/u/152045469?v=4" alt="@xykt" size="48" height="48" width="48" data-view-component="true"></img></a>

**Stars History:**
![Stargazers over time](https://starchart.cc/xykt/IPQuality.svg?background=%23FFFFFF&axis=%23333333&line=%2377dd77)