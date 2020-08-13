# Revião

## Fluxo Git

### Subindo repositório local no github ( usado no exercício da semana )
  * o git ainda não conhece essa pasta. Por isso precisamos do ```git init```.
  * Com o git inicializado ainda precisamos conecta-lo com um repositório remoto. Por isso criamos o repo no github.
  * Adicionar o remote ````git remote add origin url-que-voces-copiaram-do-github````
  * Se o repositório remoto que estamos conectando tiver sido inicializado com o readme, ou tiver qualquer outro arquivo nele: precisamos dar um git pull origin master.
  com isso pegamos o que tem na nuvem e teremos nossa branch master local atualizada.

### Trabalhando num projeto que já está no github
  * Nesse caso fazemos o ```git clone url-do-projeto```
  * não precisamos do git init
  * não precisamos setar o remote origin
  * Podemos apenas criar nossa branch a partir da master e seguir trabalhando.

## Comandos Git
  __git init__
  * diz para o git olhar para a pasta que estamos.
  * Esse comando não é necessário quando clonamos um projeto da nuvem. Pois o git já está inicializado.
  * Muita atenção na pasta que estamos ao executar esse comando. Não queremos inicializar o nosso Desktop, por exemplo.

  __git remote__
  *  ````git remote add origin url-que-voces-copiaram-do-github```` - conectamos nosso projeto com um repo remoto
  * ops! adicionamos a url errada, queremos muda-la? basta usar o comando ```git remote set-url origin nova-url-do-repo```
  * ````git remote -v ```` - para checar de onde estamos pegando (pull/fetch) e pra onde estamos mandando nosso codigo(push)

## Terminal (git bash)

Os comandos do terminal são independentes do git

### Comandos mais usados:
* Aqui vai ter conflito
* ls - list (lista todos os arquivos presentes no diretório MAC/LINUX)
* dir - list(Windows)
* dir /b - mostra lista de maneira simplificada
* pwd - Present working directory (MAC/LINUX) - __mostra a pasta que estamos__
* cd ~ - volta para a raiz
* cd .. - volta uma pasta
* cd nome-da-pasta - para entrar em uma pasta
* code . - abre o visual studio code na pasta local.
* mkdir nome-da-pasta - para criar uma pasta
* touch nome-do-arquivo - para criar um arquivo
* rm nome-do-arquivo - para remover um arquivo
* history - mostra histórico de comandos
* f7 - history no Windows
