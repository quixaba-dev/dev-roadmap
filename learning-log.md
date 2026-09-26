# Learning log · Diário de estudos

Os registros com data preservam o que foi anotado na época. A seção de agosto–setembro resume um período sem entradas regulares; não atribui datas específicas a atividades individuais.

## 21/07/2026

O fim da procrastinação e começo de uma nova era mental e estudantil.

- Organizei meu roadmap.
- Criei meu repositório.
- Defini minhas metas.
- Registrei meu projeto Maestre.

## 22–30/07/2026

- Aprendi FastAPI.
- Compreendi a importância da arquitetura e escalabilidade.
- Comecei os estudos de SQL.
- Entendi a importância do Docker para deploy de aplicações em nuvem, VPS e outros dispositivos.
- Registrei meu projeto DataCenter AI.

## Agosto–setembro de 2026 · resumo retrospectivo

Este resumo recompõe aproximadamente os dois meses sem atualizações do diário. Ele registra áreas de prática e evolução informadas, não uma sequência cronológica exata nem domínio completo.

### Python, backend e AsyncIO

- Python passou de scripts e fundamentos para aplicações mais completas, organizadas em módulos e classes, com responsabilidades separadas, configuração por variáveis de ambiente, tratamento de erros e integração com serviços externos.
- Aumentou a prática com `async def`, `await`, AsyncIO, callbacks assíncronos e clientes HTTP/API assíncronos, incluindo `AsyncOpenAI` e fluxos de bots/agentes.
- Comecei a identificar o impacto de operações bloqueantes em event loops e a distinguir fluxos síncronos e assíncronos.
- FastAPI avançou para endpoints, request/response, `Depends`, organização de backend e sessões de banco associadas a requests. Autenticação e armazenamento seguro de credenciais seguem em consolidação.

### Persistência e dados

- SQL avançou de primeiros estudos para uso de SQLAlchemy 2.x: models com `Mapped`/`mapped_column`, chaves, tipos e constraints.
- Pratiquei sessions, `select`, `execute`, `scalars`, `first`, `one_or_none`, `add`, `commit` e `refresh`, operações CRUD e integração da persistência com APIs.
- Bancos de dados continuam em consolidação; o uso de ORM representa uma etapa de evolução, não domínio completo de SQL.

### Git, arquitetura e qualidade operacional

- Passei a dar mais atenção ao staging, branches, tracking remoto, `fetch`, `pull`, `push`, merge, rebase, resolução de conflitos, `.gitignore` e comparação de histórico local/remoto.
- Comecei a estruturar commits atômicos com Conventional Commits e escopo/intenção claros, respeitando dependências entre mudanças.
- Passei a aplicar modularização, separação de responsabilidades e desacoplamento entre interfaces, infraestrutura, domínio e implementações. O DataCenter AI ajudou a pensar em uma arquitetura que pode receber novas fontes de contexto, ferramentas, interfaces e providers.
- Comecei a substituir `print()` por logging com configuração centralizada, `logging.getLogger(__name__)` e níveis DEBUG, INFO, WARNING e ERROR.

### LLM Application Development

- Os experimentos evoluíram de chamadas simples a APIs para fluxos com agentes, fontes de contexto, retrieval e ferramentas.
- Pratiquei APIs de LLM e APIs compatíveis com OpenAI, incluindo Groq; RAG, embeddings com Sentence Transformers (`all-MiniLM-L6-v2`), semantic search e FAISS.
- Trabalhei com preparação de documentos, busca vetorial/top-k, context injection, Tool Calling, schemas e roteamento de tools.
- Comecei a inspecionar o contexto recuperado e a avaliar manualmente respostas e comportamento do agente.
- O `evals/manual_eval.py` do DataCenter AI é uma ferramenta de avaliação exploratória/manual, não uma suíte de testes automatizados.

### Networking e sistemas embarcados · experiência complementar

- Experimentei ESP32 com MicroPython, Wi-Fi, DNS, sockets TCP, TLS/SSL, HTTP/HTTPS, JSON e pequenos servidores HTTP.
- Investiguei a comunicação com uma API externa em hardware limitado e depurei as etapas separadamente: DNS → TCP → TLS → HTTP → API.
- Essa prática aproximou o uso de APIs dos fundamentos de rede que ficam por trás de clientes de alto nível. Embedded permanece complementar ao foco em backend.

### Web

- HTML, CSS e JavaScript continuam presentes nos estudos e na criação de interfaces. O período recente concentrou-se mais fortemente em backend Python e arquitetura.

## Próxima entrada

Registrar aprendizados novos com datas quando disponíveis, incluindo problemas encontrados, decisões de arquitetura e o que mudou após depuração/refatoração.
