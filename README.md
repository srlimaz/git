# GIT

_**Perceba que aqui não há todos os comandos e o que tem, pode faltar alguma explicação, pois o documento em si irá crescer junto com meu conhecimento, o intuito aqui é documentar a progressão do meu saber, e após finalizado ter um documento explicativo sobre o GIT.**_

Estudando o GIT, percebi uma certa dificuldade comigo mesmo em pegar todos os termos e comandos logo de inicio, por isso criei esse arquivo ao decorrer dos cursos e pesquisas sobre o mesmo. Por ser um pouco complicado inicialmente lembrar de todos os comandos, saber oque cada um faz e as sequencias certas para chama-lós, esse arquivo irá auxiliar o aprendizado.

**Adendo**

_Para usar qualquer comando, será necessário usar na frente o "git", pois é ele que informa ao terminal que você está usando comandos do git. Todos os comandos abaixo serão apresentados sem o "git" no começo, pois interpreto que você está ciente que sem ele no começo de cada comando nada funciona._

## Comandos:

**INIT**

É usado para criar um novo repositório git, esse é o comando principal para iniciar um repositório, sem 'chamar' ele no inicio do projeto você não irá conseguir fazer os demais comandos. (_Só é necessário chama-lo no inicio de cada novo repositório git._)

**ADD**

Adiciona arquivo ao 'staging', (staging é o lugar onde o arquivo vai ficar antes dele ser enviado ao repositorio local.) 

- [.] é usado para adicionar todos os arquivos onde o bash foi chamado ou onde ele estiver no momento.

**COMMIT**

Adiciona arquivo para o repositório local do git, saindo de 'staging'. 

- **-m:**  serve para inserir um comentário ao commit. (obrigatório)

Digitando dentro do commit, você pode usar 'Ref #<num>' para referenciar um issues no github, da mesma forma usar o 'closes #<num>' para referenciar e fechar o issues.

**PUSH**

Envia (empurra) o repositório local para o repositório remoto.

![push](data:image/png;base64,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)

** "origin" "master" é a versão principal do código.

**PULL**

Baixa (puxa) o repositório remoto para o repositório local.

**CHECKOUT**

Serve para alternar entre as branch.  _EX: git checkout [branch]_

Lembre-se 

- -b: é um flag que juntamente com 'checkout' irá criar uma nova branch e ao mesmo tempo alternaria para a nova branch criada. _resumidamente, ela está juntando o comando (git branch <nova_branch>) com o comando checkout_

**CLONE**

Serve para replicar um repositório.

**MERGE**

É usado para juntar branch. Para usar você precisa estar na branch 'principal' ou na branch que você quer mesclar. _Ex: Pense que temos 3 branch, sendo elas - main, comp e mit, se você quiser fundir a 'mit' na branch 'comp', você deve usar **git merge mit**, estando já na branch mit._

**BRANCH**

Cria uma nova branch.

**STASH**

É usado para 'guardar' seu momento atual de trabalho, guardando tudo que não está 'commitado'.

Se usado sem nenhum comando posterior, o git irá gerar uma msg e salvar.

- save: serve para deixar uma mensagem no stash que será salvo.
- list: ver todos os stash salvos
- pop: carregar um 'ponto' salvo, fazendo com que ele volte todos os arquivos não 'commitados' no momento do save.
- clear: limpar a lista, onde os stash são salvos.

**LOG**

Puxa todo o histórico do repositório.

Para navegar no histórico basta usar 'Page Down' e 'Page Up'. Se desejar sair do modo de visualização do log, basta digitar "q" ou então, colocar ":" e depois digitar "q".

Para chamar o histórico de uma pasta especifica dentro do repositório, basta digitar **git log <nome-da-pasta>**. _Até mesmo para ver histórico de um arquivo em especifico, o comando é o mesmo, basta apenas colocar o nome do arquivo no lugar que da pasta_

- --oneline: traz o histórico de uma forma resumida.
- --graph: mostra o histórico um pouco mais ilustrado.

**RESET**

Reverte um commit tirando do repositório local. 

HEAD~<num>: reverte na sequencia que os commit foram enviados. No <num> representa quantos commit ele vai reverter.

--soft: revertendo o commit, trazendo todas as alterações para o staging. 

​	HEAD~<NUM> pode ser usado logo apos o --soft para informar que ele irá reverter na sequencia de X commit para staging.

--mixed: reverte os arquivos 'commitados' para o 'working directory'. _Também pode ser usado com o HEAD~<NUM> no final._

--hard: apaga o commit, resultando em perca de código. _Também pode ser usado com o HEAD~<NUM> no final._

**Lembre-se que se usar apenas o comando _'git reset <sha>'_ ou _'git reset HEAD~<NUM>'_ ele irá interpretar como --hard.**

**REVERT**

Reverte um commit criando um novo commit. _HEAD~<NUM> pode ser usado aqui para escolher qual commit o 'revert' irá se basear.

**WORK DIRECTORY**

Lugar de trabalho onde os arquivos estão sendo alterados por você, antes mesmo de serem enviados para staging.



**ALGUNS OUTROS COMANDOS**

--version: mostra a versão do git na sua maquina.

status: mostra como está o estado da área de trabalho.

ls: mostra todas as pastas no local que você está.

clear: limpar a janela de comandos.

gitk: mostra todo o repositório de forma gráfica. (Apenas no Windows não é necessario instalar uma GUI [graphical user interface]).

mkdir: criar uma pasta

cd: entrar em uma pasta



### ILUSTRAÇÃO PARA AUXILIAR O ENTENDIMENTO

![IMAGEM](https://miro.medium.com/max/724/1*OqKfKe3mqCRbaWT2Y8YDOQ.png)

- rm --cached <file> : esse comando é usado para remover o arquivo do 'staging'.

  

