# GitHub Profile Redesign Implementation Plan

> **For agentic workers:** REQUIRED SUB-SKILL: Use superpowers:subagent-driven-development (recommended) or superpowers:executing-plans to implement this plan task-by-task. Steps use checkbox (- [ ]) syntax for tracking.

**Goal:** Reestruturar completamente o perfil GitHub (README.md) de Jonas Maia com um visual moderno Dark Tech, bio com foco em Engenharia/Arquitetura/IA, arsenal tecnológico interativo em toggles com a stack selecionada (Front-End, Backend, IA, DevOps/DB), estatísticas corrigidas e remoção do SETUP_GUIDE.md.

**Architecture:** README estruturado em Markdown com componentes HTML semânticos (<details>, <summary>, <div>, <img>), banner SVG moderno embutido e cards de estatísticas estáveis.

**Tech Stack:** Markdown, SVG, GitHub Shields/Badges, GitHub Stats APIs.

## Global Constraints

- User profile: Jonas Maia (jonasmaia-newtour)
- Remover links de redes sociais (LinkedIn, Email, GitHub badges antigos)
- Remover arquivo SETUP_GUIDE.md
- Arsenal tecnológico agrupado em <details><summary> com apenas as tecnologias escolhidas pelo usuário
- Tema consistente Dark TokyoNight / Slate & Neon

---

### Task 1: Remover SETUP_GUIDE.md

**Files:**
- Delete: SETUP_GUIDE.md

- [ ] **Step 1: Remover o arquivo SETUP_GUIDE.md**
- [ ] **Step 2: Verificar remoção via git status**
- [ ] **Step 3: Commit da remoção**

`ash
git rm SETUP_GUIDE.md
git commit -m "chore: remove SETUP_GUIDE.md"
`

---

### Task 2: Criar Banner SVG Dark Tech Customizado

**Files:**
- Create: ssets/header-banner.svg

**Interfaces:**
- Produces: SVG visualmente atraente e responsivo com tipografia moderna, gradientes slate/cyan/indigo e badge de foco.

- [ ] **Step 1: Criar diretório assets e arquivo header-banner.svg**
- [ ] **Step 2: Verificar integridade do arquivo SVG**
- [ ] **Step 3: Commit do banner**

`ash
git add assets/header-banner.svg
git commit -m "feat(assets): add modern dark tech header banner svg"
`

---

### Task 3: Atualizar README.md com Novo Layout, Bio, Toggles e Estatísticas

**Files:**
- Modify: README.md

**Interfaces:**
- Produces: README.md completo, limpo, sem redes sociais, com bio orientada a arquitetura/IA, toggles de tecnologias e cards funcionais de estatísticas.

- [ ] **Step 1: Escrever nova estrutura completa do README.md**
- [ ] **Step 2: Validar links, badges e tags de fechamento de details/summary**
- [ ] **Step 3: Commit do README.md**

`ash
git add README.md
git commit -m "feat: overhaul README with architecture bio, tech toggles, and fixed stats"
`

---

### Task 4: Verificação e Validação Final

**Files:**
- Verify: README.md, ssets/header-banner.svg

- [ ] **Step 1: Validar sintaxe Markdown e ausência de links quebrados**
- [ ] **Step 2: Validar git status limpo**
