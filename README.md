<div align="center">

# Filipe Matunaga

**Engenharia de Software · UFG · 3º período**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/filipe-matunaga-a3bab9362/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Matunag)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:filipecampos.fcmb@gmail.com)

</div>

---

## 👤 Sobre mim

Estudante de Engenharia de Software na Universidade Federal de Goiás, com foco em desenvolvimento backend, agentes de IA e pesquisa aplicada. Atualmente pesquisador no **CEIA – UFG**, onde trabalho com benchmarks de ferramentas de IA e construção de agentes baseados em LLMs.

Busco crescer em ambientes que desafiem minhas habilidades técnicas e me permitam contribuir de forma significativa com projetos reais.

---

## 🛠️ Stack & Habilidades

### Linguagens
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![HTML](https://img.shields.io/badge/HTML-E34F26?style=flat-square&logo=html5&logoColor=white)

### Ferramentas & Tecnologias
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=figma&logoColor=white)
![N8N](https://img.shields.io/badge/N8N-EA4B71?style=flat-square&logo=n8n&logoColor=white)

### IA & LLMs
- Técnicas: **ReAct**, **RAG**, **orquestração de agentes**, **engenharia de prompt**
- Frameworks: **Google ADK**
- Benchmarks de ferramentas open-source

### Arquitetura & Metodologias
- Padrão **MVC**
- Boas práticas de desenvolvimento de software
- Revisão sistemática de literatura e estudos terciários

---

## 🚀 Projetos

> Adicione seus projetos abaixo seguindo o template!

---

### 📌 [Projeto Integrador 1º semestre](https://github.com/Brettas2602/Projeto-Integrador-2025-1)

**Descrição:** Sistema web especializado em auxiliar profissionais de saúde e pacientes na identificação e tratamento de câncer de colo de útero. Desenvolvido em equipe como projeto integrador da turma de Engenharia de Software 2025/1.

**Habilidades utilizadas:**

![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![HTML](https://img.shields.io/badge/HTML-E34F26?style=flat-square&logo=html5&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=figma&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)

| Aspecto | Detalhe |
|---|---|
| Linguagem principal | JavaScript |
| Linguagens auxiliares | HTML, CSS |
| Framework frontend | Next.js |
| Estilização | Tailwind CSS |
| Prototipagem | Figma |
| Versionamento | GitHub (branches + Pull Requests) |
| Trabalho em equipe | 5 integrantes, contribuições via fork/PR |

---

### 📌 [RAG Elétric](https://github.com/h3it-dias/Rag_Eletric)

**Descrição:** Sistema de RAG (Retrieval-Augmented Generation) para consulta inteligente de atos normativos da ANEEL. Realiza ETL dos dados, enriquecimento automático de ementas ausentes via LLM, indexação vetorial/híbrida e expõe uma API REST para consultas em linguagem natural. Cobre o acervo dos anos 2016, 2021 e 2022.

**Habilidades utilizadas:**

![Python](https://img.shields.io/badge/Python_3.13-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Google Cloud](https://img.shields.io/badge/Vertex_AI-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=flat-square&logo=qdrant&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)

| Aspecto | Detalhe |
|---|---|
| Linguagem principal | Python 3.13 |
| API | FastAPI + Uvicorn |
| Técnicas de IA | RAG híbrido (dense + sparse + ColBERT), engenharia de prompt |
| Agente | Google ADK + Gemini 2.5 Flash via Vertex AI |
| Banco vetorial | Qdrant Cloud |
| Embeddings | `multilingual-e5-large`, `BM25`, `ColBERTv2` (FastEmbed) |
| ETL | Selenium + ChromeDriver, PyMuPDF, Groq (geração de ementas) |
| Infraestrutura | Docker, Google Cloud VM, Uvicorn |
| Versionamento | GitHub |

---

### 📌 [RAG Elétric — Arquitetura de Agentes](https://github.com/h3it-dias/Rag_Eletric)

> Detalhamento da arquitetura multi-agente implementada no projeto RAG Elétric.

O sistema utiliza um **pipeline de 4 agentes especializados** orquestrados via Google ADK, cada um com responsabilidade isolada:

| Agente | Responsabilidade |
|---|---|
| `orquestrador_aneel` | Ponto de entrada; decide entre responder diretamente ou acionar o pipeline RAG |
| `query_agent` | Reformula a query do usuário, extrai filtros (ano, sigla, situação) e gera variantes para multi-query retrieval |
| `retrieval_agent` | Executa a busca híbrida no Qdrant usando a query expandida e retorna os documentos candidatos |
| `grader_agent` | Avalia a relevância de cada documento com score 0–1; aprova acima de 0.45 ou aplica fallback com os 2 melhores |
| `answer_agent` | Sintetiza a resposta final citando sigla, número, data e situação de cada ato normativo aprovado |

**Busca híbrida em 3 estágios (Prefetch → Re-ranking):**

```
Query do usuário
      ↓
[dense: multilingual-e5-large]  →  top-20 candidatos
[sparse: BM25]                  →  top-20 candidatos
      ↓
[ColBERTv2 — late interaction]  →  top-5 re-rankeados por token
```

**Habilidades utilizadas:**

![Python](https://img.shields.io/badge/Python_3.13-3776AB?style=flat-square&logo=python&logoColor=white)
![Google Cloud](https://img.shields.io/badge/Vertex_AI-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=flat-square&logo=qdrant&logoColor=white)

| Aspecto | Detalhe |
|---|---|
| Linguagem | Python 3.13 |
| Padrão arquitetural | Multi-agent pipeline (orquestração sequencial com estado compartilhado) |
| Framework de agentes | Google ADK (`LlmAgent`, `sub_agents`, `output_key`) |
| Modelo LLM | Gemini 2.5 Flash via Vertex AI |
| Banco vetorial | Qdrant Cloud — coleção `hybrid_search` |
| Embeddings dense | `intfloat/multilingual-e5-large` (1024 dims, multilingual) |
| Embeddings sparse | `Qdrant/BM25` (evolução do TF-IDF, vetores esparsos) |
| Re-ranking | `colbert-ir/ColBERTv2.0` (late interaction, token-by-token) |
| Validação de dados | Pydantic (`BaseModel` + `Field` em todos os agentes) |
| Engenharia de prompt | Instruções por agente com chain-of-thought e regras estritas de saída |

---

## 📊 GitHub Stats

<div align="center">

![Filipe's GitHub Stats](https://github-readme-stats.vercel.app/api?username=Matunag&show_icons=true&theme=dark&hide_border=true&bg_color=0d1117&title_color=00ADD8&icon_color=00ADD8)

![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=Matunag&layout=compact&theme=dark&hide_border=true&bg_color=0d1117&title_color=00ADD8)

</div>

---

## 🎓 Experiência

**Pesquisador** · CEIA – UFG *(Goiânia, GO)*
- Revisão sistemática da literatura e estudos terciários
- Benchmarks de ferramentas de IA, com foco em soluções open-source
- Construção de agentes baseados em LLMs com Google ADK

**Auxiliar Educacional** · Escola Shallon *(Goiânia, GO · 03/2025 – 04/2026)*
- Aplicação de provas e simulados
- Aulas extras de olimpíadas de matemática (OBMEP, Canguru, OMEG) e ciências (ONC, OBA)

---

## 🌐 Idiomas

- 🇧🇷 Português — nativo
- 🇺🇸 Inglês — avançado (C1)

---

<div align="center">
  <sub>📍 Goiânia, GO · filipecampos.fcmb@gmail.com</sub>
</div>
