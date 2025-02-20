# <img src="https://github.com/user-attachments/assets/0d980e6c-97de-4add-98c3-7197095c5080" alt="Ícone do Github" width="28px"/> Git e Github
- O Git é o Sistema de versionamento do código.
- O GitHub é a plataforma de versionamento mais utilizada.
- [Site](https://github.com/)
- [Meu Github](https://github.com/MatheusADC)

# <img src="https://github.com/user-attachments/assets/6b2d218f-a095-4e4f-ab4a-586cf55c83e6" alt="Ícone de aprovação" width="28px"/> Vantagens
- Controle das versões do código;
- Trabalho em equipe.

# <img src="https://github.com/user-attachments/assets/5c05dd2d-e256-4439-8bf1-f04e7ca0e9c7" alt="Ícone do Git" width="28px"/> Instalação do Git
- [Site](https://git-scm.com/)

# <img src="https://github.com/user-attachments/assets/4c8b7f6e-06df-4945-bfcc-bdd5c84864b0" alt="Ícone de verificação" width="28px"/> Verificar se a instalação foi bem sucedida
```
git --help ou git --version
```

# <sub><img src="https://github.com/user-attachments/assets/63b6ebba-d37d-4a91-ad27-0738c4896197" alt="Ícone do terminal" width="35"></sub> Comandos
### Inicializar novo repositório
```
git init
```

### Verificar o status do repositório
```
git status
```

<br>

> [!IMPORTANT]  
> _Commits_ são versões são código.
> 
> Arquivos marcados como _untracked_ não foram adicionados no controle de versão.

<p></p>

### Adicionar arquivo no controle de versão
```
git add "nome arquivo.extensao"
```

### Adicionar todos os arquivos concomitantemente (status do arquivo passa de _untracked_ para _modified_)
```
git add .
```

### Realizar um commit:
```
git commit -m "O que foi feito naquela versão"
```

### Configurar o seu usuário do GitHub localmente
```
git config --global user.name "seu_usuario_do_github" 
git config --global user.email "seu_email_no_github"
```

### Enviar o código para os servidores na nuvem
```
git push --set-upstream origin <nome_branch>
```

### Adicionar branch remota localmente (no seu computador) para definir para onde o código será enviado
```
git remote add origin <URL_Projeto>
```

### Verificar histórico das versões (versão mais atual é a do topo)
```
git reflog
```

### Retornar a versão
```
git reset --hard <id_commit>
```

### Verificar quais branches estão disponíveis localmente
```
git branch
```

### Criar a branch localmente
```
git branch <nome_branch>
```

### Mudar de branch
```
git checkout <nome_branch_de_destino>
```

### Apagar branch localmente
```
git branch -D <nome_branch>
````

### Atualizar branch localmente
```
git pull <nome_branch>
```

### Criar uma branch a partir de outra
```
git checkout -b <nome_branch_será_criada> <nome_branch_modelo>
```

### Criar arquivo .gitignore
```
touch .gitignore
```

# <img src="https://github.com/user-attachments/assets/1c0af4ea-f9be-431c-a40a-5c8992e95f92" alt="ícone de merge" width="28px"/> Unir código
### 1. Entre na branch que irá receber o merge
### 2. git pull
### 3. git merge <nome_branch_de_onde_virá_informacao>
### 4. git push

# <img src="https://github.com/user-attachments/assets/976f38b1-e242-4943-985c-0fd45f59df28" alt="ícone de barnches" width="28px"/> Branch
São caminhos diferentes que serão seguidos durante o processo de desenvolvimento.

# <img src="https://github.com/user-attachments/assets/b5a735cd-9d37-4773-adc4-583b76a65dc4" alt="ícone de pull request" width="28px"/> Pull request 
É a solicitação da aprovação de um commit.

# <img src="https://github.com/user-attachments/assets/6dff2470-e8c7-4ec5-8ba1-c7ddf6042cab" alt="ícone de git ignore" width="28px"/> Gitignore
A sua função é para não enviar determinados arquivos/pastas.
