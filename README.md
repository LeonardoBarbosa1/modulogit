Meu sistema no git

## comandos git:

### Configurações:<br/>
    1. Comando para colocar seu nome: sudo git config --global user.name "Seu Nome"
    2. Comando para colocar seu Email: sudo git config --global user.email "Seu Email"
    3. Comando para colocar seu Editor de texto: sudo git config --global core.editor Seu-editor-ex:vscode

Comando para fazer a listagem da configuração: sudo git config --list

Comando para inicializar o git: sudo git init

comando para para saber o status do git: sudo git status

Comando para adicionar as altereções: sudo git add nome-do-arquivo

comando commit: sudo git commit -m "Comentário sobre a alteração"

comando para adicionar as alterações e ao mesmo tempo commitar: sudo git commit -am "Comentário sobre a alteração"

comando para saber de todas as alterações: sudo git log

comando para saber a branch que a gente está: sudo git branch

comando para voltar ao commit desejado ignorando totalmente oque foi feito no novo commit: sudo git reset --hard id-commit-que-deseja-voltar

comando para voltar ao commit desejado tendo acesso a oque foi modificado no novo commit(obs: é o mais recomendado quando está trabalhando em equipe)
        sudo git reset --soft id-commit-que-deseja-voltar

comando para criar um novo branch: sudo git branch nome-branch

comando para mudar para outra branch: sudo git checkout nome-da-branch

comando para saber oque foi alterado em cada arquivo com detalhes: sudo git diff

comando para saber o nome dos arquivos que foram modificados: sudo git diff --name-only

comando para saber as alterações apenas de um arquivo: sudo git diff nome-do-arquivo

comando para enviar os conteúdos locais para o remoto: git push -u origin master

comando para não pedir id do token: git config --global credential.helper cache

comando para adicionar o repositório remoto ao seu repositório local: git remote set-url origin https://seu-token@github.com/seu-nome/nome-do-repositorio

caso seu arquivo esteja protegido e você não esteja conseguindo salvar as alterações use esse comando: sudo chmod -R 777 /nome/da/pasta


