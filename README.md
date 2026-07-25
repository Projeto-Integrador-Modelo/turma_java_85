# 🚀 Nossa Turma

Este projeto é uma atividade prática para aprender e praticar o fluxo de colaboração utilizando **Git e GitHub**.

Cada aluno deverá adicionar seu próprio perfil à página da turma através de um **Fork** e uma **Pull Request**.

------

## 🎯 Objetivo

Praticar o fluxo completo de contribuição em um projeto colaborativo:

```text
Fork
  ↓
Clone
  ↓
Branch
  ↓
Alteração
  ↓
Commit
  ↓
Push
  ↓
Pull Request
  ↓
Code Review
  ↓
Approve / Request Changes
  ↓
Merge
```

------

## 📁 Estrutura do projeto

```text
nossa-turma/
│
├── index.html
├── styles.css
├── README.md
│
└── images/
    └── aluno-exemplo.jpg
```

------

# 👨‍💻 Atividade

Cada aluno deverá adicionar seu próprio perfil à página.

O perfil deverá conter:

- Foto;
- Nome;
- Uma breve descrição.

Exemplo:

```html
<article class="student-card">

    <img
        src="https://ik.imagekit.io/vzr6ryejm/usuarios/02.jpg"
        alt="Foto do Aluno Exemplo"
    >

    <div class="student-info">

        <h3>Aluno Exemplo</h3>

        <p>
            Desenvolvedor Full Stack em formação
        </p>

    </div>

</article>
```

------

# 🔀 Passo 1 — Fazer o Fork

Acesse o repositório original da turma.

Clique em:

```text
Fork
```

Crie uma cópia do projeto na sua conta do GitHub.

------

# 💻 Passo 2 — Clonar seu Fork

Copie a URL do seu repositório e execute:

```bash
git clone URL_DO_SEU_FORK
```

Entre na pasta:

```bash
cd nossa-turma
```

------

# 🌿 Passo 3 — Criar uma Branch

Crie uma branch para sua contribuição.

Exemplo:

```bash
git checkout -b feature/adicionar-seu_nome
```

------

# 📂 Passo 4 — Abrir o arquivo index.html

Abra o arquivo abaixo com o Visual Studio Code:

```text
index.html
```

------

# 📝 Passo 5 — Adicionar seu Card

Adicione seu card dentro de:

```html
<div class="student-grid">
```

Exemplo:

```html
<article class="student-card">

    <img
        src="https://ik.imagekit.io/vzr6ryejm/usuarios/02.jpg"
        alt="Foto de Seu Nome"
	>

    <div class="student-info">

        <h3>Aluno Exemplo</h3>

        <p>
            Desenvolvedor Full Stack em formação
        </p>

    </div>

</article>
```

------

# 💾 Passo 6 — Verificar as Alterações

Execute:

```bash
git status
```

Verifique os arquivos alterados.

------

# 📦 Passo 7 — Criar o Commit

Adicione os arquivos:

```bash
git add .
```

Crie o commit:

```bash
git commit -m "feat: adiciona perfil de Seu Nome"
```

Substitua "Seu Nome" pelo seu nome.

------

# ☁️ Passo 8 — Enviar para o GitHub

Envie sua branch:

```bash
git push origin feature/adicionar-seu_nome
```

"feature/adicionar-seu_nome" é o nome da sua branch.

------

# 🔃 Passo 9 — Criar a Pull Request

Acesse seu Fork no GitHub.

O GitHub deverá mostrar a opção:

```text
Compare & pull request
```

Clique nela.

A Pull Request deverá ser direcionada para:

```text
Repositório original
        ↓
Branch main
```

Adicione um comentário e Crie a PR

---

# 👀 Passo 10 — Code Review

Outro aluno deverá revisar sua Pull Request.

O revisor deverá verificar:

-  O nome foi adicionado?
-  A foto foi adicionada?
-  O caminho da imagem está correto?
-  O atributo `alt` foi informado?
-  A descrição foi adicionada?
-  O HTML está organizado?
-  A página continua funcionando?

O revisor poderá:

### 💬 Comment

Fazer um comentário ou sugestão.

### 🔄 Request Changes

Solicitar alterações.

------

# 🔧 Passo 11 — Corrigir a Pull Request

Caso o revisor solicite alterações, faça a correção na mesma branch.

Depois:

```bash
git add .
git commit -m "fix: corrige perfil do aluno"
git push origin feature/adicionar-rafael
```

A Pull Request será atualizada automaticamente.

------

# 🎉 Resultado

Após a aprovação, a contribuição poderá ser integrada ao projeto principal.

Ao final da atividade, teremos uma página com todos os participantes da turma.

```text
Nossa Turma

┌────────┐ ┌────────┐ ┌────────┐
│ Foto   │ │ Foto   │ │ Foto   │
│ Ana    │ │ João   │ │ Maria  │
└────────┘ └────────┘ └────────┘

┌────────┐ ┌────────┐ ┌────────┐
│ Foto   │ │ Foto   │ │ Foto   │
│ Pedro  │ │ Lucas  │ │ Rafael │
└────────┘ └────────┘ └────────┘

             ...

          38 alunos
```

------

## 🏆 Desafio final

Todos os alunos deverão:

- Fazer **1 Fork**;
- Criar **1 Branch**;
- Fazer **1 Commit**;
- Abrir **1 Pull Request**;
- Realizar **1 Code Review**;
- Ter sua contribuição integrada ao projeto.

O objetivo é que todos pratiquem o ciclo completo de colaboração com Git e GitHub.
