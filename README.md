# Awesome Security [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of awesome open-source security standards, frameworks, tools, scanners, and autonomous agents maintained by the [`SecurityStandards`](https://github.com/SecurityStandards) organization.

---

## 📑 Contents

- [🏛️ Security Standards & Frameworks](#️-security-standards--frameworks)
- [🔍 OSINT (Open Source Intelligence) & Recon](#-osint-open-source-intelligence--recon)
- [🛡️ SAST (Static Application Security Testing)](#️-sast-static-application-security-testing)
- [⚡ DAST (Dynamic Application Security Testing)](#-dast-dynamic-application-security-testing)
- [📦 SCA (Software Composition Analysis) & SBOM](#-sca-software-composition-analysis--sbom)
- [🔑 Secret Scanning & Leak Detection](#-secret-scanning--leak-detection)
- [☁️ Cloud Security (CSPM, CIEM) & IaC](#️-cloud-security-cspm-ciem--iac)
- [🐳 Container & Kubernetes Security](#-container--kubernetes-security)
- [🤖 Autonomous Security Agents & AI](#-autonomous-security-agents--ai)
- [🌐 Network Security & Port Scanning](#-network-security--port-scanning)
- [🚨 SIEM, Threat Detection & Incident Response](#-siem-threat-detection--incident-response)
- [🤝 Contributing](#-contributing)

---

## 🏛️ Security Standards & Frameworks

* [SecurityStandards / security-standards](https://github.com/SecurityStandards/security-standards) [![Stars](https://img.shields.io/github/stars/SecurityStandards/security-standards?style=social)](https://github.com/SecurityStandards/security-standards) - Unified open-source repository of security policies, control procedures, regulatory mappings, checklists, and vendor questionnaires.
* [NIST Cybersecurity Framework (CSF) 2.0](https://www.nist.gov/cyberframework) - Landmark guidance from the US NIST for understanding, managing, and reducing cybersecurity risks.
* [CIS Critical Security Controls](https://www.cisecurity.org/controls) - Prioritized set of 18 essential cyber defense safeguards against prevalent attack vectors.
* [OWASP Top 10](https://owasp.org/www-project-top-10/) - The globally recognized awareness document for web application security vulnerabilities.
* [OWASP API Security Top 10](https://owasp.org/www-project-api-security/) - Periodic ranking of the most critical vulnerabilities affecting web APIs.
* [OWASP Top 10 for LLM Applications](https://owasp.org/www-project-top-10-for-large-language-model-applications/) - Standardized taxonomy of security risks for generative AI and Large Language Model applications.
* [MITRE ATT&CK](https://attack.mitre.org/) - Globally-accessible knowledge base of adversary tactics, techniques, and procedures based on real-world observations.

---

## 🔍 OSINT (Open Source Intelligence) & Recon

* [Sherlock](https://github.com/sherlock-project/sherlock) [![Stars](https://img.shields.io/github/stars/sherlock-project/sherlock?style=social)](https://github.com/sherlock-project/sherlock) - Hunt down social media accounts by username across 400+ social networks.
* [theHarvester](https://github.com/laramies/theHarvester) [![Stars](https://img.shields.io/github/stars/laramies/theHarvester?style=social)](https://github.com/laramies/theHarvester) - E-mails, subdomains, IPs, and employee name harvesting tool using search engines and public databases.
* [OWASP Amass](https://github.com/owasp-amass/amass) [![Stars](https://img.shields.io/github/stars/owasp-amass/amass?style=social)](https://github.com/owasp-amass/amass) - In-depth attack surface mapping and external asset discovery using active/passive techniques.
* [Subfinder](https://github.com/projectdiscovery/subfinder) [![Stars](https://img.shields.io/github/stars/projectdiscovery/subfinder?style=social)](https://github.com/projectdiscovery/subfinder) - Fast passive subdomain enumeration tool that discovers valid subdomains using passive online sources.
* [SpiderFoot](https://github.com/smicallef/spiderfoot) [![Stars](https://img.shields.io/github/stars/smicallef/spiderfoot?style=social)](https://github.com/smicallef/spiderfoot) - Open source intelligence (OSINT) automation platform scanning over 100 public data sources.
* [Recon-ng](https://github.com/lanmaster53/recon-ng) [![Stars](https://img.shields.io/github/stars/lanmaster53/recon-ng?style=social)](https://github.com/lanmaster53/recon-ng) - Full-featured web reconnaissance framework with independent modules, database interaction, and reporting.
* [Photon](https://github.com/s0md3v/Photon) [![Stars](https://img.shields.io/github/stars/s0md3v/Photon?style=social)](https://github.com/s0md3v/Photon) - Incredibly fast web crawler designed for extracting URLs, emails, files, and secret keys during OSINT.
* [Social-Analyzer](https://github.com/qeeqbox/social-analyzer) [![Stars](https://img.shields.io/github/stars/qeeqbox/social-analyzer?style=social)](https://github.com/qeeqbox/social-analyzer) - API, CLI, and web app for analyzing and finding a person's profile across 1000+ social platforms.

---

## 🛡️ SAST (Static Application Security Testing)

* [Semgrep](https://github.com/semgrep/semgrep) [![Stars](https://img.shields.io/github/stars/semgrep/semgrep?style=social)](https://github.com/semgrep/semgrep) - Fast, lightweight, open-source static analysis engine for finding bugs, CVEs, and enforcing code standards.
* [Bandit](https://github.com/PyCQA/bandit) [![Stars](https://img.shields.io/github/stars/PyCQA/bandit?style=social)](https://github.com/PyCQA/bandit) - Security linter and AST-based vulnerability finder for Python code.
* [GoSec](https://github.com/securego/gosec) [![Stars](https://img.shields.io/github/stars/securego/gosec?style=social)](https://github.com/securego/gosec) - Go AST-based security scanner inspecting Go source code for security flaws.
* [Brakeman](https://github.com/presidentbeef/brakeman) [![Stars](https://img.shields.io/github/stars/presidentbeef/brakeman?style=social)](https://github.com/presidentbeef/brakeman) - Static analysis security vulnerability scanner designed specifically for Ruby on Rails applications.
* [Checkstyle](https://github.com/checkstyle/checkstyle) [![Stars](https://img.shields.io/github/stars/checkstyle/checkstyle?style=social)](https://github.com/checkstyle/checkstyle) - Development tool to help programmers write Java code that adheres to standard security and style coding rules.
* [Flawfinder](https://github.com/david-a-wheeler/flawfinder) [![Stars](https://img.shields.io/github/stars/david-a-wheeler/flawfinder?style=social)](https://github.com/david-a-wheeler/flawfinder) - Lexical analyzer scanning C/C++ source code for security vulnerabilities.
* [NodeJsScan](https://github.com/ajinabraham/NodeJsScan) [![Stars](https://img.shields.io/github/stars/ajinabraham/NodeJsScan?style=social)](https://github.com/ajinabraham/NodeJsScan) - Static code scanner for Node.js applications powered by Opengrep/Semgrep.

---

## ⚡ DAST (Dynamic Application Security Testing)

* [OWASP ZAP (Zed Attack Proxy)](https://github.com/zaproxy/zaproxy) [![Stars](https://img.shields.io/github/stars/zaproxy/zaproxy?style=social)](https://github.com/zaproxy/zaproxy) - The world's most widely used open-source web application security scanner and interactive proxy.
* [Nuclei](https://github.com/projectdiscovery/nuclei) [![Stars](https://img.shields.io/github/stars/projectdiscovery/nuclei?style=social)](https://github.com/projectdiscovery/nuclei) - Fast, customizable vulnerability scanner based on simple YAML DSL templates.
* [Caido](https://github.com/caido/caido) [![Stars](https://img.shields.io/github/stars/caido/caido?style=social)](https://github.com/caido/caido) - Modern, lightweight web security auditing toolkit written in Rust, designed as a fast alternative to Burp Suite.
* [Nikto](https://github.com/sullo/nikto) [![Stars](https://img.shields.io/github/stars/sullo/nikto?style=social)](https://github.com/sullo/nikto) - Classic web server scanner testing for dangerous files, outdated server software, and configuration problems.
* [Wapiti](https://github.com/wapiti-scanner/wapiti) [![Stars](https://img.shields.io/github/stars/wapiti-scanner/wapiti?style=social)](https://github.com/wapiti-scanner/wapiti) - Web application security auditor performing black-box audits by injecting payloads and crawling pages.
* [Katana](https://github.com/projectdiscovery/katana) [![Stars](https://img.shields.io/github/stars/projectdiscovery/katana?style=social)](https://github.com/projectdiscovery/katana) - Next-generation crawling and spidering framework built in Go for web discovery.
* [Sqlmap](https://github.com/sqlmapproject/sqlmap) [![Stars](https://img.shields.io/github/stars/sqlmapproject/sqlmap?style=social)](https://github.com/sqlmapproject/sqlmap) - Automatic SQL injection and database takeover tool.
* [Commix](https://github.com/commixproject/commix) [![Stars](https://img.shields.io/github/stars/commixproject/commix?style=social)](https://github.com/commixproject/commix) - Automated all-in-one OS command injection and exploitation tool.

---

## 📦 SCA (Software Composition Analysis) & SBOM

* [Trivy](https://github.com/aquasecurity/trivy) [![Stars](https://img.shields.io/github/stars/aquasecurity/trivy?style=social)](https://github.com/aquasecurity/trivy) - Comprehensive scanner for vulnerabilities in open-source dependencies, container images, VM images, and git repositories.
* [OSV-Scanner](https://github.com/google/osv-scanner) [![Stars](https://img.shields.io/github/stars/google/osv-scanner?style=social)](https://github.com/google/osv-scanner) - Official vulnerability scanner for Google's Open Source Vulnerabilities (OSV) database.
* [Syft](https://github.com/anchore/syft) [![Stars](https://img.shields.io/github/stars/anchore/syft?style=social)](https://github.com/anchore/syft) - CLI tool and library for generating Software Bill of Materials (SBOM) from container images and filesystems.
* [Grype](https://github.com/anchore/grype) [![Stars](https://img.shields.io/github/stars/anchore/grype?style=social)](https://github.com/anchore/grype) - Vulnerability scanner for container images and filesystems paired with Syft SBOMs.
* [OWASP Dependency-Check](https://github.com/jeremylong/DependencyCheck) [![Stars](https://img.shields.io/github/stars/jeremylong/DependencyCheck?style=social)](https://github.com/jeremylong/DependencyCheck) - Software Composition Analysis (SCA) tool identifying project dependencies against the National Vulnerability Database (NVD).
* [Retire.js](https://github.com/RetireJS/retire.js) [![Stars](https://img.shields.io/github/stars/RetireJS/retire.js?style=social)](https://github.com/RetireJS/retire.js) - Scanner detecting the use of vulnerable JavaScript libraries in web applications and Node.js.

---

## 🔑 Secret Scanning & Leak Detection

* [TruffleHog](https://github.com/trufflesecurity/trufflehog) [![Stars](https://img.shields.io/github/stars/trufflesecurity/trufflehog?style=social)](https://github.com/trufflesecurity/trufflehog) - High-speed secrets scanner capable of verifying secrets against live APIs across git repos, S3, filesystems, and Slack.
* [Gitleaks](https://github.com/gitleaks/gitleaks) [![Stars](https://img.shields.io/github/stars/gitleaks/gitleaks?style=social)](https://github.com/gitleaks/gitleaks) - Fast, lightweight tool for detecting hardcoded secrets like passwords, API keys, and tokens in git commits.
* [detect-secrets](https://github.com/Yelp/detect-secrets) [![Stars](https://img.shields.io/github/stars/Yelp/detect-secrets?style=social)](https://github.com/Yelp/detect-secrets) - Enterprise-friendly secrets detection tool developed by Yelp utilizing heuristics and regular expressions.
* [Whispers](https://github.com/Skyscanner/whispers) [![Stars](https://img.shields.io/github/stars/Skyscanner/whispers?style=social)](https://github.com/Skyscanner/whispers) - Advanced static code analysis tool designed by Skyscanner to parse various formats and find secrets.

---

## ☁️ Cloud Security (CSPM, CIEM) & IaC

* [Prowler](https://github.com/prowler-cloud/prowler) [![Stars](https://img.shields.io/github/stars/prowler-cloud/prowler?style=social)](https://github.com/prowler-cloud/prowler) - Open-source security tool to perform AWS, Azure, GCP, and Kubernetes security assessments and audits aligned with CIS Benchmarks.
* [Checkov](https://github.com/bridgecrewio/checkov) [![Stars](https://img.shields.io/github/stars/bridgecrewio/checkov?style=social)](https://github.com/bridgecrewio/checkov) - Static code analysis tool for Infrastructure as Code (Terraform, CloudFormation, Kubernetes, ARM, Bicep, Helm).
* [ScoutSuite](https://github.com/nccgroup/ScoutSuite) [![Stars](https://img.shields.io/github/stars/nccgroup/ScoutSuite?style=social)](https://github.com/nccgroup/ScoutSuite) - Open-source multi-cloud security-auditing tool querying cloud APIs for risk evaluation.
* [KICS (Keeping Infrastructure as Code Secure)](https://github.com/Checkmarx/kics) [![Stars](https://img.shields.io/github/stars/Checkmarx/kics?style=social)](https://github.com/Checkmarx/kics) - Find security vulnerabilities, compliance issues, and misconfigurations in IaC solutions.
* [CloudFox](https://github.com/BishopFox/cloudfox) [![Stars](https://img.shields.io/github/stars/BishopFox/cloudfox?style=social)](https://github.com/BishopFox/cloudfox) - Situational awareness and penetration testing tool for AWS and Azure cloud environments.
* [Terrascan](https://github.com/tenable/terrascan) [![Stars](https://img.shields.io/github/stars/tenable/terrascan?style=social)](https://github.com/tenable/terrascan) - Detect compliance and security violations across Infrastructure as Code to mitigate risks before provisioning.

---

## 🐳 Container & Kubernetes Security

* [Falco](https://github.com/falcosecurity/falco) [![Stars](https://img.shields.io/github/stars/falcosecurity/falco?style=social)](https://github.com/falcosecurity/falco) - Cloud-native runtime security tool and de facto Kubernetes threat detection engine based on eBPF.
* [kube-bench](https://github.com/aquasecurity/kube-bench) [![Stars](https://img.shields.io/github/stars/aquasecurity/kube-bench?style=social)](https://github.com/aquasecurity/kube-bench) - Checks whether Kubernetes is deployed securely by running checks documented in the CIS Kubernetes Benchmark.
* [kube-hunter](https://github.com/aquasecurity/kube-hunter) [![Stars](https://img.shields.io/github/stars/aquasecurity/kube-hunter?style=social)](https://github.com/aquasecurity/kube-hunter) - Hunts for security weaknesses and vulnerabilities in Kubernetes clusters.
* [Cosign (Sigstore)](https://github.com/sigstore/cosign) [![Stars](https://img.shields.io/github/stars/sigstore/cosign?style=social)](https://github.com/sigstore/cosign) - Container Signing, verification, and storage in OCI registries.
* [Hadolint](https://github.com/hadolint/hadolint) [![Stars](https://img.shields.io/github/stars/hadolint/hadolint?style=social)](https://github.com/hadolint/hadolint) - Smarter Dockerfile linter that helps build best practice Docker images.
* [Dockle](https://github.com/goodwithtech/dockle) [![Stars](https://img.shields.io/github/stars/goodwithtech/dockle?style=social)](https://github.com/goodwithtech/dockle) - Container image linter for security and CIS benchmark compliance.

---

## 🤖 Autonomous Security Agents & AI

* [Shannon (agent-pentester)](https://github.com/SecurityStandards/agent-pentester) [![Stars](https://img.shields.io/github/stars/SecurityStandards/agent-pentester?style=social)](https://github.com/SecurityStandards/agent-pentester) - Autonomous AI pentester for web applications and APIs that analyzes source code, plans attack vectors, and executes real exploits.
* [REA (agent-reverse-engineer)](https://github.com/SecurityStandards/agent-reverse-engineer) [![Stars](https://img.shields.io/github/stars/SecurityStandards/agent-reverse-engineer?style=social)](https://github.com/SecurityStandards/agent-reverse-engineer) - Reverse engineer anything with AI agents, from dynamic app behavior down to native binaries.
* [Cloudflare Security Audit Skill](https://github.com/SecurityStandards/skill-security-audit) [![Stars](https://img.shields.io/github/stars/SecurityStandards/skill-security-audit?style=social)](https://github.com/SecurityStandards/skill-security-audit) - Coding-agent skill for multi-phase security audits with independently verified, machine-readable findings.
* [Garak](https://github.com/leondz/garak) [![Stars](https://img.shields.io/github/stars/leondz/garak?style=social)](https://github.com/leondz/garak) - LLM vulnerability scanner checking for hallucinations, data leaks, prompt injection, and toxic outputs.
* [Promptfoo](https://github.com/promptfoo/promptfoo) [![Stars](https://img.shields.io/github/stars/promptfoo/promptfoo?style=social)](https://github.com/promptfoo/promptfoo) - Test-driven security and quality evaluation framework for LLMs and prompt security.

---

## 🌐 Network Security & Port Scanning

* [Nmap](https://github.com/nmap/nmap) [![Stars](https://img.shields.io/github/stars/nmap/nmap?style=social)](https://github.com/nmap/nmap) - The legendary network mapper, port scanner, and security scanner.
* [Masscan](https://github.com/robertdavidgraham/masscan) [![Stars](https://img.shields.io/github/stars/robertdavidgraham/masscan?style=social)](https://github.com/robertdavidgraham/masscan) - The fastest internet-scale port scanner, capable of scanning the entire Internet in under 5 minutes.
* [RustScan](https://github.com/RustScan/RustScan) [![Stars](https://img.shields.io/github/stars/RustScan/RustScan?style=social)](https://github.com/RustScan/RustScan) - Modern port scanner built in Rust that finds open ports in seconds and pipes results straight into Nmap.
* [Naabu](https://github.com/projectdiscovery/naabu) [![Stars](https://img.shields.io/github/stars/projectdiscovery/naabu?style=social)](https://github.com/projectdiscovery/naabu) - Fast port scanner written in Go focused on reliability and simplicity for security researchers.
* [Httpx](https://github.com/projectdiscovery/httpx) [![Stars](https://img.shields.io/github/stars/projectdiscovery/httpx?style=social)](https://github.com/projectdiscovery/httpx) - Fast and multi-purpose HTTP toolkit allowing running multiple probes using retryablehttp library.
* [Bettercap](https://github.com/bettercap/bettercap) [![Stars](https://img.shields.io/github/stars/bettercap/bettercap?style=social)](https://github.com/bettercap/bettercap) - The Swiss army knife for WiFi, Bluetooth Low Energy, wireless, and Ethernet network reconnaissance.

---

## 🚨 SIEM, Threat Detection & Incident Response

* [Wazuh](https://github.com/wazuh/wazuh) [![Stars](https://img.shields.io/github/stars/wazuh/wazuh?style=social)](https://github.com/wazuh/wazuh) - Free and open-source platform for threat prevention, detection, and response across endpoints and cloud workloads.
* [Suricata](https://github.com/OISF/suricata) [![Stars](https://img.shields.io/github/stars/OISF/suricata?style=social)](https://github.com/OISF/suricata) - High-performance Network IDS, IPS, and Network Security Monitoring engine.
* [Zeek](https://github.com/zeek/zeek) [![Stars](https://img.shields.io/github/stars/zeek/zeek?style=social)](https://github.com/zeek/zeek) - Powerful network analysis framework and network security monitor.
* [Velociraptor](https://github.com/Velocidex/velociraptor) [![Stars](https://img.shields.io/github/stars/Velocidex/velociraptor?style=social)](https://github.com/Velocidex/velociraptor) - Advanced digital forensic and endpoint visibility tool using VQL (Velociraptor Query Language).
* [TheHive](https://github.com/TheHive-Project/TheHive) [![Stars](https://img.shields.io/github/stars/TheHive-Project/TheHive?style=social)](https://github.com/TheHive-Project/TheHive) - Scalable open-source Security Incident Response Platform designed for SOCs and CERTs.
* [MISP](https://github.com/MISP/MISP) [![Stars](https://img.shields.io/github/stars/MISP/MISP?style=social)](https://github.com/MISP/MISP) - Open Source Threat Intelligence and Sharing Platform for sharing indicators of compromise (IoCs).

---

## 🤝 Contributing

Contributions are very welcome!
1. Read our guidelines in [AGENTS.md](AGENTS.md).
2. Ensure the tool you are proposing is **actively maintained** and **open source**.
3. Include the standard Shields.io star badge: `[![Stars](https://img.shields.io/github/stars/<owner>/<repo>?style=social)](https://github.com/owner/repo)`.
4. Submit a GPG-signed Pull Request!
