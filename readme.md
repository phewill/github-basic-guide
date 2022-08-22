## Principais comandos e suas aplicações ##

### Sobre os estados dos arquivos podemos dividir em quatro estados ###

* Untracked
<p>Arquivo ainda não foi identificado como um arquivo a ser usado no git</p>

* Unmodified
<p>Arquivo não modificado</p>

* Modified
<p>Arquivo modificado</p>

* Staged
<p>Arquivo no stage quer dizer um arquivo que esta pronto para ser feito o commit</p>


#### Iniciar o git localmente ####
> git init

#### Mandar arquivos para o repositório no github ####
> git push

#### Atualizar repositório local com conteúdo do repositório remoto no github ####
> git pull
#### Verificar status dos arquivos ####
> git status

#### Verificar log ####
> git log

#### Adicionar arquivo na staging area ####
> git add 'arquivo'

#### Commitar(estado onde são criados os snapshots, cada commit é um snapshot) ####
> git commit -m 'mensagem' arquivo

#### add e comitar ####
> git commit -am 'mensagem' arquivo

------

#### Para criar uma nova branch ####
> git branch nova-branch

#### acessar uma branch ####
> git checkout nome-da-branch

#### Para excluir branch ####
> git branch -d nome-branch

#### Criar e entrar na branch ####
> git cheackout -b nome-branch

#### Relacionar commit a uma issue colocar #+numero da issue na msg####
> git commit -m "meu commit #12"

#### Para fazer push em uma branch diferente da master ####
> git push origin(github no caso) nome-da-branch

#### Para fazer o commit e encerrar a issue ####
> git commit -m "alteracao feita closes #11"
closes ou fixed

#### Fazer a branch master pegar as alterações de outra branch ####
> git merge nome-outra-branch
