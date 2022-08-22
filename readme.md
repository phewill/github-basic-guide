# <center>Guia básico de git e github</center>

## Principais comandos e suas aplicações


**Iniciar o git localmente :**<br>
<code>
git init
</code>



Mandar arquivos para o github
git push

Atualizar repositório local com github
git pull

Verificar status dos arquivos
git ignore

Verificar log
git log

Adicionar arquivo a staging area
git add 'arquivo'

Commitar(status onde são criados os snapshots)
git commit -m 'mensagem' arquivo

add e comitar
git commit -am 'mensagem' arquivo


-------------------------

Para criar uma nova branch
git branch nova-branch

acessar uma branch
git checkout nome-da-branch

Para excluir branch
git branch -d nome-branch

Criar e entrar na branch
git cheackout -b nome-branch

Para indicar que commit é relacionado a uma issue colocar #+numero da issue
git commit -m "meu commit #12"

Para fazer push em uma branch diferente da master
git push origin(github no caso) nome-da-branch

Para fazer o commit e encerrar a issue
git commit -m "alteracao feita closes #11"
closes ou fixed

Fazer a branch master pegar as alterações de outra branch
git merge nome-outra-branch