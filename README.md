<div align="center">

# 🧭 Developer Roadmap

### Backend Python · Systems · LLM Applications

**Bernardo Gomes Quixaba Silva**

Um registro prático de evolução: aprender construindo, depurando e reorganizando sistemas reais.

<img src="https://img.shields.io/badge/Python-backend-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python backend">
<img src="https://img.shields.io/badge/AsyncIO-in%20practice-4B8BBE?style=for-the-badge" alt="AsyncIO em prática">
<img src="https://img.shields.io/badge/LLM-RAG%20%26%20agents-6C5CE7?style=for-the-badge" alt="LLM, RAG e agentes">
<img src="https://img.shields.io/badge/Git-workflow-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git workflow">

</div>

<br>

## Sobre este roadmap

Este repositório acompanha minha evolução como desenvolvedor, com foco crescente em **backend Python, arquitetura modular e aplicações com LLMs**. As categorias abaixo indicam prática atual e próximos passos — aparecer em um projeto significa experiência, não domínio automático.

| ⚙️ Backend | 🧠 LLM Engineering | 🏗️ Sistemas |
| --- | --- | --- |
| Python, APIs e AsyncIO | Agents, RAG e Tool Calling | Modularização e separação de responsabilidades |
| FastAPI e SQLAlchemy em prática | Embeddings, FAISS e semantic search | Git com histórico intencional e commits claros |

## Da primeira etapa ao trabalho com sistemas

```text
Julho · fundamentos e exploração
Python  →  primeiros passos com FastAPI e SQL  →  arquitetura e Docker em estudo
                                      │
                                      ▼
Agosto–setembro · aplicação prática
APIs + AsyncIO + ORM  →  módulos e integrações  →  agentes com RAG e tools
```

No começo, o foco era consolidar Python e conhecer backend, bancos, arquitetura e deploy. Nos meses seguintes, esses assuntos passaram a aparecer juntos em aplicações: fluxos assíncronos, persistência, integrações externas, retrieval e ferramentas conectadas a agentes.

## Onde estou agora

| Uso com frequência | Consolidando | Explorando / próximos passos |
| --- | --- | --- |
| Python, AsyncIO, Git/GitHub | FastAPI, SQL e SQLAlchemy 2.x | Docker aplicado a deploy e operação |
| APIs e integrações externas | Arquitetura, segurança e observabilidade | Redis, AWS e C# |
| Modularização, logging | RAG, retrieval e avaliação de agentes | Fundamentos mais profundos de networking |

**Experiência complementar:** HTML, CSS e JavaScript seguem no repertório de estudo; MicroPython/ESP32 trouxe prática pontual com Wi-Fi, DNS, TCP, TLS e HTTP. Docker foi estudado e experimentado, mas ainda não é parte central da prática recorrente.

## Projeto em destaque · DataCenter AI

Um agente extensível organizado em torno de uma interface, um agente, recuperação de contexto e chamada de ferramentas. Discord, Groq, FAISS/Sentence Transformers, Sherlock/Holehe e os dados presentes em `data/` são implementações ou integrações atuais; cada componente pode evoluir sem redefinir o propósito do sistema.

```text
Interfaces → Agent ─┬─ RAG → Context Sources
                    └─ Tool Caller → Tools
```

## 🧭 Explore

- [Projetos](projects.md) — propósito, arquitetura e estado conhecido dos projetos.
- [Learning log](learning-log.md) — registros datados e resumo do período sem anotações.
- [Goals](goals.md) — prática atual, conhecimentos em consolidação e próximos passos.

<div align="center">

<sub>O objetivo é sair de “sei usar uma ferramenta” para entender como os componentes se conectam e como manter o sistema evolutivo.</sub>

</div>
