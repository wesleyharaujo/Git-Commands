# GIT COMANDOS

- **git status** -> Exibe status
- **git branch** -> Exibir branchs
- **git log** -> Exibir commits
- **$ git log --oneline** -> Exibir commits de forma mais sismples e reduzida
- **git log -p** -> Exibir commits com as modificações realizadas
- **https://devhints.io/git-log** -> Link log cheatsheets

---

## --- USERS CONFIG
- **git config --local user.{propriedade}** -> Exibir o valor dapropriedade do usuario local
- **git config --local user.{propriedade} "Valor"** -> Mudar config local usuario

---

## COMMITS COMANDS

- **git add .** -> Adiciona todos os arquivos da pasta na visao do git para commits
- **git add "nome.tipo"** -> Adiciona o arquivo na visao do git para commits
- **git commit -m "NOME DO COMMIT"** -> Faz um commit para branch master( -m )

---

## --- SERVER ---

- **git init --bare** -> criar repositorio "puro" que pode ser usado como servidor
- **git remote** -> exibe lista servidores vinculados
- **git remote -v** -> exibe os para qual serão enviados e recebidos dados
- **git remote add NOME_SERVIDOR CAMINHO** -> add um vinculo entre o git local e um server

---

## --- CLONE REPOSITORIO --- 

- **git clone {caminho} projeto** -> clona um repositorio dentro de uma nova pasta chamada projeto(Nome que vc escolheu)
- **git push {nome repo} {branch}** -> envia os dados do seu repositorio para o server
- **git remote rename {nome repo} {novo nome repo}** -> Renomear um vinculo com o server


