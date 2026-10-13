# Awesome Security [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> Uma lista curada e abrangente de padrões de segurança, frameworks de conformidade, políticas, checklists operacionais, agentes autônomos de segurança e ferramentas essenciais mantida pela organização [`SecurityStandards`](https://github.com/SecurityStandards).

---

## 📑 Sumário

- [Padrões e Frameworks de Conformidade](#-padrões-e-frameworks-de-conformidade)
- [Políticas e Procedimentos de Segurança](#-políticas-e-procedimentos-de-segurança)
- [Checklists de Segurança](#-checklists-de-segurança)
- [Avaliação de Terceiros e Riscos (Vendor Assessment)](#-avaliação-de-terceiros-e-riscos-vendor-assessment)
- [Agentes Autônomos de Segurança & IA](#-agentes-autônomos-de-segurança--ia)
- [Divulgação de Vulnerabilidades & Segurança Pública](#-divulgação-de-vulnerabilidades--segurança-pública)
- [Segurança de Aplicações (AppSec)](#-segurança-de-aplicações-appsec)
- [Segurança em Nuvem e DevOps (DevSecOps)](#-segurança-em-nuvem-e-devops-devsecops)
- [Contribuindo](#-contribuindo)

---

## 🏛️ Padrões e Frameworks de Conformidade

* [NIST Cybersecurity Framework (CSF) 2.0](https://www.nist.gov/cyberframework) - Estrutura de referência global do governo dos EUA para gerenciamento e redução de riscos cibernéticos.
* [ISO/IEC 27001](https://www.iso.org/standard/27001) - Padrão internacional para implementação de um Sistema de Gestão de Segurança da Informação (SGSI).
* [CIS Critical Security Controls](https://www.cisecurity.org/controls) - Conjunto priorizado de 18 salvaguardas essenciais para mitigar a maioria das ameaças cibernéticas.
* [PCI DSS v4.0](https://www.pcisecuritystandards.org/) - Padrão de segurança de dados obrigatório para empresas que processam dados de cartões de pagamento.
* [HIPAA Security Rule](https://www.hhs.gov/hipaa/for-professionals/security/index.html) - Diretrizes federais dos EUA para proteção de informações de saúde eletrônicas protegidas (ePHI).
* [SOC 2 (AICPA Trust Services Criteria)](https://www.aicpa-cima.com/topic/audit-assurance/audit-and-assurance-greater-than-soc-2) - Relatório de auditoria de controles internos focado em segurança, disponibilidade e confidencialidade.
* [FedRAMP](https://www.fedramp.gov/) - Programa federal de gerenciamento de riscos e autorização de serviços em nuvem dos EUA.

---

## 📜 Políticas e Procedimentos de Segurança

* [SecurityStandards / policies](https://github.com/SecurityStandards/security-standards/tree/main/policies) - Coleção completa de modelos de políticas mapeadas para HIPAA, NIST CSF, PCI DSS e CIS Controls.
* [JupiterOne Security Policy Templates](https://github.com/JupiterOne/security-policy-templates) - Repositório upstream de políticas de segurança prontas para auditorias.
* [SANS Information Security Policy Templates](https://www.sans.org/information-security-policy/) - Modelos de políticas de segurança gratuitos desenvolvidos pelo SANS Institute.

---

## ✅ Checklists de Segurança

* [SaaS CTO Security Checklist](https://github.com/SecurityStandards/security-standards/tree/main/checklists/cto-security) - Checklist conciso para líderes técnicos e fundadores de SaaS cobrindo código, acessos, dados e operações.
* [DevOps Security Checklist](https://github.com/SecurityStandards/security-standards/tree/main/checklists/devops-security) - Guia essencial de higiene de segurança para pipelines CI/CD, clusters de containers e nuvem.
* [OWASP Web Security Testing Guide (WSTG)](https://owasp.org/www-project-web-security-testing-guide/) - O checklist e guia definitivo de testes de penetração em aplicações web.
* [OWASP API Security Top 10](https://owasp.org/www-project-api-security/) - Os 10 riscos mais críticos de segurança em APIs modernas.

---

## 📝 Avaliação de Terceiros e Riscos (Vendor Assessment)

* [Google VSAQ](https://github.com/SecurityStandards/security-standards/tree/main/questionnaires/vsaq) - Aplicação interativa de questionários para avaliação de postura de segurança de fornecedores.
* [CAIQ (Consensus Assessments Initiative Questionnaire)](https://cloudsecurityalliance.org/research/cloud-controls-matrix/) - Questionário padrão da Cloud Security Alliance (CSA) para avaliar provedores de nuvem.
* [SIG (Standardized Information Gathering)](https://sharedassessments.org/sig/) - Questionário abrangente da Shared Assessments para gestão de riscos de terceiros.

---

## 🤖 Agentes Autônomos de Segurança & IA

* [SecurityStandards / agent-pentester](https://github.com/SecurityStandards/agent-pentester) - Agente autônomo (Shannon) que analisa código-fonte, identifica vetores de ataque e executa exploits reais em web/APIs.
* [SecurityStandards / agent-reverse-engineer](https://github.com/SecurityStandards/agent-reverse-engineer) - Agente autônomo para engenharia reversa de comportamento de aplicativos e binários.
* [SecurityStandards / skill-security-audit](https://github.com/SecurityStandards/skill-security-audit) - Skill para coding-agents (Claude, Gemini, GPT) conduzirem auditorias de segurança em fases com achados estruturados.
* [OWASP Top 10 for LLM Applications](https://owasp.org/www-project-top-10-for-large-language-model-applications/) - Os 10 principais riscos de segurança para aplicações baseadas em modelos de linguagem (Prompt Injection, Insecure Output Handling, etc.).

---

## 🌐 Divulgação de Vulnerabilidades & Segurança Pública

* [SecurityStandards / security-page](https://github.com/SecurityStandards/security-standards/tree/main/templates/security-page) - Template completo para implementação de páginas de segurança (`/security`) em sites.
* [security.txt (RFC 9116)](https://securitytxt.org/) - Padrão de arquivo legível por máquina para permitir que pesquisadores descubram canais de reporte de segurança.
* [disclose.io](https://disclose.io/) - Movimento colaborativo para padronização de políticas de divulgação responsável e termos de porto seguro (*Safe Harbor*).

---

## 💻 Segurança de Aplicações (AppSec)

* [OWASP Top 10](https://owasp.org/www-project-top-10/) - Documento de conscientização padrão para desenvolvedores e segurança de aplicações web.
* [Semgrep](https://semgrep.dev/) - Mecanismo de análise estática leve e extensível para encontrar bugs e reforçar padrões de segurança.
* [TruffleHog](https://github.com/trufflesecurity/trufflehog) - Scanner de segredos e credenciais em repositórios Git e histórico de commits.
* [Trivy](https://github.com/aquasecurity/trivy) - Scanner abrangente de vulnerabilidades para containers, sistemas de arquivos e repositórios.

---

## ☁️ Segurança em Nuvem e DevOps (DevSecOps)

* [Prowler](https://github.com/prowler-cloud/prowler) - Ferramenta de auditoria e conformidade de segurança para AWS, Azure e GCP alinhada a CIS Benchmarks.
* [ScoutSuite](https://github.com/nccgroup/ScoutSuite) - Ferramenta de auditoria multi-cloud para avaliar a postura de segurança em ambientes de nuvem.
* [Checkov](https://github.com/bridgecrewio/checkov) - Scanner de análise estática de segurança para Infraestrutura como Código (Terraform, CloudFormation, Kubernetes).
* [Cosign (Sigstore)](https://github.com/sigstore/cosign) - Assinatura, verificação e armazenamento de contêineres e artefatos de software.

---

## 🤝 Contribuindo

Contribuições são muito bem-vindas!
1. Verifique as diretrizes em [AGENTS.md](AGENTS.md).
2. Adicione recursos relevantes mantendo a categorização e o formato da lista.
3. Submeta um Pull Request assinado com GPG.
