# Plano de Implementação: Separação por Idiomas

## 1. Estrutura de Arquivos
```text
awesome-security/
├── en/                         # 20 documentos em Inglês
│   ├── 01-standards-and-frameworks.md ... 20-password-cracking-and-wordlists.md
├── pt/                         # 20 documentos em Português
│   ├── 01-standards-and-frameworks.md ... 20-password-cracking-and-wordlists.md
├── es/                         # 20 documentos em Espanhol
│   ├── 01-standards-and-frameworks.md ... 20-password-cracking-and-wordlists.md
├── docs/specs/multilingual-structure/
├── AGENTS.md
├── README.md                   # Mestre em Inglês
├── README.pt.md                # Mestre em Português
└── README.es.md                # Mestre em Espanhol
```

## 2. Decisões Técnicas
- **Zero misturas de línguas**: Cada arquivo contém exclusivamente o conteúdo no idioma do diretório correspondente.
- **Interoperabilidade Total**: Compatível nativamente com visualizadores do GitHub e agentes de IA que consomem arquivos por idioma específico.
