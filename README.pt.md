# Awesome Security (Português) [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> O catálogo exaustivo e curado de padrões de segurança, frameworks de conformidade, scanners open source, agentes autônomos de IA, ferramentas ofensivas e defensivas, livros essenciais e artigos acadêmicos canônicos.

[🇺🇸 **English**](README.md) · [🇧🇷 **Português**](README.pt.md) · [🇪🇸 **Español**](README.es.md)

---

## 🧭 Índice Mestre de Categorias (Português)

Explore os 20 domínios especializados organizados em documentos Markdown dedicados com ferramentas open source, links diretos e contagem de estrelas do GitHub em tempo real:

| # | Categoria | Foco Principal & Ferramentas Chave | Link do Documento |
| :-: | :--- | :--- | :--- |
| **01** | **🏛️ Padrões & Frameworks** | NIST CSF, ISO 27001, CIS Controls, PCI DSS, OWASP Top 10, MITRE ATT&CK | [`pt/01-standards-and-frameworks.md`](pt/01-standards-and-frameworks.md) |
| **02** | **🛡️ SAST (Análise Estática)** | Semgrep, Bandit, GoSec, Brakeman, Flawfinder, NodeJsScan, Opengrep | [`pt/02-sast.md`](pt/02-sast.md) |
| **03** | **⚡ DAST (Análise Dinâmica)** | OWASP ZAP, Nuclei, Caido, Nikto, Sqlmap, Commix, Katana, Wapiti | [`pt/03-dast.md`](pt/03-dast.md) |
| **04** | **📦 SCA & SBOM** | Trivy, Google OSV-Scanner, Syft, Grype, OWASP Dependency-Check | [`pt/04-sca-and-sbom.md`](pt/04-sca-and-sbom.md) |
| **05** | **🔍 OSINT & Reconhecimento** | Sherlock, theHarvester, OWASP Amass, Subfinder, SpiderFoot, Recon-ng | [`pt/05-osint-and-reconnaissance.md`](pt/05-osint-and-reconnaissance.md) |
| **06** | **🔑 Detecção de Segredos** | TruffleHog, Gitleaks, detect-secrets (Yelp), Whispers (Skyscanner) | [`pt/06-secret-detection.md`](pt/06-secret-detection.md) |
| **07** | **☁️ Segurança em Nuvem & IaC** | Prowler, Checkov, ScoutSuite, KICS, CloudFox | [`pt/07-cloud-and-iac-security.md`](pt/07-cloud-and-iac-security.md) |
| **08** | **🐳 Containers & Kubernetes** | Falco, kube-bench, kube-hunter, Cosign (Sigstore), Hadolint | [`pt/08-container-and-kubernetes-security.md`](pt/08-container-and-kubernetes-security.md) |
| **09** | **🤖 IA & Agentes Autônomos** | Shannon (pentester), REA (engenharia reversa), Audit Skill, Garak, Promptfoo | [`pt/09-autonomous-agents-and-ai-security.md`](pt/09-autonomous-agents-and-ai-security.md) |
| **10** | **🌐 Rede & Varredura de Portas** | Nmap, Masscan, RustScan, Naabu, Httpx, Bettercap | [`pt/10-network-security-and-port-scanning.md`](pt/10-network-security-and-port-scanning.md) |
| **11** | **🚨 SIEM, SOC & Resposta** | Wazuh, Suricata, Zeek, Velociraptor (VQL), TheHive, MISP | [`pt/11-siem-soc-and-incident-response.md`](pt/11-siem-soc-and-incident-response.md) |
| **12** | **🔐 Criptografia & PKI** | Step-CA, OpenBao (Vault), Age, SOPS | [`pt/12-cryptography-and-pki.md`](pt/12-cryptography-and-pki.md) |
| **13** | **📐 Modelagem de Ameaças** | OWASP Threat Dragon, PyTM, Google VSAQ, STRIDE | [`pt/13-threat-modeling-and-risk.md`](pt/13-threat-modeling-and-risk.md) |
| **14** | **📚 Livros & Artigos Canônicos** | Shostack, Stuttard, Aumasson, Kleppmann, Diffie-Hellman, RSA, Thompson | [`pt/14-books-and-academic-papers.md`](pt/14-books-and-academic-papers.md) |
| **15** | **🍯 Honeypots & Decepção** | Cowrie, Dionaea, T-Pot, Canarytokens, Heralding | [`pt/15-honeypots-and-deception.md`](pt/15-honeypots-and-deception.md) |
| **16** | **🔬 Engenharia Reversa** | Ghidra (NSA), Radare2, Cutter, Pwntools, Angr, Frida | [`pt/16-reverse-engineering-and-binary-exploitation.md`](pt/16-reverse-engineering-and-binary-exploitation.md) |
| **17** | **🔎 Perícia Digital & Memória** | Volatility 3, Autopsy, Sleuth Kit, YARA, Plaso, OSQuery | [`pt/17-digital-forensics-and-memory-analysis.md`](pt/17-digital-forensics-and-memory-analysis.md) |
| **18** | **🎯 Proxies Web & Fuzzers** | ffuf, Gobuster, WPScan, mitmproxy, JWT Tool | [`pt/18-web-proxies-and-fuzzers.md`](pt/18-web-proxies-and-fuzzers.md) |
| **19** | **⚔️ Red Teaming & C2** | Metasploit, Caldera (MITRE), Sliver, Atomic Red Team, Mimikatz | [`pt/19-red-teaming-and-c2.md`](pt/19-red-teaming-and-c2.md) |
| **20** | **🔓 Quebra de Senhas & Wordlists** | Hashcat, John the Ripper, SecLists, CyberChef (GCHQ) | [`pt/20-password-cracking-and-wordlists.md`](pt/20-password-cracking-and-wordlists.md) |

---

## 🤝 Como Contribuir

1. Leia as diretrizes de governança em [AGENTS.md](AGENTS.md).
2. As ferramentas recomendadas devem ser **open source** e mantidas ativamente.
3. Repositórios do GitHub devem conter o badge dinâmico de stars: `[![Stars](https://img.shields.io/github/stars/<owner>/<repo>?style=social)](https://github.com/owner/repo)`.
4. Envie seu Pull Request assinado com GPG!
