## Principais comandos e suas aplicações ##

**Iniciar o git localmente** <br>
git init

**Mandar arquivos para o github** <br>
git push

**Atualizar repositório local com github** <br>
git pull

**Verificar status dos arquivos** <br>
git ignore

**Verificar log** <br>
git log

**Adicionar arquivo a staging area** <br>
git add 'arquivo'

**Commitar(status onde são criados os snapshots)** <br>
git commit -m 'mensagem' arquivo

**add e comitar** <br>
git commit -am 'mensagem' arquivo

-------------------------

**Para criar uma nova branch** <br>
git branch nova-branch

**acessar uma branch** <br>
git checkout nome-da-branch

**Para excluir branch** <br>
git branch -d nome-branch

**Criar e entrar na branch** <br>
git cheackout -b nome-branch

**Para indicar que commit é relacionado a uma issue colocar #+numero da issue** <br>
git commit -m "meu commit #12"

**Para fazer push em uma branch diferente da master** <br>
git push origin(github no caso) nome-da-branch

**Para fazer o commit e encerrar a issue** <br>
git commit -m "alteracao feita closes #11"
closes ou fixed

**Fazer a branch master pegar as alterações de outra branch** <br>
git merge nome-outra-branch
