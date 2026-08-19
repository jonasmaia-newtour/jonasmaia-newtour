# Spec de Redesign do Perfil GitHub - Jonas Maia

**Data:** 2026-08-19  
**Status:** Proposto  

---

## 1. Visão Geral
Refatorar e aprimorar o perfil do GitHub (README.md) para destacar uma presença profissional de alto nível com foco em Engenharia de Software, Clean Architecture, Front-End moderno e Sistemas Escaláveis com Inteligência Artificial.

---

## 2. Mudanças e Estrutura do README.md

### 2.1. Header & Apresentação
- **Banner SVG Moderno / Dark Tech**: Cabeçalho visual integrado com gradiente escuro/neon, livre de instabilidades de servidores de terceiros.
- **Typing Animation**: Frases alinhadas com Engenharia de Software, FullStack e Sistemas Inteligentes.
- **Remoção de Redes Sociais**: Remoção da seção de badges de LinkedIn/Email/GitHub conforme solicitado.

### 2.2. Sobre Mim (Foco em Arquitetura & Engenharia)
- **Pilares**:
  - 🏗️ **Arquitetura & Clean Code**: Desenvolvimento orientado a boas práticas, desacoplamento, performance e manutenibilidade.
  - 🎨 **Front-End Moderno**: Criação de interfaces responsivas, acessíveis e de alta performance utilizando React, Next.js e TypeScript.
  - ⚡ **FullStack & Integrações**: APIs robustas, microsserviços e integração fluida entre camadas de backend e front-end.
  - 🤖 **Ecossistema de IA**: Implementação de workflows inteligentes, agentes e integração de modelos LLMs em sistemas corporativos.

### 2.3. Arsenal Tecnológico (com Toggles / Accordions details)
Agrupamento expansível destacando apenas as tecnologias consagradas e essenciais da área e de Front-End:
- **Front-End Core & UI**: React, Next.js, TypeScript, JavaScript, Tailwind CSS, HTML5, CSS3, Vite.
- **Backend, APIs & Runtime**: Node.js, Python, FastAPI, Express, GraphQL, REST APIs.
- **Inteligência Artificial & Agentes**: OpenAI API, Anthropic Claude, Google Gemini, LangChain, Ollama.
- **Dados, Cloud & Ferramentas**: PostgreSQL, Redis, Supabase, Docker, Git, GitHub Actions.

### 2.4. Estatísticas do GitHub & Snake
- **GitHub Stats & Top Languages**: Cards ajustados com o tema tokyonight, cores customizadas e URLs otimizadas.
- **Streak Stats**: Card de sequência de contribuições alinhado ao mesmo tema.
- **Histórico de Contribuições (Snake)**: Mantida a animação do jogo da cobrinha integrado ao workflow do GitHub Actions.

---

## 3. Limpeza de Arquivos
- Exclusão do arquivo SETUP_GUIDE.md.

---

## 4. Validação
- Verificação da renderização correta de markdown, toggles de detalhes e imagens.
- Confirmação de que não restaram links quebrados ou referências residuais.
