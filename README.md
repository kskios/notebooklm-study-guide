<div align="center">

# 🧠 Segundo Cérebro para Desenvolvedores
**Projeto DIO · NotebookLM · Programação & Tecnologia**

---

## Resumo Executivo

**Objetivo:** Usar o NotebookLM para construir um "segundo cérebro" técnico — um sistema de estudo estruturado cobrindo programação, Linux, segurança da informação, IA e engenharia de prompts.

**Ferramentas:** NotebookLM (Google), ClaudeAI (para apoio na documentação), VSCode

**O que foi entregue:**
- Notebook com +20 fontes curadas e organizadas por área
- Trilha de aprendizado gerada e refinada via prompts
- Documentação do processo completo (incluindo erros e ajustes)
- Glossário técnico, miniguia de estudo e biblioteca de prompts reutilizáveis

**Principal aprendizado:** A qualidade do que você extrai de uma IA depende diretamente da qualidade do que você pergunta. Engenharia de prompts não é um "truque" — é uma habilidade real.

---

## Índice

- [Contexto](#contexto)
- [O que é o NotebookLM](#o-que-é-o-notebooklm)
- [Objetivos de Aprendizagem](#objetivos-de-aprendizagem)
- [Curadoria de Fontes](#curadoria-de-fontes)
- [Engenharia de Prompts](#engenharia-de-prompts)
- [Troubleshooting & Dificuldades](#troubleshooting--dificuldades)
- [Miniguia de Estudo](#miniguia-de-estudo)
- [Glossário Técnico](#glossário-técnico)
- [Reflexões Finais](#reflexões-finais)
- [Estrutura do Repositório](#estrutura-do-repositório)
- [Referências](#referências)

---

## Contexto

Quem está aprendendo tecnologia sabe bem esse problema: você termina um curso, começa outro, acumula PDFs, salva threads no Twitter, cria pastas no Notion — e no fim, quando precisa lembrar algo específico, não acha nada.

A ideia deste projeto foi atacar exatamente isso. Em vez de só consumir conteúdo, o objetivo foi **construir um sistema** — um espaço onde o conhecimento se conecta, pode ser consultado rapidamente e cresce junto com o aprendizado.

O tema escolhido foi amplo de propósito: **Programação e Tecnologia** de forma integrada, passando por:

| Área | O que foi coberto |
|------|-------------------|
| Fundamentos | Algoritmos, Estruturas de Dados, Lógica de Programação |
| Linguagem | Python 3, POO, Princípios SOLID |
| Sistemas | Linux (Ubuntu, Kali), terminal, permissões, redes |
| Segurança | OWASP Top 10 Web, API e LLMs |
| IA & Prompts | Arquitetura de LLMs, técnicas de prompting, tendências 2025 |

O NotebookLM foi o motor disso tudo — não como substituto do estudo, mas como ferramenta de síntese e consulta sobre o material que eu mesmo selecionei.

---

## O que é o NotebookLM

O NotebookLM é uma ferramenta do Google que conecta um espaço de notas a um modelo de linguagem ancorado nas suas próprias fontes. A diferença principal em relação a um chatbot comum é que ele **só responde com base no que você carregou** — e cita de onde veio cada informação.

Na prática, isso muda muito. Você pode carregar um PDF acadêmico, uma documentação técnica e um vídeo do YouTube ao mesmo tempo, e depois perguntar como esses três materiais se relacionam. A resposta vem com referências, não com achismos.

Funcionalidades que usei neste projeto:
- Carregamento de PDFs, URLs e vídeos do YouTube
- Geração de resumos, FAQs e guias de estudo
- Consultas cruzadas entre múltiplas fontes
- Geração de podcast automático sobre o conteúdo

> Acesse o notebook: [NotebookLM — Segundo Cérebro para Devs](https://notebooklm.google.com/notebook/6d87dcfa-b06d-4db4-adf1-f5642b27bf8b/preview)

![Interface do NotebookLM com as fontes organizadas por área](images/notebooklm-overview.png)

---

## Objetivos de Aprendizagem

Os objetivos foram divididos em três camadas, do mais concreto ao mais estratégico:

**Técnico**
- [ ] Dominar algoritmos e estruturas de dados essenciais
- [ ] Entender Python 3 com profundidade real, não superficial
- [ ] Usar Linux com confiança no terminal e entender como o sistema funciona
- [ ] Conhecer as principais vulnerabilidades e como se proteger delas (OWASP)

**Sistêmico**
- [ ] Pensar em arquitetura, não apenas em código que funciona
- [ ] Entender como LLMs funcionam por dentro e onde eles falham
- [ ] Desenvolver uma visão integrada entre áreas (segurança, algoritmos, IA)

**Gestão do Conhecimento**
- [ ] Criar um sistema de estudo que dure e se expanda com o tempo
- [ ] Documentar o processo como portfólio, não apenas o resultado final
- [ ] Aprender a usar IA como ferramenta de raciocínio, não de atalho

---

## Curadoria de Fontes

A seleção das fontes levou em conta três critérios: confiabilidade, profundidade e complementaridade. O objetivo foi cobrir as áreas de formas diferentes — documentação oficial, livro acadêmico, aula prática e referência rápida para a mesma área quando possível.

### Documentação Oficial

| Fonte | Área |
|-------|------|
| Python 3.14 Docs | Referência primária para sintaxe, stdlib e boas práticas |
| Ubuntu Docs | Sistema operacional, servidor e configuração |
| Kali Linux Docs | Segurança ofensiva e ferramentas de pentest |

### Livros Open Source

| Fonte | Link |
|-------|------|
| Algoritmos e Estrutura de Dados 1 — UFPR | [PDF](https://www.inf.ufpr.br/marcos/livro_alg1/livro_alg1.pdf) |
| Entendendo Algoritmos — Aditya Bhargava | [PDF](https://www.kufunda.net/publicdocs/Entendendo%20Algoritmos%20Um%20guia%20ilustrado%20para%20programadores%20e%20outros%20curiosos%20(Aditya%20Y.%20Bhargava).pdf) |

### Cursos em Vídeo (YouTube)

| Curso | Instrutor |
|-------|-----------|
| Algoritmos e Lógica de Programação | Prof. Gustavo Guanabara |
| Python 3 Completo | Prof. Gustavo Guanabara |
| Análise e Desenvolvimento de Sistemas | Carcamanjo |
| Linux — Primeiros Passos | Curso em Vídeo |
| Segurança da Informação (Módulo 00) | Curso em Vídeo |

### Segurança (OWASP)

| Documento | Foco |
|-----------|------|
| OWASP Top 10:2025 | Vulnerabilidades críticas em aplicações web |
| OWASP API Security Top 10 | Segurança de APIs REST |
| OWASP Top 10 for LLMs | Riscos específicos de aplicações com IA |

### Inteligência Artificial & Prompt Engineering

| Fonte | Destaque |
|-------|----------|
| DeepSeek-V3 Technical Report ([arXiv](https://arxiv.org/pdf/2412.19437)) | Arquitetura interna de LLMs modernos |
| State of AI Report 2025 | Panorama global do setor |
| Prompt Engineering 101 — Codecademy | Zero-Shot, One-Shot, Few-Shot |
| Técnicas de Prompting — IBM | Aplicação prática em contextos reais |
| Shot-Based Prompting — Learn Prompting | Exemplos e variações |

### Referências Rápidas

- Linux Commands Cheat Sheet — [Zero To Mastery](https://zerotomastery.io/cheatsheets/linux-commands-cheat-sheet/)
- Linux Cheat Sheet — Cyberkraft
- PowerShell Commands — NinjaOne
- Windows Enumeration 2025
- Common Ports Cheat Sheet

---

## Engenharia de Prompts

Essa foi a parte mais interessante (e mais trabalhosa) do projeto. A diferença entre uma pergunta vaga e uma pergunta bem estruturada é enorme — e não fica óbvio até você ver os dois resultados lado a lado.

O framework que funcionou melhor foi organizar cada prompt em quatro dimensões:

```
PAPEL     → quem a IA deve "ser" para responder
CONTEXTO  → qual é o escopo e meu nível atual
TAREFA    → o que exatamente eu preciso
FORMATO   → como quero receber a resposta
```

### Evolução dos Prompts

**Prompt 1 — Visão geral do notebook**

Versão inicial:
```
Resuma o conteúdo deste notebook.
```
Resultado: um parágrafo genérico que poderia ter sido escrito por qualquer chatbot.

Versão refinada:
```
Com base em todas as fontes deste notebook, crie uma visão geral estruturada
do conhecimento disponível. Organize em grandes áreas temáticas com 3 a 5
pontos cada. Use linguagem técnica, mas acessível para desenvolvedor júnior/pleno.
```
Resultado: estrutura em 6 blocos temáticos com citações diretas das fontes — algo que eu realmente consegui usar para estudar.

---

**Prompt 2 — Trilha de aprendizado**

Versão inicial:
```
Como devo estudar programação?
```
Resultado: conselhos genéricos que você encontra em qualquer artigo do Medium.

Versão refinada:
```
Com base apenas nas fontes deste notebook, crie uma trilha de aprendizado
progressiva para um desenvolvedor iniciante que quer chegar ao nível pleno.
Organize em fases com: objetivo, conteúdo a estudar referenciando as fontes
disponíveis, critério de conclusão e estimativa de tempo. Priorize o 80/20.
```
Resultado: cinco fases com referências cruzadas entre os materiais, conectando o livro de algoritmos da UFPR com as aulas do Guanabara e a documentação do Python.

---

**Prompt 3 — Conexões entre áreas**

Esse foi o mais revelador. A pergunta era simples:
```
Identifique conexões entre Algoritmos, Segurança da Informação (OWASP) e
Prompt Engineering presentes nas fontes. Como o domínio de uma área
potencializa as outras? Dê exemplos práticos.
```
A resposta conectou como raciocínio algorítmico ajuda a entender vetores de ataque e como pensar em passos lógicos e estruturados melhora a qualidade dos prompts. Não é uma conexão óbvia, mas faz todo sentido depois que você vê.

---

**Tabela comparativa de abordagens**

| Abordagem | Qualidade da Resposta |
|-----------|----------------------|
| Zero-Shot vago ("explique algoritmos") | ⭐⭐ genérica, pouco útil |
| Zero-Shot específico (conceito + contexto + comparação) | ⭐⭐⭐⭐ precisa |
| Few-Shot (com exemplo do formato desejado) | ⭐⭐⭐⭐⭐ consistente |
| Chain of Thought ("pense passo a passo antes de responder") | ⭐⭐⭐⭐⭐ ótimo para conceitos complexos |
| PAPEL + CONTEXTO + TAREFA + FORMATO | ⭐⭐⭐⭐⭐ melhor resultado geral |

---

## Troubleshooting & Dificuldades

Essa seção existe porque errar faz parte — e documentar os erros é o que torna um portfólio honesto.

**Problema 1: Respostas genéricas demais**

O NotebookLM tende a dar respostas introdutórias mesmo quando a fonte tem profundidade técnica. Aconteceu bastante com o conteúdo de LLMs e com o OWASP.

Solução: adicionar instrução explícita de nível:
```
Assuma que já conheço o básico. Vá direto ao mecanismo técnico.
Cite números, arquiteturas e termos específicos quando disponíveis nas fontes.
```

**Problema 2: Modelo priorizando fontes erradas**

Com muitas fontes carregadas, o modelo às vezes ignorava materiais relevantes e focava nas fontes mais longas ou mais recentes.

Solução: nomear explicitamente quais fontes consultar em cada pergunta:
```
Com base especificamente no OWASP Top 10:2025 e no DeepSeek Technical Report...
```

**Problema 3: Inconsistências em consultas muito amplas**

Prompts que pediam síntese de muitas fontes ao mesmo tempo às vezes misturavam informações de fontes diferentes de forma imprecisa. O modelo não "mente" — mas ele interpola, e isso pode gerar afirmações ligeiramente incorretas.

Solução: prompts menores e mais focados, com verificação manual das citações antes de incorporar qualquer resposta ao material de estudo.

**Problema 4: Formato inconsistente**

Sem instrução de formato, as respostas variavam entre parágrafos, listas e tabelas de forma aleatória — o que dificulta bastante usar o conteúdo no Notion ou Obsidian.

Solução: um bloco padrão no final de cada prompt:
```
Formate em Markdown: título H2, subtítulos H3, negrito para termos-chave,
blocos de código para exemplos.
```

---

**O que aprendi com os erros**

| Lição | Impacto |
|-------|---------|
| Prompt vago = resposta vaga. Sempre. | Alto |
| Nomear a fonte desejada melhora a precisão significativamente | Alto |
| Verificar as citações é obrigatório, não opcional | Crítico |
| Menos fontes por consulta = mais foco na resposta | Médio |
| Formato da resposta precisa estar no prompt | Alto |

---

## Miniguia de Estudo

Esse é o produto central do projeto — um guia consolidado para consulta e revisão contínua.

### Mapa do Conhecimento

```
SEGUNDO CÉREBRO PARA DEVS
│
├── FUNDAMENTOS
│   ├── Lógica de Programação
│   ├── Algoritmos e Complexidade (Big O)
│   └── Estruturas de Dados
│
├── PYTHON 3
│   ├── Sintaxe, Tipos e Funções
│   ├── POO e Herança
│   └── SOLID na prática
│
├── LINUX
│   ├── Terminal e Comandos Essenciais
│   ├── Permissões e Processos
│   └── Redes e Serviços
│
├── SEGURANÇA
│   ├── OWASP Top 10 Web (2025)
│   ├── OWASP API Security
│   └── OWASP LLM Top 10
│
├── INTELIGÊNCIA ARTIFICIAL
│   ├── Arquitetura de LLMs
│   └── Prompt Engineering (Zero/One/Few-Shot, CoT)
│
└── ENGENHARIA DE SOFTWARE
    ├── Design Patterns
    ├── Clean Code
    └── SOLID
```

---

### Algoritmos — Big O em 60 segundos

| Complexidade | Nome | Exemplo |
|-------------|------|---------|
| O(1) | Constante | Acesso a array por índice |
| O(log n) | Logarítmica | Busca Binária |
| O(n) | Linear | Busca sequencial |
| O(n log n) | Linearítmica | Merge Sort |
| O(n²) | Quadrática | Bubble Sort |
| O(2ⁿ) | Exponencial | Força bruta em subconjuntos |

**Regra prática:** se o input pode crescer, O(n²) ou pior deve ser evitado. O(log n) é o que você quer ao projetar buscas.

---

### Python 3 — SOLID resumido

```python
# S — Single Responsibility: cada classe faz uma coisa só
class GeradorRelatorio:
    def gerar(self, dados): ...

class EnviadorEmail:
    def enviar(self, arquivo): ...

# O — Open/Closed: aberto para extensão, fechado para modificação
from abc import ABC, abstractmethod

class Forma(ABC):
    @abstractmethod
    def area(self) -> float: ...

class Circulo(Forma):
    def area(self) -> float:
        return 3.14 * self.raio ** 2

# Type hints tornam o código autodocumentado
def calcular_desconto(preco: float, percentual: float) -> float:
    return preco * (1 - percentual / 100)
```

---

### Segurança — OWASP Top 10:2025

| # | Vulnerabilidade | Prevenção |
|---|----------------|-----------|
| A01 | Broken Access Control | Verificar permissão em cada endpoint |
| A02 | Cryptographic Failures | TLS, bcrypt, sem MD5/SHA1 |
| A03 | Injection | Prepared statements, validação de entrada |
| A04 | Insecure Design | Threat modeling desde o início |
| A05 | Security Misconfiguration | Hardening, sem debug em produção |
| A06 | Vulnerable Components | Dependabot, Snyk |
| A07 | Auth Failures | MFA, rate limiting, expiração de sessão |
| A08 | Data Integrity Failures | Assinatura de código, SBOM |
| A09 | Logging Failures | Logs estruturados, alertas em tempo real |
| A10 | SSRF | Validação de URLs, allowlists de destinos |

---

### Linux — Referência Rápida

```bash
# Navegação
pwd && ls -la          # onde estou e o que tem aqui
find / -name "*.conf"  # buscar arquivos
grep -r "texto" ./     # buscar conteúdo

# Permissões
chmod 755 script.sh    # rwxr-xr-x
chown user:group file  # mudar dono

# Processos e Rede
ps aux | grep python   # processos rodando
ss -tuln               # portas abertas
htop                   # monitor interativo
```

---

### Prompt Engineering — Template de Alta Performance

```
PAPEL: Você é um engenheiro de software sênior com experiência em [ÁREA].
CONTEXTO: Estou no nível [NÍVEL] estudando [TEMA].
TAREFA: [descrição clara e específica]
RESTRIÇÕES: [o que não deve ser incluído]
FORMATO: Markdown — H2 para títulos, negrito para termos, código em blocos.
```

Técnicas por ordem de complexidade:

```
Zero-Shot   → pergunta direta, sem exemplos
One-Shot    → 1 exemplo antes da pergunta
Few-Shot    → 2–5 exemplos contextualizados
CoT         → "pense passo a passo antes de responder"
ReAct       → raciocínio + ação intercalados
```

---

## Glossário Técnico

| Termo | Definição | Área |
|-------|-----------|------|
| **Algoritmo** | Sequência finita de passos para resolver um problema | Fundamentos |
| **Big O Notation** | Notação que descreve a complexidade de um algoritmo no pior caso | Algoritmos |
| **API** | Contrato de comunicação entre sistemas | Arquitetura |
| **Clean Code** | Práticas para escrever código legível e manutenível | Engenharia |
| **CVE** | Identificador padrão de vulnerabilidades conhecidas | Segurança |
| **Design Pattern** | Solução reutilizável para problemas recorrentes de design | Arquitetura |
| **Few-Shot Prompting** | Técnica que usa exemplos para guiar a resposta do modelo | Prompt Engineering |
| **Hash Table** | Estrutura que mapeia chaves a valores com acesso O(1) | Estruturas de Dados |
| **LLM** | Modelo de IA treinado em grandes volumes de texto | IA |
| **OWASP** | Organização global de referência em segurança de aplicações | Segurança |
| **SOLID** | Cinco princípios de design orientado a objetos | Engenharia |
| **SSRF** | Vulnerabilidade que força o servidor a fazer requisições internas | Segurança |
| **Token** | Unidade básica processada por LLMs — subpalavra, palavra ou símbolo | IA |
| **Zero-Shot Prompting** | Pergunta direta ao modelo sem exemplos prévios | Prompt Engineering |

---

## Reflexões Finais

Antes deste projeto, eu usava IAs de forma bem ingênua — digitava uma pergunta, lia a resposta, passava para a próxima. Funcionava, mas eu não estava extraindo nem metade do potencial.

O que mudou foi entender que **o modelo responde ao que você pergunta, não ao que você quer**. Isso parece óbvio escrito assim, mas na prática faz toda a diferença. Um prompt mal formulado não vai gerar uma resposta ruim só por má vontade do modelo — ele vai gerar a melhor resposta possível para uma pergunta vaga. O problema está na pergunta.

O maior risco que identifiquei foi a **ilusão de aprendizado**: ler um resumo gerado pela IA e sentir que você domina o assunto. É uma armadilha real. O material gerado pelo NotebookLM foi útil como ponto de partida, mas o aprendizado de fato aconteceu quando eu fui verificar as fontes originais, escrever exemplos por conta própria e tentar explicar os conceitos sem olhar para o notebook.

> *"A IA é como um GPS. Ela te diz a rota mais rápida — mas não dirige por você. E se você não aprender a ler o mapa, vai ficar perdido quando o sinal cair."*

O que o NotebookLM faz muito bem é **síntese entre fontes**. Conectar o livro de algoritmos da UFPR com um documento do OWASP e um paper de LLM numa resposta coerente é algo que eu levaria horas fazendo manualmente. Para isso, a ferramenta é genuinamente poderosa.

---

## Estrutura do Repositório

```
segundo-cerebro-dev/
│
├── README.md
├── prompts/
│   └── prompts-reutilizaveis.md
└── recursos/
    └── fontes.md
```

---

## Referências

- Python Software Foundation — https://docs.python.org
- Ubuntu Documentation — https://ubuntu.com/docs
- Kali Linux Documentation — https://www.kali.org/docs
- Castilho, M. *Algoritmos e Estrutura de Dados 1* — UFPR — https://www.inf.ufpr.br/marcos/livro_alg1/livro_alg1.pdf
- Bhargava, A. Y. *Entendendo Algoritmos* — Novatec, 2017
- OWASP Top 10:2025 — https://owasp.org/Top10
- OWASP API Security Top 10 — https://owasp.org/www-project-api-security
- OWASP Top 10 for LLM Applications — https://owasp.org/www-project-top-10-for-large-language-model-applications
- DeepSeek AI. *DeepSeek-V3 Technical Report* — https://arxiv.org/pdf/2412.19437
- Zero To Mastery. *Linux Commands Cheat Sheet* — https://zerotomastery.io/cheatsheets/linux-commands-cheat-sheet
- Alura. *Princípios SOLID na POO* — https://www.alura.com.br
- NotebookLM — https://notebooklm.google.com
- DIO — https://dio.me

---

<div align="center">

Feito por [kskios](https://github.com/kskios) · Projeto DIO

</div>
