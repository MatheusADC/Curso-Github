# <img src="https://github.com/user-attachments/assets/0d980e6c-97de-4add-98c3-7197095c5080" alt="ícone do Github" width="28px"/> Git e Github
- O Git é o Sistema de versionamento do código.
- O GitHub é a plataforma de versionamento mais utilizada.

# <img src="https://github.com/user-attachments/assets/026e6e5d-91fc-4a25-a763-1fc1609c724a" alt="ícone de aprovação" width="28px"/> Vantagens
- Controle das versões do código;
- Trabalho em equipe.

# <img src="https://github.com/user-attachments/assets/51054956-9a97-47e8-b1a6-9b25b0a9eb22" alt="ícone do Git" width="28px"/> Instalação do Git
- [Site](https://git-scm.com/)

# <img src="https://github.com/user-attachments/assets/8170d1f4-0d04-4bf4-8a72-fdc19f96fa08" alt="ícone de verificação" width="28px"/> Verificar se a instalação foi bem sucedida
```
git --help ou git --version
```

# <img src="https://github.com/user-attachments/assets/41411c36-f0eb-4f6d-b546-3f69740b7343" alt="ícone do Github" width="28px"/> Site do GitHub
- [Site](https://github.com/)

- [Meu Github](https://github.com/MatheusADC)

# <img src="https://github.com/user-attachments/assets/d7224906-8501-4478-b29c-5e21c1eaad4e" alt="ícone de terminal" width="28px"/> Comandos
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

# <img src="https://github.com/user-attachments/assets/7611d8bf-04cc-4d65-80b5-d283c483a251" alt="ícone de merge" width="28px"/> Unir código
### 1. Entre na branch que irá receber o merge
### 2. git pull
### 3. git merge <nome_branch_de_onde_virá_informacao>
### 4. git push

# <img src="https://github.com/user-attachments/assets/a3ae838d-dd8e-493f-8df3-991e867cd3be" alt="ícone de barnches" width="28px"/> Branch
São caminhos diferentes que serão seguidos durante o processo de desenvolvimento.

# <img src="https://github.com/user-attachments/assets/d5427377-11a1-47fd-bc2c-23b211ad3e8a" alt="ícone de pull request" width="28px"/> Pull request 
É a solicitação da aprovação de um commit.

# <img src="https://github.com/user-attachments/assets/6dff2470-e8c7-4ec5-8ba1-c7ddf6042cab" alt="ícone de git ignore" width="28px"/> Gitignore
A sua função é para não enviar determinados arquivos/pastas.
