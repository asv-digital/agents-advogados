# Agentes para Advogados — 56 subagentes Claude Code

56 subagentes especializados para advogados brasileiros, prontos para uso no Claude Code. Cada agente é um especialista em uma peça/rotina específica do escritório de advocacia — petições iniciais, contestações, recursos, cálculos, pareceres, contratos — que atua proativamente quando o contexto da conversa bate com sua especialidade.

## Como instalar

1. Clone este repo:
   ```bash
   git clone https://github.com/asv-digital/agents-advogados.git
   ```

2. Copie os agentes para o seu projeto Claude Code:
   ```bash
   cp -r agents-advogados/agents/* /caminho/do/seu/projeto/.claude/agents/
   ```

   Ou, para uso global: `~/.claude/agents/`.

## Como usar

- **Automático**: "preciso contestar uma ação de cobrança em 15 dias" → Claude delega para `contestacao-civel`.
- **Manual**: "use o agente `mandado-seguranca-tributario` para discutir Tema 69 do meu cliente".
- **Em pipeline**: `peticao-inicial-civel` → após sentença, `apelacao-civel` → após trânsito, `cumprimento-sentenca`.

## Catálogo (56 agentes)

### Cível
01 Petição inicial · 02 Contestação · 03 Apelação · 04 Agravo de instrumento · 05 Embargos de declaração
06 Cobrança · 07 Danos morais · 08 Danos materiais · 09 Revisional de contrato · 10 Rescisória

### Trabalhista
11 Reclamação trabalhista · 12 Defesa do empregador · 13 Cálculo de verbas · 14 Horas extras
15 Recurso ordinário · 16 Recurso de revista

### Família e Sucessões
17 Divórcio consensual · 18 Divórcio litigioso · 19 Alimentos
20 Inventário extrajudicial · 21 Inventário judicial · 22 Partilha
23 Guarda compartilhada · 24 União estável

### Criminal
25 Resposta à acusação · 26 Alegações finais · 27 Habeas corpus · 28 Apelação · 29 Revisão criminal

### Tributário
30 Mandado de segurança · 31 Anulatória de débito · 32 Embargos à execução fiscal
33 Exceção de pré-executividade · 34 Recuperação tributária

### Empresarial
35 Recuperação judicial · 36 Falência · 37 Dissolução de sociedade
38 Contrato social · 39 Acordo de acionistas

### Consumidor
40 Reclamação Procon · 41 Prática abusiva CDC · 42 Vício de produto/serviço

### Imobiliário
43 Despejo · 44 Renovatória · 45 Usucapião extrajudicial · 46 Usucapião judicial · 47 Adjudicação compulsória

### Previdenciário
48 Aposentadoria por tempo · 49 Aposentadoria especial · 50 BPC/LOAS · 51 Auxílio-doença

### Operacional
52 Cumprimento de sentença · 53 Impugnação ao cumprimento
54 Cálculo judicial · 55 Parecer jurídico · 56 Minuta de contrato

## Avisos legais

- Os agentes refletem CPC, CLT, CDC, CTN, CP, CPP e legislação especial vigentes em 2026.
- Outputs gerados são **rascunhos**; o advogado responsável deve revisar e assumir a responsabilidade técnica (OAB, art. 32 do EAOAB).
- Templates e exemplos usam dados fictícios.

## Licença

Uso permitido para clientes ASV Digital / Bravy. Não redistribuir sem autorização.
