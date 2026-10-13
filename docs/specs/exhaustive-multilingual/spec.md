# Spec: Catálogo Exaustivo Multilíngue (`exhaustive-multilingual`)

## 1. Contexto & Motivação
Expandir o repositório [`SecurityStandards/awesome-security`](https://github.com/SecurityStandards/awesome-security) para uma estrutura modular onde **cada seção temática torna-se um arquivo Markdown dedicado dentro de `categories/`**. Além disso, o catálogo deve abranger **livros, artigos canônicos e ferramentas open source**, com descrições e títulos em **três idiomas (Português, Inglês e Espanhol)** e contagem dinâmica de GitHub Stars.

## 2. Requisitos e Escopo
- **RF01:** Modularizar o repositório em arquivos dedicados na pasta `categories/`:
  - `01-standards-and-frameworks.md`
  - `02-sast.md` (Static Application Security Testing)
  - `03-dast.md` (Dynamic Application Security Testing)
  - `04-sca-and-sbom.md` (Software Composition Analysis)
  - `05-osint-and-reconnaissance.md` (Open Source Intelligence)
  - `06-secret-detection.md` (Secrets & Credential Leaks)
  - `07-cloud-and-iac-security.md` (CSPM, CIEM, IaC)
  - `08-container-and-kubernetes-security.md`
  - `09-autonomous-agents-and-ai-security.md`
  - `10-network-security-and-port-scanning.md`
  - `11-siem-soc-and-incident-response.md`
  - `12-cryptography-and-pki.md`
  - `13-threat-modeling-and-risk.md`
  - `14-books-and-academic-papers.md`
- **RF02:** Cada arquivo conterá descrições e notas em **Inglês, Português e Espanhol** (EN / PT / ES).
- **RF03:** Todo repositório GitHub conterá badge dinâmico de stars (`https://img.shields.io/github/stars/<owner>/<repo>?style=social`).
- **RF04:** A seção de livros e artigos trará referências fundamentais de literatura acadêmica e prática da área em EN, PT e ES.
- **RF05:** O `README.md` raiz funcionará como o portal mestre indexando todos os módulos temáticos com contadores e navegação limpa.
- **RNF01:** Apenas conteúdo definitivo sobre o assunto sem notas sobre tarefas pendentes ou processos editoriais (conforme regra de ouro da organização).

## 3. Critérios de Aceite
- [ ] 14 categorias criadas em `categories/`.
- [ ] README.md raiz atualizado como hub de navegação mestre.
- [ ] Badges dinâmicos de estrelas em todos os links do GitHub.
- [ ] Commits assinados com a chave GPG `B6FA8458D5176E83`.
