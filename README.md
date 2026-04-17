# Git-Flow - Testes

## Comandos Branches

### Criar branch
git branch nome-da-branch

### Trocar de branch
git checkout nome-da-branch

### Criar e trocar ao mesmo tempo
git ckeckout -b nome-da-branch

### Listar branches
git branch

### Envio de branches
git push origon nome-da-branch

---

## Comandos básicos do GIT:

### Clonar repositório
git clone <colocar o endereço único>

### Ver status
git status

### Adicionar arquivos
git add .

git add nome-do-arquivo

### Criar commit
git commit -m "mensagem"

### Enviar para o GitHub
git push origin main

### Atualizar repositório
git pull origin main

---

## Correções de commits

### Alterar último commit
git commit --amend

### Desfazer commit (mantendo alterações)
git reset --soft HEAD~1

### Desfazer commit (apagar tudo)
git reset --hard HEAD~1
