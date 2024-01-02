# lojavirtual
O objetivo desse projeto é dar os primeiros passos com o git e git/hub, além de aprofundar os conhecimentos já estabelecidos

	========CRIANDO UM REPOSITÓRIO LOCAL========

cd Desktop/
mkdir projeto
cd projeto
git init
git status

	========ALTERANDO ARQUIVOS NO REPOSITÓRIO========

git add .

	========FAZENDO O PRIMEIRO COMMIT

git commit -m "creating initial files"

	========VER HISTÓRICO DOS COMMITS========

git log
git log --oneline

	========PEDINDO AJUDA AO GIT========

git help --all

	========BRANCHS========

git branch       // VISUALIZAR
git branch nome  // CRIAR
git switch nome  // ENTRAR NA BRANCH

git switch -c nome // Criar e entrar na BRANCH

1)IR PARA A BRANCH IRÁ PERMANECER
2) git merge nome

	========GITIGNORE========

criar arquivo .gitignore

	========CORRIGINDO MENSAGEM DE COMMIT========

git --amend -m "mensagem do commit" (irá mudar apenas a última mensagem do commit)

	========VOLTANDO COMMIT ANTIGOS========

git revert HEAD --no-edit(volta um commit)
git reset código do commit (VOLTA PARA UM COMMIT ESPECÍFICO)
git stash 		(deixa todos os arquivos exatamente iguais ao commit anterior)


