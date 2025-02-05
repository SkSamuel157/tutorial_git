# git & GitHub 

##  Guia
1.  [Como criar uma conta no Github](#como-criar-uma-conta-no-github)
2.  [Como Usar o GitHub com o Git](#como-usar-o-github-com-o-git)
3.  [Comandos Básicos do Git](#como-criar-uma-conta-no-github)



---
## Como criar uma conta no Github

1. Acesse o site [https://github.com/](https://github.com/).  
2. Clique em **"Fazer login"** no canto superior direito.  
3. Preencha as informações solicitadas:
   - **Nome de Usuário**: nome de usuário.  
   - **Email**: seu e-mail.  
   - **Senha**: crie uma senha.  
4. Clique em **"Criar Conta"**.  
5. Confirme seu e-mail através do link enviado para seu Gmail.  

---
## Como Usar o GitHub com o Git

1. Crie um repositório no GitHub:

Clique em "New repository".

Dê um nome ao repositório e clique em "Create repository".



2. No terminal, conecte o repositório local ao remoto:

git remote add origin https://github.com/seu-usuario/nome-do-repo.git
git push -u origin main


3. Para futuras alterações:

git add .
git commit -m "Descrição da alteração"
git push




---
## Comandos Básicos do Git

- Inicializar um Repositório
```sh

git init

```
---

- Clonar um Repositório Existente
```sh

git clone https://github.com/usuario/repo.git

```
Faz o download de um repositório remoto para o seu computador.
---

- Verificar o Status dos Arquivos
```sh

git status

```
Mostra alterações no diretório de trabalho.
---

- Adicionar Arquivos para o Commit
```sh

git add nome-do-arquivo

```
- Ou para adicionar todos os arquivos modificados:
```sh

git add

```
---

- Fazer um Commit
```sh

git commit -m "Mensagem descritiva sobre a alteração"

```
---

- Conectar a um Repositório Remoto
```sh

git remote add origin https://github.com/usuario/repo.git

```
---

- Enviar Alterações para o GitHub
```sh
git push -u origin main

```
---

- Baixar Alterações do Repositório Remoto
```sh
git pull origin main

```
---
