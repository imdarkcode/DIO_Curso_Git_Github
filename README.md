# DIO | Curso de Git e Github

Repositório para armazenar os comandos de Git e Github do curso de Versionamento de Código com Git e Github da [DIO](https://www.dio.).

## 📚 Documentação

- [Documentação Git](https://git-scm.com/doc)
- [Documentação Github](https://docs.github.com/pt)

## 🖥️ Comandos

**Configurar usuário e email**

    git config --global user.name <nome>
    git config --global user.email <email>

**Mostrar versão do git**

    git --version

**Inicializar um repositório**

    git init

**Clonar repositório remoto**

    git clone <URL> <nome_da_pasta> --branch <nome_da_branch> --single-branch

**Adicionar repositório remoto**

    git remote add origin <URL>

**Mostrar repositório remoto**

    git remote -v

**Mostrar status do repositório**

    git status

**Adicionar arquivo a área de preparação**

    git add <arquivo>

**Remover arquivo da área de preparação**

    git reset <arquivo>

**Adicionar um commit**

    git commit -m "<titulo_do_commit>" -m "<descrição_do_commit>"

**Mostrar árvore de commits**

    git log

**Mostrar árvore de commits detalhada**

    git reflog

**Adicionar arquivo ao .gitignore**

    echo <arquivo> > .gitignore

**Restaurar as alterações feitas no arquivo**

    git restore <arquivo>

**Mudar o texto do último commit**

    git commit --amend -m "<titulo_do_commit>" -m "<descrição_do_commit>"

**Abrir editor de texto o último commit**

    git commit --amend

**Voltar para um commit anterior**

    git reset <codigo_do_commit_que_deseja_voltar>

**Voltar para um commit anterior e apagar alterações de commits posteriores**

    git reset --hard <codigo_do_commit_que_deseja_voltar>

**Renomear o nome da branch**

    git branch -M main

**Enviar alterações para o repositório remoto**

    git push -u origin <nome_da_branch>

**Enviar alterações para o repositório remoto sobrescrevendo o histórico de commits**

    git push --force-with-lease origin <nome_da_branch>

**Baixar alterações para o repositório local**

    git pull

**Criar uma branch no repositório**

    git checkout -b <nome_da_branch>

**Trocar de branch no repositório**

    git checkout <nome_da_branch>

**Listar branchs do repositório**

    git branch

**Listar o último commit de cada branch**

    git branch -v

**Mesclar branch com outra**

    git merge <nome_da_branch>

**Apagar branch**

    git branch -d <nome_da_branch>

**Baixar alterações para o repositório local sem mesclar com a branch padrão**

    git fetch origin <nome_da_branch>

**Arquivar alterações**

    git stash

**Mostrar lista de alterações arquivadas**

    git stash list

**Aplicar alterações arquivadas**

    git stash pop

## ⌨️ Convenção de Commits

| Tipo | Descrição |
| ---- | ---- |
| `feat` | Adicionar nova funcionalidade ao projeto |
| `fix` | Corrigir um bug ou problema no projeto |
| `docs` | Alterar a documentação do projeto |
| `style` | Aplicar mudanças na aparência sem afetar a funcionalidade |
| `refactor` | Aplicar mudanças no código sem afetar a funcionalidade |
| `test` | Adicionar ou alterar testes no projeto |  