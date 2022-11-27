# Treinando o Git

## Untracked
- Não marcado: Arquivo adicionado que o git não viu!

## Unmodified
- Existe no git, mas não foi modificado!

## Modified
- O git já o conhece, mas foi modificado. Precisa de um commit para ser adicionado!

## staged
- Momento de criação de uma imagem/versão/hash no github.
- Fazendo uma alteração!

## git log
	## git log --decorate
	## git log --author="leandro"
	## git shortlog
	## git shortlog -sn
	## git log --graph
	## git diff
	## git diff --name-only

## git checkout <arquivo> ou git restore <arquivo>
- Volta as modificações do arquivo que não foram comitados!

## git reset HEAD <arquivo> 
- Reseta o commit feito por tal arquivo!!

## git merge nome-da-branch
- Tem que estar na branch master e para fazer o 'merge' da outra branch

## git rebase 
- Melhor que o 'merge' pois deixa tudo numa linha só sem confusão ou confitos

## git stash
- Guarda as alterações numa parte fora, sem precisar dar o 'commit' 
	## git stash apply
	- Volta as modificações tirando as do lugar à parte
	## git stash list
	## git stash clear
	- limpa o lugar 

## git config --global alias.o-atalho comando
- ex: git config --global alias.s status

## git tag
- ex.: git tag -a 1.0.0 -m "Create alguma coisa"

## git revert 
- Reverte pro commit anterior sem apagar as alterações atuais

## git tag -D numero-da-tag
- deletar a tag

## para deletar o mesmo no github: git push origin :1.0.0
## para deletar uma branch da mesma forma: git push origin :teste

[![Botão](https://leandrocesar.com/img/favicon.ico)](https://leandrocesar.com)
