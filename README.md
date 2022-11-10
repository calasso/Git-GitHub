## :octocat: Git & GitHub 


### Guia com seleção de comandos para o dia-a-dia com Git e GitHub

<hr>

### :mega: Comandos exporádicos

$`git config --global user.email {"email@gmail.com"}` Configurar o e-mail que será apresentado nos commits

$`git config --global user.name {Nome}` Configurar o nome que será apresentado nos commits

$`git config –list`  Para listar as configurações do git

$`git config --global --unset user.name`  Para limpar o nome inserido anteriormente

$`git init`  Iniciar o repositório)

$`git clone {caminho/do/repositório}`  Para clonar repositórios 

$`git remote add origin {https://github.com/usuario/repositorio.git}`  Adicionando a “origin” que é um apelido apra a URL

$`git remote -v`  Lista de repositórios remotos

$`git fetch` Pusa para o repositorio local todas as branch que esta no repositorio do github

<hr>

### :mega: Comandos do dia-a-dia

$`git restore –staged {NOME-DO-ARQUIVO.TX}T`  Serve para remover algo que foi usado no $git add

$`git status` Verifica em quais arquivos voce mexeu e podem ser commitados 

$`git add` Adciona um elemento para ser commitado

$`git add .{extensão}` Adciona todos arquivos com aquela extensão podendo variar de acordo com a extensão que voce queira

$`git add .` ou `git add *` Adciona todos arquivos para commit ignorando os arquivos que esta no git ignore

$`git reset {NOME_DO_ARQUIVO}` Remove arquivo

$`git commit -m "descrição do que fez aqui"` Adciona as mudanças no repositorio local

$`git push origin main`  “push” envia os commits para a “main / master”, sobe o seu repositorio local para o repositorio

$`git pull` Atualiza seu repositorio local com o que esta na branch que esta trabalhando

$`git pull origin {NomeBranch}`Atualiza seu repositorio com a branch que de sua escolha

$`git checkout {NomeBranch}` Muda de branch

$`git checkout -b {NomeBranch}` Cria uma branch no repositorio local

$`git checkout -- .` Remove todos arquivos editados para não serem adcionado ao commit

$`git merge` Junta duas ou mais branchs (Tem que estar na branch que quer que seja atualizada, no caso de conflito, normalmente as IDEs ajudam a resolver)

$`git stash` Caso tenha feito na branch errada ele consegue pegar tudo que fez e salvar no seu repositorio local para voce transferir para branch correta

$`git stash apply` Pega os dados que foi salvo com stash e adciona na branch de sua escolha // se fez o commit não tem como fazer o stash

$`git clean -df` Remove todos untracked files

$`git branch -D {NOME-DA-BRANCH}`  Remover btanch, o "-D" força a remoção
