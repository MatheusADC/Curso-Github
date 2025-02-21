# <img src="https://github.com/user-attachments/assets/0d980e6c-97de-4add-98c3-7197095c5080" alt="Ícone do Github" width="28px"/> Git e Github
- O Git é um Sistema de Versionamento;
- O GitHub é uma das plataformas de versionamento mais utilizadas;
- [Site](https://github.com/)
- [Meu Github](https://github.com/MatheusADC)

# <img src="https://github.com/user-attachments/assets/6b2d218f-a095-4e4f-ab4a-586cf55c83e6" alt="Ícone de aprovação" width="28px"/> Vantagens
- Controle das versões do código;
- Trabalho colaborativo.

# <img src="https://github.com/user-attachments/assets/5c05dd2d-e256-4439-8bf1-f04e7ca0e9c7" alt="Ícone do Git" width="28px"/> Instalação do Git
- [Site](https://git-scm.com/)

# <img src="https://github.com/user-attachments/assets/4c8b7f6e-06df-4945-bfcc-bdd5c84864b0" alt="Ícone de verificação" width="28px"/> Verificação do _status_ da instalação
```
git --help ou git --version
```

# <sub><img src="https://github.com/user-attachments/assets/63b6ebba-d37d-4a91-ad27-0738c4896197" alt="Ícone do terminal" width="35"></sub> Comandos
### Inicialização do repositório
```
git init
```

### Verificação do status do repositório
```
git status
```

<p></p>

> [!IMPORTANT]  
> Um _Commit_ é uma operação que registra as modificações feitas em um repositório de versionamento.
> 
> Arquivos marcados como _untracked_ não foram adicionados ao controle de versão.

<br/>

### Adição do arquivo ao controle de versão
```
git add <nome_arquivo.extensao>
```

### Adição dos arquivos de forma concomitante (alteração do status do arquivo de _untracked_ para _modified_)
```
git add .
```

### Realização de um _commit_
```
git commit -m <mensagem>
```

### Configuração do usuário do GitHub localmente
```
git config --global user.name <username>
git config --global user.email "<e-mail>
```

### Envio do código para o _cloud server_ 
```
git push --set-upstream origin <nome_branch>
```

### Adição local da _branch_ remota
```
git remote add origin <URL_Projeto>
```

### Verificação do histórico das versões
```
git reflog
```

<p></p>

> [!CAUTION]
> A versão mais atual é a que está localizada no topo do texto de retorno.

<br/>

### Retorno da versão
```
git reset --hard <ID_commit>
```

### Verificação das _branches_ disponíveis localmente
```
git branch
```

### Criação da _branch_ local
```
git branch <nome_branch>
```

### Exclusão da _branch_
```
git checkout <nome_branch_de_destino>
```

### Exclusão da  _branch_ localmente
```
git branch -D <nome_branch>
````

### Atualização da _branch_ local
```
git pull <nome_branch>
```

### Criação de uma _branch_ a partir de outra _branch_
```
git checkout -b <nome_branch_criada> <nome_branch_modelo>
```

### Criação do arquivo .gitignore
```
touch .gitignore
```

# <img src="https://github.com/user-attachments/assets/1c0af4ea-f9be-431c-a40a-5c8992e95f92" alt="ícone de merge" width="28px"/> União do código
### 1. Entre na branch que receberá o _merge_
### 2. Execute o comando `git pull`
### 3. Execute o comando `git merge <nome_branch_principal>`
### 4. Execute o comando `git push`

# <img src="https://github.com/user-attachments/assets/976f38b1-e242-4943-985c-0fd45f59df28" alt="ícone de barnches" width="28px"/> _Branches_
São ramificações distintas que podem são criadas ao longo do processo de desenvolvimento.

# <img src="https://github.com/user-attachments/assets/b5a735cd-9d37-4773-adc4-583b76a65dc4" alt="ícone de pull request" width="28px"/> _Pull request_ 
É a solicitação da aprovação de um _commit_.

# <img src="https://github.com/user-attachments/assets/6dff2470-e8c7-4ec5-8ba1-c7ddf6042cab" alt="ícone de git ignore" width="28px"/> _Gitignore_
A sua função é evitar o envio de determinados arquivos ou pastas para o repositório.
