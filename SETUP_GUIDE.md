# 🚀 Guia de Ativação do seu GitHub Profile README

Este repositório contém a sua apresentação profissional de alto impacto para o GitHub, configurada especificamente para o perfil **AI FullStack & Integration Developer**.

---

## 📌 Passo 1: Criar o Repositório Especial no GitHub

Para que o GitHub reconheça este README como o seu perfil oficial:

1. Acesse: [https://github.com/new](https://github.com/new)
2. No campo **Repository name**, digite **exatamente o seu nome de usuário do GitHub** (ex: se seu usuário for `jonasmaia`, o nome do repo deve ser `jonasmaia`).
3. Uma mensagem especial aparecerá: *"You found a secret! `<username>/<username>` is a special repository that you can use to add a README.md to your GitHub profile."*
4. Marque o repositório como **Public** (Público).
5. Deixe desmarcadas as opções de inicialização (README, .gitignore, licença), pois já temos tudo pronto localmente.
6. Clique em **Create repository**.

---

## 📌 Passo 2: Publicar os Arquivos Locais para o GitHub

No terminal (dentro da pasta `github-profile`):

```bash
git init
git add .
git commit -m "feat: initial github profile readme and snake action"
git branch -M main
git remote add origin https://github.com/<SEU-USUARIO>/<SEU-USUARIO>.git
git push -u origin main
```

*(Substitua `<SEU-USUARIO>` pelo seu username real do GitHub)*.

---

## 📌 Passo 3: Ativar Permissões do GitHub Actions para a Cobrinha (Snake)

Para que a animação da cobrinha seja gerada e enviada automaticamente para o branch `output`:

1. No seu repositório no GitHub, vá em **Settings** > **Actions** > **General**.
2. Na seção **Workflow permissions** (ao final da página), selecione:
   - ✅ **Read and write permissions**
3. Clique em **Save**.
4. Para testar imediatamente sem esperar a meia-noite:
   - Vá na aba **Actions** no topo do seu repositório.
   - Clique em **Generate Contribution Snake** na lateral esquerda.
   - Clique no botão **Run workflow** > **Run workflow**.

---

## ⚙️ Personalizações Rápidas (Opcional)

No arquivo `README.md`, verifique se deseja ajustar:
- **Links Sociais**: Atualize o link do seu LinkedIn e GitHub se o handle for diferente.
- **Username dos Cards**: Se o seu username no GitHub for diferente de `jonasmaia` (ex: `jonasmaia-newtour`), faça um Replace rápido de `jonasmaia` para o seu username no `README.md`.
