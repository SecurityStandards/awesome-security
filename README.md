# Awesome Security [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> The exhaustive, multilingual (🇺🇸 English · 🇧🇷 Português · 🇪🇸 Español) curated index of open-source security standards, frameworks, scanners, autonomous AI agents, offensive tooling, defensive platforms, essential books, and foundational academic papers.
>
> O catálogo exaustivo e multilíngue de padrões de segurança, frameworks de conformidade, scanners open source, agentes autônomos de IA, ferramentas ofensivas e defensivas, livros essenciais e artigos acadêmicos canônicos.
>
> El catálogo exhaustivo y multilingüe de estándares de seguridad, marcos de cumplimiento, escáneres de código abierto, agentes autónomos de IA, herramientas ofensivas y defensivas, libros esenciales y artículos académicos canónicos.

---

## 🧭 Master Category Index / Índice de Categorias / Índice de Categorías

Explore as 20 categorias especializadas, organizadas em arquivos dedicados com ferramentas open source, links diretos, contagem de estrelas do GitHub em tempo real e anotações trilíngues:

| # | Category / Categoria | Key Focus / Foco Principal | File Link |
| :-: | :--- | :--- | :--- |
| **01** | **🏛️ Standards & Frameworks** | NIST CSF, ISO 27001, CIS Controls, PCI DSS, OWASP Top 10, MITRE ATT&CK | [`01-standards-and-frameworks.md`](categories/01-standards-and-frameworks.md) |
| **02** | **🛡️ SAST (Static Analysis)** | Semgrep, Bandit, GoSec, Brakeman, Flawfinder, NodeJsScan, Opengrep | [`02-sast.md`](categories/02-sast.md) |
| **03** | **⚡ DAST (Dynamic Analysis)** | OWASP ZAP, Nuclei, Caido, Nikto, Sqlmap, Commix, Katana, Wapiti | [`03-dast.md`](categories/03-dast.md) |
| **04** | **📦 SCA & SBOM** | Trivy, Google OSV-Scanner, Syft, Grype, OWASP Dependency-Check | [`04-sca-and-sbom.md`](categories/04-sca-and-sbom.md) |
| **05** | **🔍 OSINT & Reconnaissance** | Sherlock, theHarvester, OWASP Amass, Subfinder, SpiderFoot, Recon-ng | [`05-osint-and-reconnaissance.md`](categories/05-osint-and-reconnaissance.md) |
| **06** | **🔑 Secret Detection** | TruffleHog, Gitleaks, detect-secrets (Yelp), Whispers (Skyscanner) | [`06-secret-detection.md`](categories/06-secret-detection.md) |
| **07** | **☁️ Cloud Security (CSPM, IaC)** | Prowler, Checkov, ScoutSuite, KICS, CloudFox | [`07-cloud-and-iac-security.md`](categories/07-cloud-and-iac-security.md) |
| **08** | **🐳 Container & Kubernetes** | Falco, kube-bench, kube-hunter, Cosign (Sigstore), Hadolint | [`08-container-and-kubernetes-security.md`](categories/08-container-and-kubernetes-security.md) |
| **09** | **🤖 Autonomous AI Agents & LLM** | Shannon (pentester), REA (reverse-engineer), Audit Skill, Garak, Promptfoo | [`09-autonomous-agents-and-ai-security.md`](categories/09-autonomous-agents-and-ai-security.md) |
| **10** | **🌐 Network & Port Scanning** | Nmap, Masscan, RustScan, Naabu, Httpx, Bettercap | [`10-network-security-and-port-scanning.md`](categories/10-network-security-and-port-scanning.md) |
| **11** | **🚨 SIEM, SOC & Incident Response** | Wazuh, Suricata, Zeek, Velociraptor (VQL), TheHive, MISP | [`11-siem-soc-and-incident-response.md`](categories/11-siem-soc-and-incident-response.md) |
| **12** | **🔐 Cryptography & PKI** | Step-CA, OpenBao (Vault), Age, SOPS | [`12-cryptography-and-pki.md`](categories/12-cryptography-and-pki.md) |
| **13** | **📐 Threat Modeling & Risk** | OWASP Threat Dragon, PyTM, Google VSAQ, STRIDE | [`13-threat-modeling-and-risk.md`](categories/13-threat-modeling-and-risk.md) |
| **14** | **📚 Essential Books & Papers** | Shostack, Stuttard, Aumasson, Kleppmann, Diffie-Hellman, RSA, Thompson | [`14-books-and-academic-papers.md`](categories/14-books-and-academic-papers.md) |
| **15** | **🍯 Honeypots & Deception** | Cowrie, Dionaea, T-Pot, Canarytokens, Heralding | [`15-honeypots-and-deception.md`](categories/15-honeypots-and-deception.md) |
| **16** | **🔬 Reverse Engineering & Exploitation** | Ghidra (NSA), Radare2, Cutter, Pwntools, Angr, Frida | [`16-reverse-engineering-and-binary-exploitation.md`](categories/16-reverse-engineering-and-binary-exploitation.md) |
| **17** | **🔎 Digital Forensics & Memory** | Volatility 3, Autopsy, Sleuth Kit, YARA, Plaso, OSQuery | [`17-digital-forensics-and-memory-analysis.md`](categories/17-digital-forensics-and-memory-analysis.md) |
| **18** | **🎯 Web Proxies & Fuzzers** | ffuf, Gobuster, WPScan, mitmproxy, JWT Tool | [`18-web-proxies-and-fuzzers.md`](categories/18-web-proxies-and-fuzzers.md) |
| **19** | **⚔️ Red Teaming & C2** | Metasploit, Caldera (MITRE), Sliver, Atomic Red Team, Mimikatz | [`19-red-teaming-and-c2.md`](categories/19-red-teaming-and-c2.md) |
| **20** | **🔓 Password Cracking & Wordlists** | Hashcat, John the Ripper, SecLists, CyberChef (GCHQ) | [`20-password-cracking-and-wordlists.md`](categories/20-password-cracking-and-wordlists.md) |

---

## 🤝 Contributing / Contribuindo / Contribuyendo

1. Consulte o contrato de governança em [AGENTS.md](AGENTS.md).
2. Cada ferramenta proposta deve ser **open source** e mantida ativamente.
3. Repositórios do GitHub devem incluir o badge dinâmico de stars: `[![Stars](https://img.shields.io/github/stars/<owner>/<repo>?style=social)](https://github.com/owner/repo)`.
4. Mantenha as anotações trilíngues (🇺🇸 EN / 🇧🇷 PT / 🇪🇸 ES).
5. Submeta um Pull Request assinado com GPG.
