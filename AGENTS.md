# Contrato Canônico de Agentes de IA - SecurityStandards / awesome-security

Este documento define os requisitos mandatórios para qualquer agente trabalhando neste repositório.

## 1. Identidade & Assinatura Criptográfica (Inviolável)
- **Autor e Committer:** SEMPRE `Matheus Breguêz <matbrgz@gmail.com>`.
- **Assinatura GPG:** Todos os commits DEVEM ser assinados com a chave `B6FA8458D5176E83`.
- **Proibições:** NUNCA usar `--no-gpg-sign` ou sobrescrever autor.
- **Co-autoria da IA:** Apenas como trailer no rodapé do commit:
  `Co-Authored-By: <Agent Name> <noreply@...>`

## 2. Metodologia: Domain-Based Spec-Driven Development (SDD)
- Toda feature ou evolução segue especificações estruturadas por domínio em `docs/specs/<domain>/` com `spec.md`, `plan.md` e `tasks.md`.

## 3. Diretrizes de Qualidade do Catálogo
- Apenas ferramentas ativas e open source.
- Sempre fornecer links diretos e badges de estrelas do GitHub (`https://img.shields.io/github/stars/<owner>/<repo>?style=social`).
