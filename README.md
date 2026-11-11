# Vulnerability Research & Responsible Disclosure

Publicly verifiable vulnerability research by **Tae-Hoon Ha (hataehoon)**. Public researcher credits use `dpfkdlemtp`, `hataehoon` or `Taehoon Ha`.

## Published CVEs

| CVE / case page | Project | Attribution | Official CVE record |
| --- | --- | --- | --- |
| [CVE-2026-118196](https://lists.apache.org/thread/2x7c9741d50xw3o10h92rk19cr55trof) | Apache Allura | Reporter (`hataehoon`) | [CVE record](https://github.com/CVEProject/cvelistV5/blob/main/cves/2026/118xxx/CVE-2026-118196.json) |
| [CVE-2026-109411](https://www.samba.org/samba/security/CVE-2026-109411.html) | Samba | Reporter (`hataehoon`) | [CVE record](https://github.com/CVEProject/cvelistV5/blob/main/cves/2026/109xxx/CVE-2026-109411.json) |
| [CVE-2026-118489](https://github.com/vert-x3/vertx-web/security/advisories/GHSA-xh2g-9hw9-mvp3) | Eclipse Vert.x | Finder (`dpfkdlemtp`) | [CVE record](https://github.com/CVEProject/cvelistV5/blob/main/cves/2026/118xxx/CVE-2026-118489.json) |
| [CVE-2026-111822](https://lists.apache.org/thread/b5gop0kwsm4sr1pgdrfcd14q8hx942j5) | Apache ActiveMQ Classic | Finder (`hataehoon`) | [CVE record](https://github.com/CVEProject/cvelistV5/blob/main/cves/2026/111xxx/CVE-2026-111822.json) |
| [CVE-2026-84161](https://github.com/Ericsson/codechecker/security/advisories/GHSA-w57m-6g36-jjwv) | Ericsson CodeChecker | Reporter (`dpfkdlemtp`) | [CVE record](https://github.com/CVEProject/cvelistV5/blob/main/cves/2026/84xxx/CVE-2026-84161.json) |
| [CVE-2026-111453](https://lists.apache.org/thread/z212137tkfobdgl0hnos7qg6w6r1mxw5) | Apache Airflow | Finder (`hataehoon`) | [CVE record](https://github.com/CVEProject/cvelistV5/blob/main/cves/2026/111xxx/CVE-2026-111453.json) |
| [CVE-2026-116192](https://github.com/rclone/rclone/security/advisories/GHSA-xqmq-v4wj-rw5m) | rclone | Reporter (`dpfkdlemtp`) | [CVE record](https://github.com/CVEProject/cvelistV5/blob/main/cves/2026/116xxx/CVE-2026-116192.json) |
| [CVE-2026-110860](https://github.com/gitpython-developers/GitPython/security/advisories/GHSA-gq48-pqfc-9p58) | GitPython | Reporter (`dpfkdlemtp`) | [CVE record](https://github.com/CVEProject/cvelistV5/blob/main/cves/2026/110xxx/CVE-2026-110860.json) |
| [CVE-2026-100633](https://github.com/dpfkdlemtp/CVE-2026-100633) | SiYuan | Reporter (`dpfkdlemtp`) | [CVE record](https://github.com/CVEProject/cvelistV5/blob/main/cves/2026/100xxx/CVE-2026-100633.json) |
| [CVE-2021-43716](https://github.com/dpfkdlemtp/CVE-2021-43716) | Epson EH-TW5350 | B-BEAM-BOB team research | [CVE record](https://github.com/CVEProject/cvelistV5/blob/main/cves/2021/43xxx/CVE-2021-43716.json) |
| [CVE-2021-43717](https://github.com/dpfkdlemtp/CVE-2021-43717) | Epson EH-TW5350 | B-BEAM-BOB team research | [CVE record](https://github.com/CVEProject/cvelistV5/blob/main/cves/2021/43xxx/CVE-2021-43717.json) |
| [CVE-2021-43718](https://github.com/dpfkdlemtp/CVE-2021-43718) | Epson EH-TW5350 | B-BEAM-BOB team research | [CVE record](https://github.com/CVEProject/cvelistV5/blob/main/cves/2021/43xxx/CVE-2021-43718.json) |

The three Epson CVEs came from **one team research project**. The [original team advisory collection](https://github.com/dpfkdlemtp/epson-eh-tw5350-advisories) is the canonical reference linked by those CVE records and lists Tae-Hoon Ha among the researchers.

The [SiYuan project advisory](https://github.com/siyuan-note/siyuan/security/advisories/GHSA-9g6v-r3xf-673q) now lists CVE-2026-100633 and credits `dpfkdlemtp` as Reporter.

## Selected Public Security Advisories

Selected public advisories with researcher credit. Severity labels and fixed versions follow the cited project advisories.

### Critical severity

| Project | Published advisory | Severity | Patched versions |
| --- | --- | --- | --- |
| Apache Allura | [OAuth1 rebinding](https://lists.apache.org/thread/2x7c9741d50xw3o10h92rk19cr55trof) | Critical | 1.22.1 |

### High severity

| Project | Published advisory | Severity | Patched versions |
| --- | --- | --- | --- |
| Samba | [Access-control bypass on Ceph RGW shares](https://www.samba.org/samba/security/CVE-2026-109411.html) | High | 4.25.1 |
| Eclipse Vert.x | [Cross-user disclosure through shared HTTP caching](https://github.com/vert-x3/vertx-web/security/advisories/GHSA-xh2g-9hw9-mvp3) | High | 4.5.36 / 5.2.3 |
| AngleSharp | [Quadratic attribute parsing causes CPU denial of service](https://github.com/AngleSharp/AngleSharp/security/advisories/GHSA-h5fx-ppwm-hhh5) | High | >= 1.8.2 |
| dbt Core | [Arbitrary file overwrite during dependency resolution](https://github.com/dbt-labs/dbt/security/advisories/GHSA-xwgp-43x8-639j) | High | 1.12.6 / 1.11.16 |
| Datasette | [Table permission bypass](https://github.com/simonw/datasette/security/advisories/GHSA-h547-rmjf-5m2m) | High | 0.65.5 / 1.0a40 |
| TwelveMonkeys | [Excessive memory allocation in the PICT image reader](https://github.com/haraldk/TwelveMonkeys/security/advisories/GHSA-859w-fq5p-6c86) | High | 3.15.1 |
| Kaneo | [Outbound destination validation bypass](https://github.com/usekaneo/kaneo/security/advisories/GHSA-w4gj-hv53-f2pj) | High | 2.47.1 |

### Additional selected projects

| Project | Published advisory | Severity | Patched versions |
| --- | --- | --- | --- |
| Milvus | [Cross-database import-job metadata disclosure](https://github.com/milvus-io/milvus/security/advisories/GHSA-6hp9-pxpj-9f64) | Moderate | 3.0.4 |
| GitPython | [Symlink-based path traversal in Submodule.move()](https://github.com/gitpython-developers/GitPython/security/advisories/GHSA-gq48-pqfc-9p58) | Moderate | >= 3.2.0 |
| rclone | [Server-side request forgery in named remote roots](https://github.com/rclone/rclone/security/advisories/GHSA-xqmq-v4wj-rw5m) | Moderate | 1.74.2 |
| AngleSharp | [SVG serialization mutation XSS](https://github.com/AngleSharp/AngleSharp/security/advisories/GHSA-cgp3-27rh-pcp2) | Moderate | >= 1.8.2 |
| Sonos tract (ONNX inference) | [Symlink traversal in ONNX external data loading](https://github.com/sonos/tract/security/advisories/GHSA-7q44-75hx-2x3h) | Moderate | 0.21.19 / 0.22.5 / 0.23.9 |

CVE publication, researcher credit, advisory severity and fixed-version fields verified on **2026-11-11**. The CVE table includes Reporter and Finder credits; Epson records retain their team attribution.

Only publicly disclosed, verifiable work is listed here.
