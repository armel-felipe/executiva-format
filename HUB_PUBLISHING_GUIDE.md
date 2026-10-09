# 📦 Guia de Publicação no Hub - Skill Executiva Format

## ✅ Status Atual

Sua skill **executiva-format** foi criada com sucesso e está pronta para publicação!

### Estrutura Multi-Agente Criada:

```
executiva-format/
├── SKILL.md                          # Arquivo principal da skill
├── README.md                         # Documentação em português
├── HUB_PUBLISHING_GUIDE.md          # Este guia (em inglês)
├── package.json                      # Pacote npm compatível
├── agents/
│   └── skills/
│       └── executiva-format/         # Para agents/skills
│           └── SKILL.md              # Copia da skill principal
├── .claude/
│   └── skills/
│       └── executiva-format/         # Para Claude/.claude
│           └── SKILL.md              # Copia da skill principal
└── opencode/
    └── skills/
        └── executiva-format/         # Para OpenCode/opencode
            └── SKILL.md              # Copia da skill principal
```

## 🎯 O Que Esta Skill Faz

A skill **executiva-format** transforma textos desestruturados, emails longos ou contextos operacionais em **resumos executivos de alta performance** usando o **Framework Triádico de 60 Segundos**.

### Principais Recursos:
- ✅ Inversão cronológica (BLUF - Bottom Line Up Front)
- ✅ Quantificação de métricas (subjetivo → números)
- ✅ Contraste dialético entre status quo e estado futuro otimizado
- ✅ CTA triádico claro: [Ação] + [Escopo] + [Prazo]

### Framework Utilizado:
Baseado no **Triálise do Contraste Executivo** (Nancy Duarte + Minto Pyramid Principle)

```
┌─────────────────────────────────────────────────────┐
│ 1. O QUE É (Status Quo Medível)                     │
│    - Problema com métricas concretas                │
│    - Custo da inação / Impacto direto               │
└──────────────────┬──────────────────────────────────┘
                   │
                   ▼
┌─────────────────────────────────────────────────────┐
│ 2. O QUE PODERIA SER (Contraste)                    │
│    - Estado futuro otimizado                        │
│    - Guardrails: sem aumentar headcount/risco       │
└──────────────────┬──────────────────────────────────┘
                   │
                   ▼
┌─────────────────────────────────────────────────────┐
│ 3. O QUE PRECISA ACONTECER AGORA (CTA Triádico)     │
│    - [Ação] + [Escopo] + [Prazo exato]              │
└─────────────────────────────────────────────────────┘
```

## 📚 Instalação Universal

A skill pode ser instalada em **qualquer agente compatível**:

### Via NPM (Recomendado)

```bash
# Adicionar ao seu repositório do GitHub primeiro (veja abaixo)
npx skills add github:marcioptea/executiva-format
```

### Instalação Manual

#### Para OpenCode/opencode:
```bash
cp -r executiva-format ~/.config/opencode/skills/
# OU para projeto específico:
cp -r executiva-format .opencode/skills/
```

#### Para agents:
```bash
cp -r executiva-format ~/.agents/skills/
```

#### Para Claude:
```bash
cp -r executiva-format ~/.claude/skills/
```

## 🚀 Próximos Passos para Publicar no Hub

### Opção 1: Publicar via GitHub (Recomendado)

1. **Criar repositório público no GitHub:**
   ```bash
   # Nome do repositório: skill-executiva-format OU executiva-format
   ```

2. **Fazer push dos arquivos:**
   ```bash
   cd /Users/mac/llm\ server/projetos/playground/executiva-format
   
   git init
   git add .
   git commit -m "Initial commit: Executiva Format skill"
   
   # Criar repositório no GitHub via web ou API
   # Depois fazer push:
   git remote add origin https://github.com/marcioptea/executiva-format.git
   git branch -M main
   git push -u origin main
   ```

3. **Disponibilizar para instalação:**
   - Usuários podem instalar com: `npx skills add github:marcioptea/executiva-format`

### Opção 2: Publicar via OpenWork Cloud Marketplace

1. Conectar conta GitHub em **Settings > Connect**
2. Usar capability: `postPluginsImportMcpsFromGithubUrl`
3. Importar repositório no marketplace da organização

## 📊 Testes e Validação

### Exemplo de Uso:

**Input Operacional:**
> "Pessoal, nas reuniões do comitê notamos que aprovação de compras >R$10k está demorando quase 15 dias corridos. O time de compras fica cobrando a diretoria por email, perdemos prazos e descontos..."

**Output da Skill (Executivo):**
```markdown
* **O QUE É:** O processo atual de aprovação de compras leva 15 dias corridos, resultando na perda recorrente de descontos comerciais.
* **O QUE PODERIA SER:** Redução do ciclo para 3 dias úteis ao eliminar 2 etapas redundantes, mantendo 100% da governança sobre os valores.
* **O QUE PRECISA ACONTECER AGORA:** Aprovação da alteração de alçada no sistema até quinta-feira, 18h.
```

## 🔧 Metadados do Pacote

- **Nome:** `executiva-format`
- **Versão:** `1.0.0`
- **Licença:** MIT
- **Autor:** Marcio Penta Teixeira
- **Keywords:** skill, executive-communication, c-level, business-writing, openwork, claude-code, opencode

## 📝 Licença

MIT License - Livre para uso e modificação.

---

**Pronto para publicar!** 🎉

A estrutura multi-agente está completa e a skill pode ser instalada em:
- ✅ OpenCode / opencode
- ✅ agents (Hermes Agent)
- ✅ Claude / .claude
- ✅ Via npm / npx skills add

Para finalizar publicação, escolha uma das opções acima e siga os passos!
