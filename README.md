# 57 Agents Advocacia — Claude Code para advogados

**57 subagentes especializados** para advogados brasileiros, prontos para uso no Claude Code. Cada agente e um especialista em uma peca/rotina especifica do escritorio de advocacia — peticoes iniciais, contestacoes, recursos, calculos, pareceres, contratos — que atua proativamente quando o contexto da conversa bate com sua especialidade.

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

3. Reinicie o Claude Code (`/exit` e abra de novo). Confirme com `/agents`.

## Como usar

- **Automatico**: "preciso contestar uma acao de cobranca em 15 dias" -> Claude delega para `contestacao-civel`.
- **Manual**: "use o agente `mandado-seguranca-tributario` para discutir Tema 69 do meu cliente".
- **Em pipeline**: `peticao-inicial-civel` -> apos sentenca, `apelacao-civel` -> apos transito, `cumprimento-sentenca`.

## Catalogo (57 agentes)

### Civel
01 Peticao inicial · 02 Contestacao · 03 Apelacao · 04 Agravo de instrumento · 05 Embargos de declaracao
06 Cobranca · 07 Danos morais · 08 Danos materiais · 09 Revisional de contrato · 10 Rescisoria

### Trabalhista
11 Reclamacao trabalhista · 12 Defesa do empregador · 13 Calculo de verbas · 14 Horas extras
15 Recurso ordinario · 16 Recurso de revista

### Familia e Sucessoes
17 Divorcio consensual · 18 Divorcio litigioso · 19 Alimentos
20 Inventario extrajudicial · 21 Inventario judicial · 22 Partilha
23 Guarda compartilhada · 24 Uniao estavel

### Criminal
25 Resposta a acusacao · 26 Alegacoes finais · 27 Habeas corpus · 28 Apelacao · 29 Revisao criminal

### Tributario
30 Mandado de seguranca · 31 Anulatoria de debito · 32 Embargos a execucao fiscal
33 Excecao de pre-executividade · 34 Recuperacao tributaria

### Empresarial
35 Recuperacao judicial · 36 Falencia · 37 Dissolucao de sociedade
38 Contrato social · 39 Acordo de acionistas

### Consumidor
40 Reclamacao Procon · 41 Pratica abusiva CDC · 42 Vicio de produto/servico

### Imobiliario
43 Despejo · 44 Renovatoria · 45 Usucapiao extrajudicial · 46 Usucapiao judicial · 47 Adjudicacao compulsoria

### Previdenciario
48 Aposentadoria por tempo · 49 Aposentadoria especial · 50 BPC/LOAS · 51 Auxilio-doenca

### Operacional
52 Cumprimento de sentenca · 53 Impugnacao ao cumprimento
54 Calculo judicial · 55 Parecer juridico · 56 Minuta de contrato

### Direito Digital (57) — NOVO
57 LGPD / data breach / parecer LGPD / defesa em processo sancionatorio ANPD

## Avisos legais

- Os agentes refletem CPC, CLT, CDC, CTN, CP, CPP, LGPD e legislacao especial vigentes em 2026.
- Outputs gerados sao **rascunhos**; o advogado responsavel deve revisar e assumir a responsabilidade tecnica (OAB, art. 32 do EAOAB).
- Templates e exemplos usam dados ficticios.

## Licenca

Uso permitido para clientes ASV Digital / Bravy. Nao redistribuir sem autorizacao.
