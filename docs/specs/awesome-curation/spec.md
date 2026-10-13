# Spec: Curadoria Abrangente de Segurança Open Source (`awesome-curation`)

## 1. Contexto & Motivação
O repositório [`SecurityStandards/awesome-security`](https://github.com/SecurityStandards/awesome-security) deve se tornar a lista de referência definitiva para ferramentas e padrões de segurança de código aberto (Open Source), incorporando as principais categorias operacionais: OSINT, SAST, DAST, SCA, Secrets Detection, Container/K8s Security, Cloud Security, Red Team / Pentesting, Threat Intelligence, SIEM/SOC e Agentes de IA.

## 2. Requisitos & Escopo

### Requisitos Funcionais (RF)
* **RF01:** Adicionar seções detalhadas para as principais técnicas:
  * **SAST** (Static Application Security Testing)
  * **DAST** (Dynamic Application Security Testing)
  * **SCA** (Software Composition Analysis & Dependency Scanning)
  * **OSINT** (Open Source Intelligence & Reconnaissance)
  * **Secrets Detection** (Varredura de credenciais e tokens)
  * **Container & Kubernetes Security**
  * **Cloud Security (CSPM / CIEM)**
  * **Network Security & Port Scanning**
  * **Threat Intelligence & SIEM**
  * **IA & Agentes Autônomos de Segurança**
* **RF02:** Foco estrito em projetos **Open Source** consolidados.
* **RF03:** Adicionar contagem de estrelas (GitHub Stars) dinâmica/atualizada via badges Shields.io (`![Stars](https://img.shields.io/github/stars/<owner>/<repo>?style=flat-square)`) em cada projeto hospedado no GitHub.
* **RF04:** Organizar com sumário navegável e padronização visual impecável.

### Requisitos Não-Funcionais (RNF)
* **RNF01:** Seguir o padrão canônico do [awesome-list](https://awesome.re).
* **RNF02:** Governança Spec-Driven Domain-Based (`docs/specs/awesome-curation/`).

## 3. Critérios de Aceite
- [ ] Todas as seções técnicas implementadas com ferramentas de ponta.
- [ ] Badges de estrelas do GitHub adicionados em cada repositório.
- [ ] README.md formatado e revisado.
- [ ] Commits assinados via GPG.
