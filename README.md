# 📝 Executiva Format - Skill de Comunicação Executiva C-Level

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Skill Version](https://img.shields.io/badge/version-1.0.0-blue.svg)](https://github.com/armel-felipe/executiva-format)

> Transforma textos desestruturados, emails longos e contextos operacionais em **resumos executivos de alta performance** usando o Framework Triádico de 60 Segundos.

## 🎯 O Que Esta Skill Faz

A skill **executiva-format** aplica o **Framework Triálise do Contraste Executivo** (Nancy Duarte + Minto Pyramid Principle) para converter inputs operacionais em sínteses executivas orientadas à tomada de decisão C-Level.

### Principais Recursos

- ✅ **BLUF (Bottom Line Up Front)** - A conclusão precede a fundamentação
- ✅ **Inversão Temporal** - Foco no resultado, não na jornada da análise
- ✅ **Quantificação de Qualidade** - Subjetivos viram métricas explícitas
- ✅ **Contraste Dialético** - Status quo vs. Estado futuro otimizado
- ✅ **Guardrails Automáticos** - Benefícios com governança mantida
- ✅ **CTA Triádico** - [Ação] + [Escopo] + [Prazo exato]

## 📚 Framework: 60 Segundos Executivos

```
┌─────────────────────────────────────────────────────────────┐
│ 1. O QUE É (Status Quo Medível)                             │
│    - Problema com métricas concretas                        │
│    - Custo da inação / Impacto direto                       │
│    Max: 1-2 frases                                          │
└──────────────────┬──────────────────────────────────────────┘
                   │
                   ▼
┌─────────────────────────────────────────────────────────────┐
│ 2. O QUE PODERIA SER (Contraste)                            │
│    - Estado futuro otimizado                                │
│    - Ganho de eficiência mantendo restrições                │
│    - Sem aumentar headcount/riso                            │
│    Max: 1-2 frases                                          │
└──────────────────┬──────────────────────────────────────────┘
                   │
                   ▼
┌─────────────────────────────────────────────────────────────┐
│ 3. O QUE PRECISA ACONTECER AGORA (CTA Triádico)            │
│    - [Ação Requerida] + [Escopo/Objeto] + [Prazo Limite]   │
│    Max: 1 frase                                             │
└─────────────────────────────────────────────────────────────┘
```

## 🚀 Instalação Universal

### Via NPM (Recomendado)

```bash
# Instalar em qualquer agente compatível
npx skills add github:armel-felipe/executiva-format
```

### Instalação Manual

#### OpenCode / opencode
```bash
cp -r executiva-format ~/.config/opencode/skills/
# OU para projeto específico:
cp -r executiva-format .opencode/skills/
```

#### Hermes Agent (agents)
```bash
cp -r executiva-format ~/.agents/skills/
```

#### Claude / .claude
```bash
cp -r executiva-format ~/.claude/skills/
```

## 📖 Como Usar

### Exemplo 1: Email Operacional → Executivo

**Input do Usuário:**
> "Pessoal, nas reuniões do comitê notamos que aprovação de compras >R$10k está demorando quase 15 dias corridos. O time de compras fica cobrando a diretoria por email, perdemos prazos e descontos..."

**Output da Skill (Executivo):**
```markdown
* **O QUE É:** O processo atual de aprovação de compras leva 15 dias corridos, resultando na perda recorrente de descontos comerciais.
* **O QUE PODERIA SER:** Redução do ciclo para 3 dias úteis ao eliminar 2 etapas redundantes, mantendo 100% da governança sobre os valores.
* **O QUE PRECISA ACONTECER AGORA:** Aprovação da alteração de alçada no sistema até quinta-feira, 18h.
```

### Exemplo 2: Contexto Técnico → Executivo

**Input do Usuário:**
> "Tivemos 3 quedas no mês passado, e-commerce ficou offline 4 horas. Cloud custaria R$15k/mês a mais mas resolveria estabilidade para Black Friday."

**Output da Skill (Executivo):**
```markdown
* **O QUE É:** 4 horas de downtime no e-commerce no último mês com perda estimada de R$120 mil em vendas devido à infraestrutura legado.
* **O QUE PODERIA SER:** Disponibilidade de 99,9% e suporte à Black Friday migrando para nuvem com adição de R$15 mil/mês no orçamento de TI.
* **O QUE PRECISA ACONTECER AGORA:** Validação da aditiva contratual de infraestrutura até amanhã, às 12h.
```

## 🎯 Quando Usar Esta Skill

Use quando o usuário mencionar:
- "organizar texto"
- "criar resumo executivo"
- "formatar no estilo executivo"
- "melhorar comunicação para diretoria"
- "simplificar email para CEO"
- "preciso apresentar isso para C-Level"
- "texto muito longo para decisão rápida"

## 🔧 Regras de Transformação

| Operador | Entrada (Ruído) | Saída (Executivo) |
|----------|-----------------|-------------------|
| **Inversão Temporal** | Narrativa cronológica ("Reunimos...", "Analisamos...") | Afirmação de resultado ("Identificamos...", "Mapeamos...") |
| **Quantificação** | Termos subjetivos ("muito lento", "ineficiente") | Métricas explícitas ("8 dias de ciclo", "$50k/mês") |
| **Guardrails** | Foco apenas no benefício | Benefício + Manutenção de Governança |
| **Injunção da Decisão** | Pedidos abertos ("O que acham?") | CTA Triádico ([Ação] + [Objeto] + [Prazo]) |

## 📊 Métricas de Qualidade (Score 0-10)

A skill aplica automaticamente:
1. **Inversão Temporal** (Peso 3): Começa pelo problema medível?
2. **Métricas** (Peso 2): Todos subjetivos viraram números?
3. **Contraste + Restrição** (Peso 3): Ganho futuro com guardrails?
4. **CTA Triádico** (Peso 2): [Ação] + [Escopo] + [Prazo exato]?

## 🏗️ Estrutura do Repositório

```
executiva-format/
├── SKILL.md                          # Skill principal completa
├── README.md                         # Documentação de uso (este arquivo)
├── HUB_PUBLISHING_GUIDE.md          # Guia técnico de publicação
├── PUBLISH_INSTRUCTIONS.md          # Instruções de publicação
├── package.json                      # Pacote npm compatível
├── agents/skills/executiva-format/  # Para Hermes Agent
│   └── SKILL.md                      # Copia da skill principal
├── .claude/skills/executiva-format/ # para Claude
│   └── SKILL.md                      # Copia da skill principal
└── opencode/skills/executiva-format/# para OpenCode/opencode
    └── SKILL.md                      # Copia da skill principal
```

## 📚 Framework Teórico

Baseado no **Triálise do Contraste Executivo**:
- **Nancy Duarte** - "Resonate: Presentations, Sales Calls, and Other Stories That Stick"
- **Minto Pyramid Principle** - "The Minto Pyramid Principle: Logic in Writing, Thinking & Problem Solving"

## 📄 Licença

MIT License - Livre para uso e modificação.

```
Copyright (c) 2024 Felipe Armel

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

## 🤝 Contribuições

Contribuições são bem-vindas! Para contribuir:

1. Fork o repositório
2. Crie uma branch para sua feature (`git checkout -b feature/AmazingFeature`)
3. Commit suas mudanças (`git commit -m 'Add some AmazingFeature'`)
4. Push para a branch (`git push origin feature/AmazingFeature`)
5. Abra um Pull Request

## 📞 Suporte

Para issues e perguntas, abra um [issue no GitHub](https://github.com/armel-felipe/executiva-format/issues).

---

**Pronto para transformar sua comunicação executiva!** 🚀

Esta skill está disponível para instalação universal em:
- ✅ OpenCode / opencode
- ✅ Hermes Agent (agents)  
- ✅ Claude / .claude
- ✅ Via npm / npx skills add

[![Star this repo](https://img.shields.io/github/stars/armel-felipe/executiva-format?style=social)](https://github.com/armel-felipe/executiva-format/stargazers)
