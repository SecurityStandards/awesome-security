# Awesome Security (Español) [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> El catálogo exhaustivo y curado de estándares de seguridad, marcos de cumplimiento, escáneres de código abierto, agentes autónomos de IA, herramientas ofensivas y defensivas, libros esenciales y artículos académicos canónicos.

[🇺🇸 **English**](README.md) · [🇧🇷 **Português**](README.pt.md) · [🇪🇸 **Español**](README.es.md)

---

## 🧭 Índice Maestro de Categorías (Español)

Explore los 20 dominios especializados organizados en documentos Markdown dedicados con herramientas de código abierto, enlaces directos y recuento de estrellas de GitHub en tiempo real:

| # | Categoría | Enfoque Principal & Herramientas Clave | Enlace al Documento |
| :-: | :--- | :--- | :--- |
| **01** | **🏛️ Estándares & Marcos** | NIST CSF, ISO 27001, CIS Controls, PCI DSS, OWASP Top 10, MITRE ATT&CK | [`es/01-standards-and-frameworks.md`](es/01-standards-and-frameworks.md) |
| **02** | **🛡️ SAST (Análisis Estático)** | Semgrep, Bandit, GoSec, Brakeman, Flawfinder, NodeJsScan, Opengrep | [`es/02-sast.md`](es/02-sast.md) |
| **03** | **⚡ DAST (Análisis Dinámico)** | OWASP ZAP, Nuclei, Caido, Nikto, Sqlmap, Commix, Katana, Wapiti | [`es/03-dast.md`](es/03-dast.md) |
| **04** | **📦 SCA & SBOM** | Trivy, Google OSV-Scanner, Syft, Grype, OWASP Dependency-Check | [`es/04-sca-and-sbom.md`](es/04-sca-and-sbom.md) |
| **05** | **🔍 OSINT & Reconocimiento** | Sherlock, theHarvester, OWASP Amass, Subfinder, SpiderFoot, Recon-ng | [`es/05-osint-and-reconnaissance.md`](es/05-osint-and-reconnaissance.md) |
| **06** | **🔑 Detección de Secretos** | TruffleHog, Gitleaks, detect-secrets (Yelp), Whispers (Skyscanner) | [`es/06-secret-detection.md`](es/06-secret-detection.md) |
| **07** | **☁️ Seguridad en la Nube & IaC** | Prowler, Checkov, ScoutSuite, KICS, CloudFox | [`es/07-cloud-and-iac-security.md`](es/07-cloud-and-iac-security.md) |
| **08** | **🐳 Contenedores & Kubernetes** | Falco, kube-bench, kube-hunter, Cosign (Sigstore), Hadolint | [`es/08-container-and-kubernetes-security.md`](es/08-container-and-kubernetes-security.md) |
| **09** | **🤖 IA & Agentes Autónomos** | Shannon (pentester), REA (ingeniería inversa), Audit Skill, Garak, Promptfoo | [`es/09-autonomous-agents-and-ai-security.md`](es/09-autonomous-agents-and-ai-security.md) |
| **10** | **🌐 Red & Escaneo de Puertos** | Nmap, Masscan, RustScan, Naabu, Httpx, Bettercap | [`es/10-network-security-and-port-scanning.md`](es/10-network-security-and-port-scanning.md) |
| **11** | **🚨 SIEM, SOC & Respuesta** | Wazuh, Suricata, Zeek, Velociraptor (VQL), TheHive, MISP | [`es/11-siem-soc-and-incident-response.md`](es/11-siem-soc-and-incident-response.md) |
| **12** | **🔐 Criptografía & PKI** | Step-CA, OpenBao (Vault), Age, SOPS | [`es/12-cryptography-and-pki.md`](es/12-cryptography-and-pki.md) |
| **13** | **📐 Modelado de Amenazas** | OWASP Threat Dragon, PyTM, Google VSAQ, STRIDE | [`es/13-threat-modeling-and-risk.md`](es/13-threat-modeling-and-risk.md) |
| **14** | **📚 Libros & Artículos Canónicos** | Shostack, Stuttard, Aumasson, Kleppmann, Diffie-Hellman, RSA, Thompson | [`es/14-books-and-academic-papers.md`](es/14-books-and-academic-papers.md) |
| **15** | **🍯 Honeypots & Decepción** | Cowrie, Dionaea, T-Pot, Canarytokens, Heralding | [`es/15-honeypots-and-deception.md`](es/15-honeypots-and-deception.md) |
| **16** | **🔬 Ingeniería Inversa** | Ghidra (NSA), Radare2, Cutter, Pwntools, Angr, Frida | [`es/16-reverse-engineering-and-binary-exploitation.md`](es/16-reverse-engineering-and-binary-exploitation.md) |
| **17** | **🔎 Informática Forense & Memoria** | Volatility 3, Autopsy, Sleuth Kit, YARA, Plaso, OSQuery | [`es/17-digital-forensics-and-memory-analysis.md`](es/17-digital-forensics-and-memory-analysis.md) |
| **18** | **🎯 Proxies Web & Fuzzers** | ffuf, Gobuster, WPScan, mitmproxy, JWT Tool | [`es/18-web-proxies-and-fuzzers.md`](es/18-web-proxies-and-fuzzers.md) |
| **19** | **⚔️ Red Teaming & C2** | Metasploit, Caldera (MITRE), Sliver, Atomic Red Team, Mimikatz | [`es/19-red-teaming-and-c2.md`](es/19-red-teaming-and-c2.md) |
| **20** | **🔓 Descifrado de Contraseñas & Wordlists** | Hashcat, John the Ripper, SecLists, CyberChef (GCHQ) | [`es/20-password-cracking-and-wordlists.md`](es/20-password-cracking-and-wordlists.md) |

---

## 🤝 Cómo Contribuir

1. Lea las pautas de ingeniería en [AGENTS.md](AGENTS.md).
2. Las herramientas recomendadas deben ser **de código abierto** y mantenerse activamente.
3. Los repositorios de GitHub deben contener la insignia dinámica de estrellas: `[![Stars](https://img.shields.io/github/stars/<owner>/<repo>?style=social)](https://github.com/owner/repo)`.
4. ¡Envíe su Pull Request firmado con GPG!
