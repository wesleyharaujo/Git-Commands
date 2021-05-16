# GIT COMANDOS

## --- BASICS

- **git init** -> cria um novo repositorio
- **git status** -> Exibe status
- **git log** -> Exibir commits
- **$ git log --oneline** -> Exibir commits de forma mais sismples e reduzida
- **git log -p** -> Exibir commits com as modificações realizadas
- **https://devhints.io/git-log** -> Link log cheatsheets

---

## --- USERS CONFIG
- **git config --local user.{propriedade}** -> Exibir o valor dapropriedade do usuario local
- **git config --local user.{propriedade} "Valor"** -> Mudar config local usuario

---

## --- BRANCHES

- **git branch** -> Exibir branches
- **git branch {nome}** -> Cria uma nova branches com o nome indicado
- **git branch checkout {branch}** -> Muda para a branch escolhida 


---

## --- COMMITS COMANDS

- **git add .** -> Adiciona todos os arquivos da pasta na visao do git para commits
- **git add {arquivo.extensão}** -> Adiciona o arquivo na visao do git para commits
- **git commit -{branch} "{NOME DO COMMIT}"** -> Faz um commit
- **git merge {branch}** -> Junta duas branches ( para salvar no VIM use :X)
- **git rebase {branch}** -> Puxa os commits da branch escolhida para atual logo antes do seu ultimo commit

---

## --- SERVER CONFIG ---

- **git init --bare** -> Criar repositorio "puro" que pode ser usado como servidor
- **git remote add NOME_SERVIDOR CAMINHO** -> Add um vinculo entre o git local e um server
- **git remote rename {nome repo} {novo nome repo}** -> Renomear um vinculo com o server
- **git remote** -> Exibir lista de servidores vinculados
- **git remote -v** -> Exibir para os servidores vinculados e seus caminhos

---

## --- SERVER PUSH/PULL DADOS --- 

- **git clone {caminho} {nome novo repositorio}** -> Clona um repositorio dentro de uma nova pasta com o nome que vc escolheu
- **git push {nome repo} {branch}** -> envia os dados do seu repositorio para o server
