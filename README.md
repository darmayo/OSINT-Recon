<div align="center">

# 🕵️ OSINT & Recon Toolkit — Complete Edition

**Koleksi tools, workflow, checklist, dan resource untuk OSINT, Attack Surface Recon, Domain/DNS Recon, Subdomain Enumeration, ASN/BGP/IP Intelligence, Internet Exposure Search, GitHub Dorking, Email/Username OSINT, Cloud Exposure, URL Archive Recon, JavaScript Endpoint Discovery, Metadata Analysis, Threat Intelligence, dan Bug Bounty Recon.**

![Focus](https://img.shields.io/badge/focus-OSINT%20%7C%20recon%20%7C%20attack%20surface-7F77DD?style=flat-square)
![Usage](https://img.shields.io/badge/usage-ethical%20only-D85A30?style=flat-square)
![Category](https://img.shields.io/badge/category-osint%20%7C%20reconnaissance%20%7C%20bug%20bounty-1D9E75?style=flat-square)
![Resources](https://img.shields.io/badge/resources-246-58a6ff?style=flat-square)

</div>

---

## 📌 Tentang Repo Ini

Fokusnya adalah pengumpulan informasi legal dan etis dari sumber terbuka untuk bug bounty, asset discovery, attack surface mapping, threat intelligence, SOC enrichment, dan security research.

Resource yang berisiko seperti phishing, doxing, account checking tanpa izin, scraping agresif, dan geolocation abuse dipisahkan ke bagian **Restricted / Ethics / Research Only**.

---

## 📑 Daftar Isi

- [🎯 OSINT Methodology, Frameworks & Learning](#osint-methodology-frameworks--learning)
- [🔍 Search Engines, Dorking & Public Web Discovery](#search-engines-dorking--public-web-discovery)
- [🌐 Domain, DNS, WHOIS & Subdomain Recon](#domain-dns-whois--subdomain-recon)
- [🌍 IP, ASN, BGP & Network Intelligence](#ip-asn-bgp--network-intelligence)
- [🛰️ Internet Exposure, Attack Surface & Device Search Engines](#internet-exposure-attack-surface--device-search-engines)
- [🕰️ URL, Archive, Crawl & Historical Recon](#url-archive-crawl--historical-recon)
- [📜 JavaScript, Endpoint, Secret & Source Map Recon](#javascript-endpoint-secret--source-map-recon)
- [💻 GitHub, Code Search & Secret Exposure Recon](#github-code-search--secret-exposure-recon)
- [📧 Email, Username & People OSINT](#email-username--people-osint)
- [👥 Social Media, Profiles & Platform OSINT](#social-media-profiles--platform-osint)
- [🧪 Breach, Leak & Credential Exposure Intelligence](#breach-leak--credential-exposure-intelligence)
- [☁️ Cloud, Bucket, Firebase & SaaS Exposure Recon](#cloud-bucket-firebase--saas-exposure-recon)
- [📸 Screenshots, Web Fingerprinting & Technology Detection](#screenshots-web-fingerprinting--technology-detection)
- [🖼️ Metadata, Images, Reverse Image & Geolocation OSINT](#metadata-images-reverse-image--geolocation-osint)
- [🏢 Company, Organization & Business OSINT](#company-organization--business-osint)
- [🧿 Threat Intelligence, IOC & Reputation Lookup](#threat-intelligence-ioc--reputation-lookup)
- [🤖 OSINT Automation & Recon Frameworks](#osint-automation--recon-frameworks)
- [📚 Wordlists, Dorks & Recon Dictionaries](#wordlists-dorks--recon-dictionaries)
- [📝 Reporting, Evidence Capture & Case Management](#reporting-evidence-capture--case-management)
- [🤖 AI-Assisted OSINT & Recon Workflow](#ai-assisted-osint--recon-workflow)
- [🚫 Restricted / Ethics / Research Only](#restricted--ethics--research-only)

- [🧭 OSINT & Recon Workflow](#-osint--recon-workflow)
- [✅ OSINT & Recon Checklist](#-osint--recon-checklist)
- [⚖️ Disclaimer](#️-disclaimer)

---

## 🧭 OSINT & Recon Workflow

1. **Scope & Legal Boundary**
   - Tentukan target legal: domain, organization, ASN, brand, IP range, app, product, atau bug bounty scope.

2. **Organization & Domain Mapping**
   - Kumpulkan root domain, subsidiaries, acquisitions, brand names, emails, company records, and public assets.

3. **DNS & Subdomain Recon**
   - Lakukan passive subdomain enum, CT logs, DNS history, permutation, resolution, and live host validation.

4. **IP/ASN/BGP Mapping**
   - Map ASN, netblock, hosting provider, cloud exposure, and internet-facing services.

5. **Internet Exposure Search**
   - Gunakan Shodan, Censys, FOFA, ZoomEye, Netlas, LeakIX, BinaryEdge, dan exposure intelligence.

6. **URL, Archive & JavaScript Recon**
   - Kumpulkan archived URLs, API endpoints, JS files, source maps, secrets, routes, and historical paths.

7. **Code, Secret & Cloud Exposure**
   - Cari leaked keys, exposed repos, public buckets, Firebase exposure, SaaS config, and hardcoded credentials.

8. **People, Email & Username OSINT**
   - Kumpulkan hanya data yang legal dan relevan untuk assessment: contact security, public emails, employee patterns, and org profile.

9. **Threat Intelligence & Reputation**
   - Enrich domain/IP/hash/URL dengan IOC, malware URL, abuse reputation, and threat intel feeds.

10. **Evidence & Reporting**
   - Simpan source URL, timestamp, screenshot, query, finding evidence, impact, and remediation recommendation.

---

## 🎯 OSINT Methodology, Frameworks & Learning

| Resource | Link | Fungsi |
|---|---|---|
| OSINT Framework | https://osintframework.com/ | Framework visual untuk kategori dan sumber OSINT. |
| Awesome OSINT | https://github.com/jivoi/awesome-osint | Awesome list OSINT tools dan resources. |
| Awesome OSINT / ph055a | https://github.com/Ph055a/OSINT_Collection | Koleksi OSINT resources. |
| Bellingcat Online Investigation Toolkit | https://bellingcat.gitbook.io/toolkit | Toolkit investigasi online dan verifikasi sumber terbuka. |
| SANS OSINT Tips | https://www.sans.org/blog/list-of-really-useful-osint-tools/ | Daftar OSINT tools dan referensi investigasi. |
| IntelTechniques Tools | https://inteltechniques.com/tools/ | Koleksi tools OSINT untuk pencarian dan investigasi. |
| OSINT Dojo | https://www.osintdojo.com/resources/ | Resource OSINT learning dan workflow. |
| Nixintel OSINT | https://nixintel.info/ | Artikel dan tutorial OSINT praktis. |
| OSINT Curious | https://osintcurio.us/ | OSINT training, articles, dan methodology. |
| Trace Labs OSINT VM | https://www.tracelabs.org/initiatives/osint-vm | VM/resource untuk OSINT learning dan investigations. |
| SANS SEC487 OSINT Resources | https://www.sans.org/cyber-security-courses/open-source-intelligence-gathering/ | Referensi course OSINT untuk metodologi. |
| OWASP Amass User Guide | https://owasp-amass.github.io/docs/ | Panduan attack surface mapping dan recon. |

---

## 🔍 Search Engines, Dorking & Public Web Discovery

| Resource | Link | Fungsi |
|---|---|---|
| Google Advanced Search | https://www.google.com/advanced_search | Advanced search untuk Google dorking dan public exposure discovery. |
| Google Hacking Database | https://www.exploit-db.com/google-hacking-database | Database Google dorks untuk exposure discovery. |
| Bing Search | https://www.bing.com/ | Search engine alternatif untuk indexing berbeda. |
| Yandex Search | https://yandex.com/ | Search engine alternatif untuk image/search discovery. |
| DuckDuckGo | https://duckduckgo.com/ | Privacy-focused search engine untuk OSINT. |
| Brave Search | https://search.brave.com/ | Search engine alternatif dengan index sendiri. |
| Startpage | https://www.startpage.com/ | Search engine proxy hasil Google dengan privacy focus. |
| SearchCode | https://searchcode.com/ | Search engine source code publik. |
| PublicWWW | https://publicwww.com/ | Search engine untuk HTML/JS/CSS public web content. |
| NerdyData | https://www.nerdydata.com/ | Source code search untuk web technologies dan snippets. |
| SourceGraph | https://sourcegraph.com/search | Code search lintas repository publik. |
| grep.app | https://grep.app/ | Search code across GitHub repositories. |
| Dehashed Search | https://www.dehashed.com/ | Breach/search intelligence platform; gunakan legal dan etis. |
| Hunter.io | https://hunter.io/ | Email/domain discovery untuk organization OSINT. |

---

## 🌐 Domain, DNS, WHOIS & Subdomain Recon

| Resource | Link | Fungsi |
|---|---|---|
| Amass | https://github.com/owasp-amass/amass | Attack surface mapping dan DNS/subdomain enumeration. |
| Subfinder | https://github.com/projectdiscovery/subfinder | Passive subdomain enumeration tool. |
| Assetfinder | https://github.com/tomnomnom/assetfinder | Find related domains/subdomains. |
| Findomain | https://github.com/Findomain/Findomain | Fast subdomain enumeration tool. |
| puredns | https://github.com/d3mondev/puredns | Fast domain resolver dan DNS bruteforcing. |
| dnsx | https://github.com/projectdiscovery/dnsx | Fast DNS toolkit untuk resolution dan filtering. |
| MassDNS | https://github.com/blechschmidt/massdns | High-performance DNS resolver untuk bulk resolution. |
| dnsrecon | https://github.com/darkoperator/dnsrecon | DNS enumeration and zone transfer testing tool. |
| dnsenum | https://github.com/fwaeytens/dnsenum | DNS enumeration script. |
| Fierce | https://github.com/mschwager/fierce | DNS reconnaissance tool. |
| crt.sh | https://crt.sh/ | Certificate Transparency search untuk domain/subdomain discovery. |
| Crtsh CLI | https://github.com/UnaPibaGeek/ctfr | Certificate Transparency subdomain finder. |
| SecurityTrails | https://securitytrails.com/ | DNS, domain, subdomain, dan historical DNS intelligence. |
| DNSDumpster | https://dnsdumpster.com/ | DNS recon dan host discovery. |
| ViewDNS.info | https://viewdns.info/ | Online DNS/IP/domain lookup tools. |
| WhoisXML API | https://www.whoisxmlapi.com/ | WHOIS/DNS/IP intelligence APIs. |

---

## 🌍 IP, ASN, BGP & Network Intelligence

| Resource | Link | Fungsi |
|---|---|---|
| BGP Toolkit | https://bgp.he.net/ | BGP/ASN lookup dan routing intelligence. |
| RIPEstat | https://stat.ripe.net/ | IP/ASN/network intelligence dari RIPE NCC. |
| RADb | https://www.radb.net/query | Routing registry lookup. |
| ARIN Whois | https://search.arin.net/rdap/ | North America IP/ASN RDAP lookup. |
| RIPE Database | https://apps.db.ripe.net/db-web-ui/query | Europe/Middle East/Central Asia IP/ASN DB lookup. |
| APNIC Whois | https://wq.apnic.net/static/search.html | Asia Pacific IP/ASN lookup. |
| LACNIC Whois | https://query.milacnic.lacnic.net/home | Latin America and Caribbean IP/ASN lookup. |
| AFRINIC Whois | https://afrinic.net/whois | Africa IP/ASN lookup. |
| IPinfo | https://ipinfo.io/ | IP geolocation, ASN, company, privacy, dan hosted domain intelligence. |
| ip-api | https://ip-api.com/ | IP geolocation dan ASN lookup. |
| AbuseIPDB | https://www.abuseipdb.com/ | IP abuse reputation database. |
| GreyNoise | https://www.greynoise.io/ | Internet scanning/noise intelligence untuk IP reputation. |
| Spur | https://spur.us/ | IP contextualization, VPN/proxy/residential IP intelligence. |
| PeeringDB | https://www.peeringdb.com/ | Network/ASN/IXP peering intelligence. |
| CIDR Report | https://www.cidr-report.org/ | BGP/CIDR report dan route aggregation info. |

---

## 🛰️ Internet Exposure, Attack Surface & Device Search Engines

| Resource | Link | Fungsi |
|---|---|---|
| Shodan | https://www.shodan.io/ | Search engine untuk internet-connected devices, services, banners, ports, dan exposed assets. |
| Censys | https://search.censys.io/ | Search engine untuk internet hosts, certificates, ports, protocols, dan exposure. |
| FOFA | https://fofa.info/ | Attack surface search engine. |
| ZoomEye | https://www.zoomeye.org/ | Cyberspace search engine untuk exposed assets dan services. |
| Netlas | https://netlas.io/ | Internet asset search engine untuk DNS, IP, certificates, ports, dan web exposure. |
| LeakIX | https://leakix.net/ | Search engine untuk exposed services, leaks, dan misconfigurations. |
| BinaryEdge | https://www.binaryedge.io/ | Internet scanning dan threat intelligence. |
| ONYPHE | https://www.onyphe.io/ | Cyber defense search engine untuk exposed assets dan threat intelligence. |
| Criminal IP | https://www.criminalip.io/ | Attack surface intelligence dan asset risk search. |
| FullHunt | https://fullhunt.io/ | Attack surface management dan exposure intelligence. |
| Hunter How | https://hunter.how/ | Internet asset search engine. |
| Quake 360 | https://quake.360.net/ | Cyberspace search engine dari Qihoo 360. |
| Shadowserver Dashboard | https://dashboard.shadowserver.org/ | Internet exposure dan vulnerability observation dari Shadowserver. |
| GreyNoise Visualizer | https://viz.greynoise.io/ | IP scanning/noise intelligence visualizer. |

---

## 🕰️ URL, Archive, Crawl & Historical Recon

| Resource | Link | Fungsi |
|---|---|---|
| Wayback Machine | https://web.archive.org/ | Archived web pages dan historical URLs. |
| Wayback CDX API | https://github.com/internetarchive/wayback/tree/master/wayback-cdx-server | API untuk query archived URLs dari Internet Archive. |
| gau | https://github.com/lc/gau | Fetch known URLs dari AlienVault, Wayback, Common Crawl, dan URLScan. |
| waybackurls | https://github.com/tomnomnom/waybackurls | Mengambil archived URLs dari Wayback Machine. |
| waymore | https://github.com/xnl-h4ck3r/waymore | URL collection dari Wayback, Common Crawl, URLScan, dan AlienVault. |
| hakrawler | https://github.com/hakluke/hakrawler | Simple crawler untuk endpoint discovery. |
| katana | https://github.com/projectdiscovery/katana | Crawling framework untuk endpoints, routes, forms, dan JS links. |
| urlscan.io | https://urlscan.io/ | URL scan archive, DOM, request, screenshot, dan infrastructure intelligence. |
| Common Crawl Index | https://index.commoncrawl.org/ | Public web crawl index untuk historical URL/content discovery. |
| AlienVault OTX URL | https://otx.alienvault.com/ | Threat intel/URL/domain/IP indicators. |
| URLhaus | https://urlhaus.abuse.ch/ | Malware URL database dari abuse.ch. |
| urlhunter | https://github.com/utkusen/urlhunter | Recon tool untuk URL discovery dari multiple sources. |

---

## 📜 JavaScript, Endpoint, Secret & Source Map Recon

| Resource | Link | Fungsi |
|---|---|---|
| LinkFinder | https://github.com/GerbenJavado/LinkFinder | Menemukan endpoint dari JavaScript. |
| jsluice | https://github.com/BishopFox/jsluice | Ekstraksi URL, endpoint, dan secret dari JS. |
| xnLinkFinder | https://github.com/xnl-h4ck3r/xnLinkFinder | Deep link discovery dari JavaScript dan pages. |
| JSFinder | https://github.com/Threezh1/JSFinder | Mencari URL dan subdomain dari JavaScript. |
| JSRecon-Buddy | https://github.com/TheArqsz/JSRecon-Buddy | Browser extension untuk menemukan endpoint, routes, secrets, dan subdomain dari JavaScript. |
| SecretFinder | https://github.com/m4ll0k/SecretFinder | Discover endpoints dan secrets di JavaScript files. |
| Mantra | https://github.com/brosck/mantra | Mencari API key dan secrets pada halaman web/file JavaScript. |
| JSAnalyzer | https://github.com/jenish-sojitra/JSAnalyzer | Analisis JavaScript untuk endpoint, secret, URL, dan email. |
| JSMap-Inspector | https://github.com/ynsmroztas/JSMap-Inspector | Inspeksi JavaScript Source Map .js.map. |
| MapperPlus | https://github.com/midoxnet/mapperplus | Ekstraksi source dari exposed .js.map. |
| sourcemapper | https://github.com/denandz/sourcemapper | Ekstraksi source asli dari source map. |
| subjs | https://github.com/lc/subjs | Fetch JavaScript file URLs from URL lists. |

---

## 💻 GitHub, Code Search & Secret Exposure Recon

| Resource | Link | Fungsi |
|---|---|---|
| GitHub Search | https://github.com/search | Search public repositories, code, issues, commits, dan users. |
| GitHub Advanced Search | https://github.com/search/advanced | Advanced GitHub search for code/repo/user discovery. |
| GitHub Dorks | https://github.com/techgaun/github-dorks | GitHub dorking resources untuk secrets/exposure discovery. |
| Gitrob | https://github.com/michenriksen/gitrob | Recon tool untuk menemukan sensitive files di GitHub organizations. |
| Gitleaks | https://github.com/gitleaks/gitleaks | Secret scanner untuk Git repos dan filesystem. |
| trufflehog | https://github.com/trufflesecurity/trufflehog | Secret scanning pada Git history dan filesystem. |
| git-secrets | https://github.com/awslabs/git-secrets | Tool untuk mencegah dan mendeteksi secrets di Git. |
| detect-secrets | https://github.com/Yelp/detect-secrets | Secret detection tool dari Yelp. |
| shhgit | https://github.com/eth0izzle/shhgit | Monitor public GitHub events for secrets. |
| GitTools | https://github.com/internetwache/GitTools | Dump dan ekstraksi exposed .git directories. |
| GitHacker | https://github.com/WangYihang/GitHacker | Recover exposed .git directory for authorized testing. |
| git-dumper | https://github.com/arthaud/git-dumper | Dump exposed .git repositories dari web server. |
| Repo-supervisor | https://github.com/auth0/repo-supervisor | Detect secrets and security issues in repositories. |
| Semgrep | https://github.com/semgrep/semgrep | Static analysis untuk source code dan security patterns. |

---

## 📧 Email, Username & People OSINT

| Resource | Link | Fungsi |
|---|---|---|
| theHarvester | https://github.com/laramies/theHarvester | Gather emails, subdomains, hosts, employee names, dan open-source intelligence. |
| EmailRep | https://emailrep.io/ | Email reputation and risk lookup. |
| Have I Been Pwned | https://haveibeenpwned.com/ | Breach exposure lookup untuk email/domain sesuai izin. |
| Holehe | https://github.com/megadose/holehe | Email account existence checker across services; gunakan etis dan sesuai izin. |
| h8mail | https://github.com/khast3x/h8mail | Email breach and OSINT tool; defensive/authorized use. |
| Sherlock | https://github.com/sherlock-project/sherlock | Hunt usernames across social networks. |
| Maigret | https://github.com/soxoj/maigret | Username search across many sites. |
| WhatsMyName | https://github.com/WebBreacher/WhatsMyName | Username enumeration across websites. |
| UserSearch | https://usersearch.org/ | Username/email/phone lookup website. |
| Namechk | https://namechk.com/ | Username/domain availability lookup. |
| WhatsMyName Web | https://whatsmyname.app/ | Web app for username search. |
| Social Analyzer | https://github.com/qeeqbox/social-analyzer | Social media username profiling/recon framework. |
| GHunt | https://github.com/mxrch/GHunt | Google account OSINT tool; use ethically and legally. |

---

## 👥 Social Media, Profiles & Platform OSINT

| Resource | Link | Fungsi |
|---|---|---|
| Social Searcher | https://www.social-searcher.com/ | Social media search engine. |
| Sowdust Search | https://www.sowsearch.info/ | Facebook search helper. |
| IntelX Facebook Tools | https://intelx.io/tools?tab=facebook | Facebook OSINT utilities. |
| TweetDeck / X Pro | https://pro.twitter.com/ | Monitoring/search workflow for X/Twitter. |
| Twint | https://github.com/twintproject/twint | Twitter scraping/OSINT tool; archived, use carefully and respect terms. |
| snscrape | https://github.com/JustAnotherArchivist/snscrape | Social network scraping CLI/library; respect terms and law. |
| instaloader | https://github.com/instaloader/instaloader | Download/inspect Instagram profile data available to authorized/public access. |
| OSINTgram | https://github.com/Datalux/Osintgram | Instagram OSINT tool; use ethically and within terms. |
| TikTokApi | https://github.com/davidteather/TikTok-Api | Unofficial TikTok API for research; respect terms. |
| LinkedIn Search | https://www.linkedin.com/search/results/all/ | Professional profile/company search. |
| Reddit Search | https://www.reddit.com/search/ | Reddit content/user/community search. |
| Pushshift Reddit Search | https://search.pullpush.io/ | Reddit archive search alternative. |

---

## 🧪 Breach, Leak & Credential Exposure Intelligence

| Resource | Link | Fungsi |
|---|---|---|
| Intelligence X | https://intelx.io/ | Search engine untuk leaks, documents, domains, emails, dan OSINT sources. |
| LeakCheck | https://leakcheck.io/ | Breach lookup service; use ethically. |
| BreachDirectory | https://breachdirectory.org/ | Breach lookup service; use ethically. |
| Hudson Rock Cybercrime Intelligence | https://www.hudsonrock.com/threat-intelligence-cybercrime-tools | Infostealer exposure intelligence tools. |
| Firefox Monitor | https://monitor.mozilla.org/ | Breach notification/lookup by Mozilla. |
| HIBP Domain Search | https://haveibeenpwned.com/DomainSearch | Domain-wide breach search untuk domain yang dimiliki/authorized. |
| pwned-passwords | https://haveibeenpwned.com/Passwords | Password exposure check via k-anonymity model. |

---

## ☁️ Cloud, Bucket, Firebase & SaaS Exposure Recon

| Resource | Link | Fungsi |
|---|---|---|
| GrayHatWarfare | https://grayhatwarfare.com/ | Public cloud bucket search engine. |
| s3scanner | https://github.com/sa7mon/s3scanner | Audit bucket S3 terbuka yang ditemukan dari app/config/API. |
| s3tk | https://github.com/KingOfBugbounty/s3tk | Toolkit keamanan Amazon S3. |
| CloudFox | https://github.com/BishopFox/cloudfox | Cloud attack path situational awareness untuk cloud assets yang masuk scope. |
| ScoutSuite | https://github.com/nccgroup/ScoutSuite | Multi-cloud security auditing tool. |
| Prowler | https://github.com/prowler-cloud/prowler | AWS/Azure/GCP/Kubernetes security assessment. |
| CloudSplaining | https://github.com/salesforce/cloudsplaining | AWS IAM security assessment. |
| CloudMapper | https://github.com/duo-labs/cloudmapper | AWS account visualization and assessment. |
| CloudBrute | https://github.com/0xsha/CloudBrute | Cloud asset discovery tool; authorized testing only. |
| GCPBucketBrute | https://github.com/RhinoSecurityLabs/GCPBucketBrute | GCP bucket enumeration/testing for authorized scope. |
| Firebase Scanner | https://github.com/shivsahni/FireBaseScanner | Firebase misconfiguration scanner for authorized testing. |
| Firebase APK Scanner Skill | https://github.com/trailofbits/skills/tree/main/plugins/firebase-apk-scanner | Mendeteksi Firebase exposure dari APK. |

---

## 📸 Screenshots, Web Fingerprinting & Technology Detection

| Resource | Link | Fungsi |
|---|---|---|
| EyeWitness | https://github.com/RedSiege/EyeWitness | Screenshot dan fingerprinting web services. |
| gowitness | https://github.com/sensepost/gowitness | Web screenshot utility untuk reconnaissance. |
| aquatone | https://github.com/michenriksen/aquatone | Visual inspection of websites across large number of hosts. |
| httpx | https://github.com/projectdiscovery/httpx | Fast HTTP probing, title, tech detection, response info, dan screenshot support. |
| WhatWeb | https://github.com/urbanadventurer/WhatWeb | Web technology fingerprinting. |
| Wappalyzer | https://www.wappalyzer.com/ | Technology profiler untuk web services. |
| BuiltWith | https://builtwith.com/ | Technology lookup untuk domains. |
| Netcraft Site Report | https://sitereport.netcraft.com/ | Site report, hosting, tech, dan network information. |
| httprobe | https://github.com/tomnomnom/httprobe | Probe domains/hosts untuk HTTP/HTTPS services. |
| Cloudflare Radar URL Scanner | https://radar.cloudflare.com/scan | URL scanner untuk webpage/infrastructure information. |

---

## 🖼️ Metadata, Images, Reverse Image & Geolocation OSINT

| Resource | Link | Fungsi |
|---|---|---|
| ExifTool | https://github.com/exiftool/exiftool | Read/write metadata pada images, docs, PDFs, dan files. |
| FOCA | https://github.com/ElevenPaths/FOCA | Metadata extraction and document analysis tool. |
| mat2 | https://0xacab.org/jvoisin/mat2 | Metadata anonymization toolkit; useful to understand metadata risks. |
| Jeffrey's Image Metadata Viewer | http://exif.regex.info/exif.cgi | Online image metadata viewer. |
| Google Lens | https://lens.google/ | Image search, visual search, landmark/object identification. |
| Yandex Images | https://yandex.com/images/ | Reverse image search alternative. |
| TinEye | https://tineye.com/ | Reverse image search engine. |
| Bing Visual Search | https://www.bing.com/visualsearch | Reverse image/visual search. |
| GeoGuessr Tips / Geolocation OSINT | https://geohints.com/ | Geolocation hints for visual OSINT. |
| Overpass Turbo | https://overpass-turbo.eu/ | OpenStreetMap query tool for geolocation research. |
| OpenStreetMap | https://www.openstreetmap.org/ | Open map data for location verification. |
| SunCalc | https://www.suncalc.org/ | Sun position calculator for image/video geolocation. |

---

## 🏢 Company, Organization & Business OSINT

| Resource | Link | Fungsi |
|---|---|---|
| Crunchbase | https://www.crunchbase.com/ | Company, funding, acquisition, and organization intelligence. |
| OpenCorporates | https://opencorporates.com/ | Global company registry search. |
| SEC EDGAR | https://www.sec.gov/edgar/search/ | US public company filings. |
| Companies House | https://find-and-update.company-information.service.gov.uk/ | UK company registry. |
| GLEIF LEI Search | https://search.gleif.org/ | Legal Entity Identifier lookup. |
| Wappalyzer Lookup | https://www.wappalyzer.com/lookup/ | Technology lookup for organizations. |
| Apollo | https://www.apollo.io/ | B2B/company/person search; use ethically. |
| ZoomInfo | https://www.zoominfo.com/ | Business/company/person data platform; use ethically. |
| LinkedIn Company Search | https://www.linkedin.com/search/results/companies/ | Company page and employee discovery. |
| Google Maps | https://maps.google.com/ | Company location, branch, and review information. |

---

## 🧿 Threat Intelligence, IOC & Reputation Lookup

| Resource | Link | Fungsi |
|---|---|---|
| VirusTotal | https://www.virustotal.com/ | File, URL, domain, IP, and hash reputation/intelligence. |
| Pulsedive | https://pulsedive.com/ | Threat intelligence search untuk domain, IP, URL, dan IOC. |
| ThreatFox | https://threatfox.abuse.ch/ | IOC database untuk malware indicators. |
| MalwareBazaar | https://bazaar.abuse.ch/ | Malware sample repository/hash lookup. |
| YARAify | https://yaraify.abuse.ch/ | YARA-based malware intelligence lookup. |
| Abuse.ch Feeds | https://abuse.ch/ | Threat intelligence feeds by abuse.ch. |
| MISP Project | https://www.misp-project.org/ | Threat intelligence sharing platform. |
| OpenCTI | https://github.com/OpenCTI-Platform/opencti | Open-source cyber threat intelligence platform. |
| CIRCL Passive DNS | https://www.circl.lu/services/passive-dns/ | Passive DNS service by CIRCL. |
| Spamhaus | https://www.spamhaus.org/ | IP/domain/email abuse and blocklist intelligence. |

---

## 🤖 OSINT Automation & Recon Frameworks

| Resource | Link | Fungsi |
|---|---|---|
| SpiderFoot | https://github.com/smicallef/spiderfoot | OSINT automation framework for domains, IPs, emails, usernames, and more. |
| Recon-ng | https://github.com/lanmaster53/recon-ng | Web reconnaissance framework with modules. |
| Maltego | https://www.maltego.com/ | Link analysis and OSINT graphing platform. |
| reconftw | https://github.com/six2dez/reconftw | Automated recon workflow for bug bounty and attack surface mapping. |
| Sn1per | https://github.com/1N3/Sn1per | Automated recon and vulnerability assessment framework; authorized scope only. |
| Raccoon | https://github.com/evyatarmeged/Raccoon | Reconnaissance and vulnerability scanning tool. |
| Osmedeus | https://github.com/j3ssie/Osmedeus | Workflow engine for offensive security/recon automation. |
| FinalRecon | https://github.com/thewhiteh4t/FinalRecon | Web reconnaissance tool. |
| Photon | https://github.com/s0md3v/Photon | Crawler for OSINT and web recon. |
| ReconDog | https://github.com/s0md3v/ReconDog | Reconnaissance toolkit. |
| BBOT | https://github.com/blacklanternsecurity/bbot | Recursive internet scanner and OSINT automation framework. |

---

## 📚 Wordlists, Dorks & Recon Dictionaries

| Resource | Link | Fungsi |
|---|---|---|
| SecLists | https://github.com/danielmiessler/SecLists | Wordlists untuk DNS, directories, usernames, passwords, fuzzing, dan discovery. |
| Commonspeak2 Wordlists | https://github.com/assetnote/commonspeak2-wordlists | Wordlists for domains, subdomains, and paths. |
| OneListForAll | https://github.com/six2dez/OneListForAll | Large content discovery wordlist. |
| wordlists | https://github.com/kkrypt0nn/wordlists | Wordlists collection for security testing. |
| Statistically-Likely-Usernames | https://github.com/insidetrust/statistically-likely-usernames | Username wordlists for authorized testing. |
| FuzzDB | https://github.com/fuzzdb-project/fuzzdb | Attack and discovery patterns for application fuzzing. |
| Bo0oM Fuzz.txt | https://github.com/Bo0oM/fuzz.txt | Fuzzing wordlists for web/API discovery. |
| Assetnote Wordlists | https://wordlists.assetnote.io/ | Generated wordlists for content discovery. |
| Probable Wordlists | https://github.com/berzerk0/Probable-Wordlists | Password/username wordlists collection. |

---

## 📝 Reporting, Evidence Capture & Case Management

| Resource | Link | Fungsi |
|---|---|---|
| Hunchly | https://www.hunch.ly/ | Web capture and evidence management for OSINT investigations. |
| Obsidian | https://obsidian.md/ | Markdown knowledge base/note-taking for OSINT cases. |
| CherryTree | https://github.com/giuspen/cherrytree | Hierarchical note-taking app for investigation notes. |
| Gephi | https://gephi.org/ | Open graph visualization platform. |
| draw.io | https://www.drawio.com/ | Diagramming for recon maps and relationship graphs. |
| Flameshot | https://github.com/flameshot-org/flameshot | Screenshot tool for evidence capture. |
| ShareX | https://github.com/ShareX/ShareX | Screenshot and screen capture tool. |
| Archive.today | https://archive.ph/ | Webpage archiving for evidence preservation. |
| Wayback Save Page Now | https://web.archive.org/save | Archive web pages to Wayback Machine. |
| Dradis CE | https://github.com/dradis/dradis-ce | Collaboration and reporting framework for assessments. |
| DefectDojo | https://github.com/DefectDojo/django-DefectDojo | Vulnerability management and reporting platform. |

---

## 🤖 AI-Assisted OSINT & Recon Workflow

| Resource | Link | Fungsi |
|---|---|---|
| BugTrace-AI | https://github.com/yz9yt/BugTrace-AI | AI-assisted bug bounty/recon workflow tool. |
| AIRecon | https://github.com/pikpikcu/airecon | Autonomous security agent berbasis Ollama/Kali Docker. |
| pentest-ai-agents | https://github.com/0xSteph/pentest-ai-agents | AI subagents untuk offensive security workflow. |
| Bug-Bounty-Agents | https://github.com/matty69v/Bug-Bounty-Agents | Agent AI untuk bug bounty workflow. |
| claude-bug-bounty | https://github.com/shuvonsec/claude-bug-bounty | Claude Code workflow untuk bug bounty. |
| claude-code-owasp | https://github.com/agamm/claude-code-owasp | Claude Code workflow berbasis OWASP untuk review security. |
| Trail of Bits Skills | https://github.com/trailofbits/skills | Plugin/skills collection untuk security automation. |
| secskills | https://github.com/trilwu/secskills | Security skills/workflows untuk AI-assisted security work. |
| Guardian CLI | https://github.com/zakirkun/guardian-cli | AI-powered pentest automation CLI. |
| RAI | https://github.com/RevoltSecurities/RAI | CLI framework untuk LLM agent/team workflow. |
| CAI | https://github.com/aliasrobotics/cai | Cybersecurity AI framework untuk agent security testing. |
| burp-mcp-agents | https://github.com/aress31/burp-mcp-agents | MCP agents untuk Burp Suite workflow. |

---

## 🚫 Restricted / Ethics / Research Only

> Resource di bagian ini rawan disalahgunakan untuk phishing, stalking, doxing, harassment, scraping agresif, atau pelanggaran privasi. Gunakan hanya untuk awareness, defensive research, training legal, consent-based investigation, atau scope yang jelas.

| Resource | Link | Catatan |
|---|---|---|
| Seeker | https://github.com/thewhiteh4t/seeker | Geolocation/phishing-style OSINT; tidak cocok untuk operasional publik tanpa scope/legal basis. |
| Evilginx2 | https://github.com/kgretzky/evilginx2 | Phishing/MFA attack framework; awareness/defense training only. |
| SocialFish | https://github.com/UndeadSec/SocialFish | Phishing framework; not recommended for OSINT repo workflow. |
| BlackEye | https://github.com/An0nUD4Y/blackeye | Phishing-style toolkit; not recommended. |
| CamPhish | https://github.com/techchipnet/CamPhish | Camera phishing tool; not allowed for ethical OSINT workflow. |
| PhoneInfoga | https://github.com/sundowndev/phoneinfoga | Phone number OSINT; use only with consent/legal basis. |
| Ignorant | https://github.com/megadose/ignorant | Phone number account checker; consent/legal basis only. |
| Doxing-related tools | https://github.com/topics/doxing | Doxing/stalking resources are not appropriate for ethical OSINT repos. |

---

## ✅ OSINT & Recon Checklist

### Scope & Preparation

```text
[ ] Tentukan target legal/scope
[ ] Catat domain utama
[ ] Catat company/brand/subsidiary
[ ] Catat ASN/IP range jika ada
[ ] Catat batasan bug bounty / rules of engagement
[ ] Siapkan folder evidence
[ ] Simpan tanggal, query, dan sumber data
```

### Domain, DNS & Subdomain

```text
[ ] WHOIS/RDAP lookup
[ ] Certificate Transparency search
[ ] Passive subdomain enumeration
[ ] DNS history review
[ ] DNS record review: A, AAAA, MX, TXT, NS, SOA
[ ] Subdomain permutation jika scope mengizinkan
[ ] Resolve subdomain aktif
[ ] Validasi live HTTP/HTTPS
[ ] Screenshot web assets
```

### IP, ASN & Exposure

```text
[ ] ASN/BGP lookup
[ ] Netblock mapping
[ ] Reverse DNS lookup
[ ] Shodan/Censys/FOFA/ZoomEye/Netlas search
[ ] Exposed service review
[ ] Cloud bucket/Firebase exposure check
[ ] TLS/certificate relationship mapping
[ ] Abuse/reputation lookup
```

### URL, Archive & JavaScript

```text
[ ] Wayback URL collection
[ ] Common Crawl/urlscan collection
[ ] Crawl live site
[ ] Extract JavaScript files
[ ] Extract endpoints/routes
[ ] Check source maps
[ ] Search secrets/API keys
[ ] Map API base URLs
[ ] Identify staging/dev/debug paths
```

### Code, Secret & Cloud

```text
[ ] GitHub organization/repo search
[ ] GitHub dorking
[ ] Secret scanning public repos
[ ] Exposed .git check
[ ] Public bucket search
[ ] Firebase exposure check
[ ] SaaS config exposure check
[ ] Leaked token validation only if legal/safe
```

### People / Email / Username

```text
[ ] Identify security contact
[ ] Identify public email pattern
[ ] Check public employee pages only if relevant
[ ] Avoid stalking/doxing
[ ] Avoid private account probing
[ ] Use breach lookup only with authorization/consent
```

### Reporting

```text
[ ] Sertakan source URL
[ ] Sertakan timestamp
[ ] Sertakan query yang digunakan
[ ] Sertakan screenshot/evidence
[ ] Jelaskan impact
[ ] Jelaskan confidence level
[ ] Jelaskan remediation
[ ] Jelaskan batasan dan asumsi
```

---

## ⚖️ Disclaimer

Gunakan tools dan resource ini hanya untuk OSINT legal, bug bounty sesuai scope, defensive security, asset discovery, SOC enrichment, threat intelligence, lab pribadi, dan security research yang etis.

Jangan menggunakan resource ini untuk doxing, stalking, harassment, phishing, credential theft, account takeover, scraping ilegal, bypass privasi, pengumpulan data personal tanpa dasar hukum/izin, atau aktivitas yang melanggar hukum.

Selalu hormati privasi, terms of service, robots.txt bila relevan, rate limit, dan batasan program bug bounty atau assessment.
