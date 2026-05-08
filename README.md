# Engenharia de Agentes Corporativos com IA
### FIAP — Módulos I e II

> Repositório centralizado com todos os materiais interativos desenvolvidos ao longo do curso de pós-graduação em Engenharia de Agentes Corporativos com IA da FIAP.

---

## Sobre o Curso

O curso aborda a construção de agentes de IA de nível corporativo utilizando as principais ferramentas e frameworks do ecossistema moderno: **Google ADK**, **LangGraph**, **Vertex AI** e a **API Claude**. Com carga horária de **129 horas distribuídas em 43 sessões**, os módulos cobrem desde fundamentos de token economics até arquiteturas avançadas com memória, RAG, busca híbrida e comunicação entre agentes (A2A).

---

## Navegação

Abra o arquivo [`index.html`](./index.html) no navegador para acessar o **hub centralizado** com todos os materiais organizados por módulo, descrições e busca integrada.

---

## Estrutura dos Materiais

### Plano de Aula
| Arquivo | Descrição |
|---|---|
| `00-agentes-avancados-de-ia-programa.html` | Programa completo do curso |
| `01-ecossistema-adk-economia-tokens.html` | Aula 1 — ADK e economia de tokens |
| `lab-calculadora-custos.html` | Lab interativo: calculadora de custos de LLM |
| `setup-guide.html` | Guia de setup do ambiente de desenvolvimento |

### Content Library
| Arquivo | Descrição |
|---|---|
| `index-content-library-2026-02-01.html` | Dashboard master do curso (129 h · 43 sessões) |
| `01-langgraph.html` | Módulo 2 — Introdução ao LangGraph |

### Agente 1 — The Governance Gateway
| Arquivo | Descrição |
|---|---|
| `index-agente-1-governance-gateway-2026-02-09.html` | Gateway de governança corporativa |
| `agente-1-governance-gateway--setup.html` | Setup e configuração |
| `index-agente-1-mock-2026-02-09.html` | Versão mock para testes |
| `agente-1-mock--setup.html` | Setup da versão mock |

### Agente 3 — The Memory
| Arquivo | Descrição |
|---|---|
| `index-agente-3-the-memory-2026-02-20.html` | Arquitetura de memória de longo prazo |
| `rag.html` | RAG — Retrieval-Augmented Generation |
| `agente-3-memory--rag_II.html` | RAG avançado com visualizações (Plotly.js) |
| `hybrid_search.html` | Busca híbrida: BM25 + Reciprocal Rank Fusion |
| `index-agente-3-memory-v1-2026-02-20.html` | Versão v1 (histórico) |
| `agente-3-memory-v1--setup.html` | Setup v1 |
| `modulo1-agente-3--setup.html` | Setup — Módulo 1, Aula 4 |

### Agente 4 — RAG ADK & Vector Search
| Arquivo | Descrição |
|---|---|
| `index-agente-4-rag-adk-2026-02-27.html` | RAG com Agent Development Kit |
| `index-4-agents-rag-vertex-2026-02-27.html` | 4 agentes integrados ao Vertex AI |
| `vector-search.html` | Lab: métricas de distância vetorial (L1, L2, Cosine, Dot Product) |
| `rag-vertex--rag_II.html` | RAG II no contexto Vertex AI |

### Agente 6 — LangGraph ADK
| Arquivo | Descrição |
|---|---|
| `index-agente-6-langgraph-adk-2026-04-17.html` | LangGraph ADK — v1 |
| `index-agentes-6-langgraph-adk-2026-04-24.html` | LangGraph ADK — v2 |
| `2026-02-01--modelo.html` | Modelo de arquitetura — v1 |
| `2026-04-24--modelo.html` | Modelo completo: topologias, HIL, time travel (674 KB) |
| `aula-a2a.html` | Comunicação Agent-to-Agent (A2A) |
| `2026-04-17--claude_code.html` | Integração com Claude Code — v1 |
| `2026-04-24--claude_code.html` | Integração com Claude Code — v2 |
| `2026-04-24--matriz-priorizacao-roi-ia.html` | Matriz de priorização ROI em IA — v1 |
| `2026-05-01--matriz-priorizacao-roi-ia.html` | Matriz de priorização ROI em IA — v2 |
| `arquitetura-visao-macro-projetos-ia.html` | Arquitetura macro de projetos de IA |

---

## Convenção de Nomenclatura

Todos os arquivos que originalmente se chamavam `index.html` foram renomeados seguindo o padrão:

```
index-[contexto]-[YYYY-MM-DD].html
```

Arquivos com nomes duplicados entre módulos distintos recebem prefixo de data ou contexto para evitar ambiguidade e preservar o histórico de versões.

---

## Stack Tecnológica dos Materiais

| Tecnologia | Uso |
|---|---|
| **Tailwind CSS** | Estilização e layout responsivo |
| **Chart.js** | Gráficos interativos de barras, radar e dispersão |
| **Plotly.js** | Visualizações avançadas de embeddings e chunks |
| **JavaScript** | Interatividade, cálculos em tempo real e navegação |
| **HTML5 / CSS3** | Estrutura base de todos os materiais |

---

## Como usar localmente

Não há dependências de servidor. Basta clonar e abrir no navegador:

```bash
git clone https://github.com/glauciodaniel/agentes-avancados-ia-mod-I-II.git
cd agentes-avancados-ia-mod-I-II
# abra o index.html no navegador de sua preferência
```

---

## Período do Curso

```
Fevereiro 2026 → Maio 2026
```

---

*FIAP — Pós-Graduação em Engenharia de Agentes Corporativos com IA*
