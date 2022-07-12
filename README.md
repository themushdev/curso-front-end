cd# Curso Front-end
# EBAC

# GIT
- Conceitos de versionamento
- Histórico
- Controle de versão
- Quem alterou
- O quê alterou
- Quando alterou
- Todos os arquivos
- Evolução contínua

# Instalação do Git
https://git-scm.com/

# Clonar o projeto
git clone https://github.com/cavalcantemmarcelo/curso-frontend.git

# Commits
Informação de alteração

- após testado todo seu código
- git add * 
- git commit -m "mensagem" 
- git push (enviar alterações para o repositório GitHub) 
- git pull (puxar / trazer alterações do GitHub para sua máquina)

# GitFlow
Fluxo do Git

# Branchs
são ramificações / versões paralelas

- main / master (vai para produção, quando o projeto é publicado)
- develop
- DOD Definition of Done: critérios de aceite
- versionamento 1.0.0
- git checkout -b dev (cria uma branch) 
- git checkout master/main (mudar de branch)

# Merge
- checar se houve alteração na Main antes de subir o código com: git fetch --all

Mescla de branchs Você pode precisar resolver conflitos manualmente

git merge main

# Pull Requests
Mescla de branchs no repositório Permite code review O respositório resolve os conflitos automaticamente

configura o GitFlow
git flow init git flow feature start {nome-da-feature}
