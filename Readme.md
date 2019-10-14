#GitHub

1) git-config:


git config --list = tudo que tenho no meu git
git config --global core.editor code = editar editor do git
git config --global user.email = editar email do git 
git config --global user.name = editar nome do git

2) git add:

git add Readme.md = adicionar Readme.md no git


3) git status:

git status = informações do git atual

4) quando salvar algo aqui:

Changes not staged for commit:
arquivo qeu ainda não foi salvo

precisa fazer um git add 

Se quiser salvar mudanças = git commit -m "Add Reame.md"

5) git log = utilizar bastante para ver as informações

git log = informações dos arquivos
git log -- decorate = informações dos branchs
git log --author="Lincoln" = busca de determinado autor

git shortlog = informações sobre cada contribuinte
git shortlog -sm = pessoa + quant de commit
git log --graph = informações das mudanças em cada branch

git show  = ir no git log, buscar o numero do commit e ver as alterações feitas