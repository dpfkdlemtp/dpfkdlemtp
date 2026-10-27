# Vulnerability Research & Responsible Disclosure

Publicly verifiable vulnerability research by **Tae-Hoon Ha (hataehoon)**. My GitHub handle in the public records is `dpfkdlemtp`.

## Published CVEs

| CVE / case page | Project | Attribution | Official CVE record |
| --- | --- | --- | --- |
| [CVE-2026-116192](https://github.com/rclone/rclone/security/advisories/GHSA-xqmq-v4wj-rw5m) | rclone | Reporter (`dpfkdlemtp`) | [CVE record](https://github.com/CVEProject/cvelistV5/blob/main/cves/2026/116xxx/CVE-2026-116192.json) |
| [CVE-2026-110860](https://github.com/gitpython-developers/GitPython/security/advisories/GHSA-gq48-pqfc-9p58) | GitPython | Reporter (`dpfkdlemtp`) | [CVE record](https://github.com/CVEProject/cvelistV5/blob/main/cves/2026/110xxx/CVE-2026-110860.json) |
| [CVE-2026-100633](https://github.com/dpfkdlemtp/CVE-2026-100633) | SiYuan | Reporter (`dpfkdlemtp`) | [CVE record](https://github.com/CVEProject/cvelistV5/blob/main/cves/2026/100xxx/CVE-2026-100633.json) |
| [CVE-2021-43716](https://github.com/dpfkdlemtp/CVE-2021-43716) | Epson EH-TW5350 | B-BEAM-BOB team research | [CVE record](https://github.com/CVEProject/cvelistV5/blob/main/cves/2021/43xxx/CVE-2021-43716.json) |
| [CVE-2021-43717](https://github.com/dpfkdlemtp/CVE-2021-43717) | Epson EH-TW5350 | B-BEAM-BOB team research | [CVE record](https://github.com/CVEProject/cvelistV5/blob/main/cves/2021/43xxx/CVE-2021-43717.json) |
| [CVE-2021-43718](https://github.com/dpfkdlemtp/CVE-2021-43718) | Epson EH-TW5350 | B-BEAM-BOB team research | [CVE record](https://github.com/CVEProject/cvelistV5/blob/main/cves/2021/43xxx/CVE-2021-43718.json) |

The three Epson CVEs came from **one team research project**, not three independent solo discoveries. The [original team advisory collection](https://github.com/dpfkdlemtp/epson-eh-tw5350-advisories) is the canonical reference linked by the CVE records and lists Tae-Hoon Ha among the researchers. The [SiYuan GitHub security advisory](https://github.com/siyuan-note/siyuan/security/advisories/GHSA-9g6v-r3xf-673q) lists `dpfkdlemtp` as reporter.

For SiYuan, [GitHub declined a second CVE assignment](https://github.com/siyuan-note/siyuan/security/advisories/GHSA-9g6v-r3xf-673q#advisory-comment-311744) because CVE-2026-100633 already exists. The official CVE record is published and references that GHSA; the GHSA CVE field has not yet been linked to it.

## Selected Public Security Advisories

These published advisories credit `dpfkdlemtp` as Reporter and identify patched versions.

### High severity

| Project | Published advisory | Severity | Patched versions |
| --- | --- | --- | --- |
| dbt Core | [Arbitrary file overwrite during dependency resolution](https://github.com/dbt-labs/dbt/security/advisories/GHSA-xwgp-43x8-639j) | High | 1.12.6 / 1.11.16 |
| Datasette | [Table permission bypass](https://github.com/simonw/datasette/security/advisories/GHSA-h547-rmjf-5m2m) | High | 0.65.5 / 1.0a40 |
| TwelveMonkeys | [Excessive memory allocation in the PICT image reader](https://github.com/haraldk/TwelveMonkeys/security/advisories/GHSA-859w-fq5p-6c86) | High | 3.15.1 |
| Kaneo | [Outbound destination validation bypass](https://github.com/usekaneo/kaneo/security/advisories/GHSA-w4gj-hv53-f2pj) | High | 2.47.1 |

### Additional selected projects

| Project | Published advisory | Severity | Patched versions |
| --- | --- | --- | --- |
| GitPython | [Symlink-based path traversal in Submodule.move()](https://github.com/gitpython-developers/GitPython/security/advisories/GHSA-gq48-pqfc-9p58) | Moderate | >= 3.2.0 |
| rclone | [Server-side request forgery in named remote roots](https://github.com/rclone/rclone/security/advisories/GHSA-xqmq-v4wj-rw5m) | Moderate | 1.74.2 |
| AngleSharp | [SVG serialization mutation XSS](https://github.com/AngleSharp/AngleSharp/security/advisories/GHSA-cgp3-27rh-pcp2) | Moderate | >= 1.8.2 |
| Sonos tract (ONNX inference) | [Symlink traversal in ONNX external data loading](https://github.com/sonos/tract/security/advisories/GHSA-7q44-75hx-2x3h) | Moderate | 0.21.19 / 0.22.5 / 0.23.9 |

Advisory links, reporter credit, and patched versions verified on 2026-10-27. Severities follow the project advisories. Published CVE records are listed above; an advisory's CVE field may not yet reflect an existing CVE record.

Only publicly disclosed, verifiable work is listed here.
