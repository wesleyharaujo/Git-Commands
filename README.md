# GIT COMANDOS

## --- BASICS

- **git init** -> cria um novo repositorio
- **git status** -> Exibe status
- **git log** -> Exibir commits
- **git log --oneline** -> Exibir commits de forma mais sismples e reduzida
- **git log -p** -> Exibir commits com as modificações realizadas
- **git log --graph**  -> Exibir log com grafico de branches
- **https://devhints.io/git-log** -> Link log cheatsheets

---

## --- USERS CONFIG
- **git config --local user.{propriedade}** -> Exibir o valor dapropriedade do usuario local
- **git config --local user.{propriedade} "Valor"** -> Mudar config local usuario

---

## --- BRANCHES

- **git branch** -> Exibir branches
- **git branch {nome}** -> Cria uma nova branches com o nome indicado
- **git checkout {branch}** -> Muda para a branch escolhida 
- **git branch -d {branch}** -> remover uma branch

---

## CTRL-Z

- **git checkout -- {arquivos}** -> Desfazer mudanças que ainda não foram add para commit
- **git reset HEAD** -> Desfazer mudanças que ja foram add
- **git revert {hash}** -> Desfazer commit

- **git stash** -> Salva temporariamente um trabalho sem realizar um log
- **git stash list** -> Lista os stash 
- **git stash pop {numero stash}** -> Lista os stash 

- **git checkout {commit hash}** -> Usado para voltar o estado do codigo para o commit escolhido ( E possivel criar uma nova branch para criar uma nova linhqa de trabalho )]

---

## --- COMMITS COMANDS

- **git add .** -> Adiciona todos os arquivos da pasta na visao do git para commits
- **git add {arquivo.extensão}** -> Adiciona o arquivo na visao do git para commits
- **git commit -{branch} "{NOME DO COMMIT}"** -> Faz um commit
- **git merge {branch}** -> Junta duas branches ( para salvar no VIM use :X)
- **git rebase {branch}** -> Puxa os commits da branch escolhida para atual logo antes do seu ultimo commit

---

## --- REPOSITORIO CONFIG ---

- **git init --bare** -> Criar repositorio "puro" que pode ser usado como servidor
- **git remote add NOME_SERVIDOR CAMINHO** -> Add um vinculo entre o git local e um server
- **git remote rename {nome repo} {novo nome repo}** -> Renomear um vinculo com o server
- **git remote** -> Exibir lista de servidores vinculados
- **git remote -v** -> Exibir para os servidores vinculados e seus caminhos

---

## --- REPOSITORIO PUSH/PULL DADOS --- 

- **git clone {caminho} {nome novo repositorio}** -> Clona um repositorio dentro de uma nova pasta com o nome que vc escolheu
- **git push {nome repo} {branch}** -> Envia os dados para o repositorio
- **git pull {repositorio} {branch}** -> Puxa dados do repositorio 
