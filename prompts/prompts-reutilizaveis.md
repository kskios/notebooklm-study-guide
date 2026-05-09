# Prompts Reutilizáveis

Coleção de prompts testados neste projeto. Todos funcionam no NotebookLM e em outros LLMs — basta ajustar `[VARIÁVEL]` para o seu contexto.

---

## Planejamento e Trilhas de Estudo

**Trilha progressiva por nível**
```
Com base nas fontes deste notebook, crie uma trilha de aprendizado para
alguém no nível [iniciante/intermediário/avançado] que quer dominar [TEMA].
Organize em fases com: objetivo da fase, conteúdo prioritário referenciando
as fontes disponíveis, critério de conclusão e estimativa de tempo.
Use o princípio 80/20 — foque no que gera mais resultado.
```

**Mapa de conceitos interconectados**
```
Identifique os 10 conceitos mais importantes sobre [TEMA] presentes nas fontes.
Para cada um: defina em 1 linha, liste 2 conceitos relacionados e indique
o nível de pré-requisito (básico / intermediário / avançado).
```

**Conexões entre áreas**
```
Identifique conexões não óbvias entre [ÁREA A] e [ÁREA B] presentes nas fontes.
Para cada conexão: explique o mecanismo, dê um exemplo prático e indique
por que essa relação importa para um desenvolvedor.
```

---

## Síntese e Resumo

**Resumo executivo técnico**
```
Resuma [FONTE ou TEMA] em três partes:
1. O que é e por que importa — máximo 3 linhas
2. Os 5 conceitos essenciais — em bullet points
3. Como aplicar na prática — 1 exemplo concreto

Total: no máximo 300 palavras.
```

**Comparação técnica entre conceitos**
```
Compare [CONCEITO A] e [CONCEITO B] com base nas fontes disponíveis.
Use uma tabela com os critérios: definição, uso ideal, vantagens,
desvantagens e exemplo de aplicação real.
```

**Deep dive em conceito específico**
```
Explique [CONCEITO] com profundidade técnica. Assuma que já entendo o básico.
Inclua: mecanismo interno de funcionamento, casos de uso reais, armadilhas
comuns e melhores práticas. Referencie as fontes quando disponível.
```

---

## Avaliação e Revisão

**Checklist de domínio por área**
```
Crie um checklist de 15 itens para avaliar se alguém domina [TEMA].
Cada item deve ser uma competência verificável na prática, não teórica.
Use checkboxes Markdown. Organize do básico ao avançado.
```

**Quiz de fixação com gabarito**
```
Crie 10 perguntas de múltipla escolha sobre [TEMA] baseadas nas fontes.
Para cada pergunta: 4 alternativas (uma correta), nível de dificuldade
(básico / intermediário / avançado) e explicação breve da resposta correta.
```

**Revisão espaçada — perguntas de alta retenção**
```
Com base nas fontes sobre [TEMA], gere 15 perguntas abertas para revisão ativa.
As perguntas devem exigir que eu explique o conceito com minhas próprias palavras,
não apenas recite definições. Ordene da mais fundamental à mais avançada.
```

---

## Aplicação Prática

**Projeto progressivo em três versões**
```
Sugira um projeto prático para consolidar o aprendizado sobre [TEMA].
Organize em 3 versões:
- V1 (básico — 1 dia): objetivo, tecnologias, requisito mínimo
- V2 (intermediário — 1 semana): expansões, novas features
- V3 (avançado — 1 mês): escalabilidade, boas práticas, deploy

Para cada versão inclua o critério de "pronto".
```

**Troubleshooting de conceito difícil**
```
Estou com dificuldade em entender [CONCEITO]. Explique de 3 formas diferentes:
1. Uma analogia do cotidiano
2. Um exemplo de código comentado passo a passo
3. Um diagrama em texto/ASCII mostrando o fluxo

Use as fontes disponíveis como base.
```

**Geração de glossário por área**
```
Com base nas fontes deste notebook, gere um glossário com os 20 termos
mais importantes sobre [TEMA]. Para cada termo: definição em 1 linha,
área de origem e qual fonte tem a explicação mais aprofundada.
Formate em tabela Markdown.
```

---

## Dicas de Uso

- **Sempre especifique o nível:** "assuma que sou iniciante" ou "assuma que já conheço o básico" mudam muito a resposta.
- **Nomeie as fontes:** quando o notebook tem muitas fontes, dizer "com base especificamente no OWASP Top 10 e no DeepSeek paper" direciona muito melhor.
- **Peça o formato antes de pedir o conteúdo:** incluir instrução de formato no final de todo prompt evita resposta inconsistente.
- **Verifique as citações:** sempre cheque se o que o modelo afirmou está realmente na fonte indicada.