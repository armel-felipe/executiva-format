# Executive Format - Skill de Comunicação Executiva C-Level

Transforma textos desestruturados, emails longos ou contextos operacionais em resumos executivos de alta performance usando o **Framework Triádico de 60 Segundos**.

## 🎯 O Que Esta Skill Faz

- ✅ Transforma emails/transcrições/relatórios longos em resumos executivos
- ✅ Aplica inversão cronológica (BLUF - Bottom Line Up Front)
- ✅ Converte termos subjetivos em métricas explícitas
- ✅ Cria contraste dialético entre status quo e estado futuro otimizado
- ✅ Gera CTA triádico claro: [Ação] + [Escopo] + [Prazo]

## 📚 Framework Utilizado

Baseado no **Triálise do Contraste Executivo** (Nancy Duarte + Minto Pyramid Principle):

1. **O QUE É** - Status quo medível com métricas concretas
2. **O QUE PODERIA SER** - Estado futuro otimizado com guardrails
3. **O QUE PRECISA ACONTECER AGORA** - CTA triádico com decisão clara

## 🚀 Instalação

### Via secure-skill-installer (Recomendado)

A skill pode ser instalada em qualquer agente compatible:

```bash
# Para OpenCode/opencode
npx skills add github:marcioptea/executiva-format

# Para agents
npx skills add github:marcioptea/executiva-format

# Para Claude
npx skills add github:marcioptea/executiva-format
```

### Instalação Manual

#### OpenCode/opencode
Copie `opencode/skills/executiva-format/SKILL.md` para:
- `~/.config/opencode/skills/executiva-format/` (global)
- `.opencode/skills/executiva-format/` (projeto específico)

#### agents
Copie `agents/skills/executiva-format/SKILL.md` para:
- `~/.agents/skills/executiva-format/`

#### Claude
Copie `.claude/skills/executiva-format/SKILL.md` para:
- `~/.claude/skills/executiva-format/`

## 📖 Como Usar

### Exemplo 1: Email Operacional → Executivo

**Input:**
> "Pessoal, nas reuniões do comitê notamos que aprovação de compras >R$10k está demorando quase 15 dias corridos. O time de compras fica cobrando a diretoria por e-mail, perdemos prazos de fornecedores..."

**Skill Responde:**
```markdown
* **O QUE É:** O processo atual de aprovação de compras leva 15 dias corridos, resultando na perda recorrente de descontos comerciais.
* **O QUE PODERIA SER:** Redução do ciclo para 3 dias úteis ao eliminar 2 etapas de aprovação redundantes, mantendo 100% da governança sobre os valores.
* **O QUE PRECISA ACONTECER AGORA:** Aprovação da alteração de alçada no sistema até quinta-feira, 18h.
```

### Exemplo 2: Contexto Técnico → Executivo

**Input:**
> "Tivemos 3 quedas no mês passado, e-commerce ficou offline 4 horas. Cloud custaria R$15k/mês a mais mas resolveria estabilidade para Black Friday."

**Skill Responde:**
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

## 📊 Métricas de Qualidade

A skill aplica automaticamente:
1. **Inversão Temporal** - Começa pelo problema medível
2. **Quantificação** - Subjetivos viram números
3. **Contraste + Guardrails** - Benefício com governança mantida
4. **CTA Triádico** - [Ação] + [Escopo] + [Prazo exato]

## 🔧 Recursos Avançados

- **Versão Fala**: Script de 60 segundos para apresentação oral
- **Versão Escrita**: Formatado para email/Slack com marcadores visuais
- **Guardrails Automáticos**: Sempre menciona manutenção de governança, risco controlado
- **Verbos Executivos**: Usa apenas linguagem assertiva e ativa

## 📄 Licença

MIT License - Livre para uso e modificação.

---

**Framework Original:** Triálise do Contraste Executivo (Nancy Duarte + Minto Pyramid Principle)  
**Versão da Skill:** 1.0
