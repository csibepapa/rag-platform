# rag-platform
Modular, plugin-driven RAG platform for building knowledge-injected AI workflows.
## Architecture

[CLI] → [CORE] ← [PLUGINS]
          ↑
       [ADMIN]
## Components
- [rag-core](https://github.com/csibepapa/rag-core) → engine
- [rag-cli](https://github.com/csibepapa/rag-cli) → execution
- [rag-admin](https://github.com/csibepapa/rag-admin) → management
- [rag-plugins-for-rag-core](https://github.com/csibepapa/rag-plugins-for-rag-core) → extensions
