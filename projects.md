# Projects · Projetos

As descrições abaixo combinam os registros históricos deste roadmap com o contexto de evolução fornecido para agosto–setembro de 2026. O código-fonte dos projetos não está incluído neste repositório; portanto, detalhes de implementação não citados aqui não foram inferidos.

## DataCenter AI

**Propósito:** arquitetura extensível de agente de IA capaz de combinar fontes externas de contexto por RAG com ferramentas que ampliam as capacidades do modelo.

```text
Interfaces
    │
    ▼
  Agent
   ├── RAG ─────────► Context Sources
   └── Tool Caller ─► Tools
```

Essa separação mantém o propósito do sistema independente dos componentes conectados no momento:

| Componente | Implementação atual informada |
| --- | --- |
| Interface | Discord |
| Provider de modelo | Groq |
| Retrieval vetorial | Sentence Transformers e FAISS |
| Ferramentas | Sherlock e Holehe |
| Fontes de contexto | Dados específicos presentes em `data/`, incluindo conteúdo de Blox Fruits |

Esses elementos são substituíveis: conteúdo de Blox Fruits é uma fonte possível, Sherlock/Holehe são tools, Discord é uma interface e Groq é um provider. Nenhum deles, isoladamente, define o projeto.

**Áreas de aprendizagem associadas:** agentes, RAG, embeddings, semantic search, Tool Calling, arquitetura modular, AsyncIO, logging e avaliação exploratória.

**Avaliação:** há um `evals/manual_eval.py` para avaliação manual/exploratória de prompts, respostas, contexto recuperado e métricas. Isso não deve ser apresentado como cobertura automatizada de testes.

## Maestre

**Descrição registrada:** orquestrador de agentes de IA que transforma um plano principal em tarefas e encaminha cada tarefa ao subagente correspondente.

**Tecnologias registradas originalmente:** Python, OpenAI e JSON.

**Pendências registradas originalmente:** corrigir bugs, melhorar o formato JSON usado na comunicação entre agentes e adicionar validação ao orquestrador.

Estas informações vêm do registro de julho. Não há código do Maestre neste repositório para confirmar seu estado atual ou acrescentar detalhes de implementação.

## Registrar projetos

Ao adicionar ou revisar um projeto, documentar o propósito antes das tecnologias; distinguir implementação atual de arquitetura; registrar o que foi realmente usado, o que está em avaliação e limitações conhecidas.
