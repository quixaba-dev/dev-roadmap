# Goals · Objetivos

Este roadmap separa prática recorrente de assuntos que ainda estão amadurecendo. Um tópico não é considerado concluído só por ter aparecido em um projeto.

## Conhecimentos utilizados com frequência

- **Python para aplicações backend:** organização modular, classes, separação de responsabilidades, configuração por ambiente, tratamento de erros e integrações externas.
- **AsyncIO:** `async`/`await`, callbacks assíncronos e clientes de API em fluxos assíncronos; atenção a operações bloqueantes dentro do event loop.
- **Git/GitHub:** staging, branches, tracking remoto, fetch/pull/push, merge/rebase, conflitos e commits com intenção clara, incluindo Conventional Commits.
- **Práticas de estruturação:** módulos por responsabilidade, logging com `logging.getLogger(__name__)` e configuração compartilhada.

## Conhecimentos em consolidação

- **FastAPI e backend web:** endpoints, request/response, `Depends`, sessões por request, autenticação e persistência. Há experiência prática, com fundamentos ainda em aprofundamento.
- **SQL e SQLAlchemy 2.x:** models tipados (`Mapped`, `mapped_column`), constraints, sessions, consultas com `select`/`execute`/`scalars`, operações CRUD e integração com APIs.
- **Arquitetura:** limites entre interface, domínio, infraestrutura e implementações; desacoplamento e extensibilidade validados pela construção de projetos.
- **Aplicações de LLM:** APIs compatíveis, agentes, RAG, embeddings, semantic search, FAISS, top-k retrieval, context injection e Tool Calling.
- **Logging e avaliação:** níveis e diagnóstico por módulo; avaliação manual/exploratória de contexto e comportamento de agentes, sem confundir isso com testes automatizados.
- **Segurança e configuração:** variáveis de ambiente, credenciais e integração com serviços externos, com aprofundamento ainda necessário.

## Próximos passos

- Aprofundar SQL: joins, transações, índices, migrações e consultas eficientes.
- Melhorar desenho e confiabilidade de APIs: validação, autenticação/autorização, testes automatizados e gestão de erros.
- Explorar concorrência, cancelamento, timeouts e isolamento de operações bloqueantes em aplicações assíncronas.
- Tornar avaliação de RAG/agentes mais sistemática, mantendo avaliações manuais distintas de testes automatizados.
- Evoluir observabilidade com logs úteis e diagnóstico consistente entre API, retrieval e tools.
- Consolidar Docker por meio de uso aplicado em desenvolvimento e deploy.
- Continuar fundamentos de HTML, CSS e JavaScript sem deslocar o foco principal de backend.

## Objetivos de longo prazo

- **Redis**, **AWS** e **C#** continuam como objetivos futuros do plano original; não representam experiência prática recorrente registrada aqui.
- Aprofundar arquitetura e escalabilidade a partir das necessidades concretas dos sistemas construídos.
- Compreender melhor networking e operação de serviços, levando adiante a experiência complementar com ESP32/MicroPython.

## Evolução desde o início

| Registro inicial · julho de 2026 | Estado atual · resumo de agosto–setembro de 2026 |
| --- | --- |
| Consolidar Python e começar FastAPI/SQL | Construir aplicações Python modulares com APIs, AsyncIO e persistência ORM |
| Estudar arquitetura, escalabilidade e Docker | Aplicar separação de responsabilidades e extensibilidade em projetos; Docker segue secundário |
| Explorar chamadas simples a APIs de LLM | Montar fluxos com agente, RAG, busca vetorial e Tool Calling |
| Git ainda como ferramenta de publicação | Usar branches, staging e histórico com commits intencionais |

Consulte o [learning log](learning-log.md) para a cronologia preservada e [projects](projects.md) para o contexto das aplicações.
