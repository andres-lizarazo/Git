git init
git add <nombre del archivo>
git add .
git add -A
git add --all

git commit -m "Descripcion del commit"
gir commit --amend -m "cambio de descripcion"

git log
git log --graph --oneline --all
git log --oneline --graph
git status
git diff
git diff --staged
git log --oneline
git show id_commit

git remote add origin https://github.com/andres-lizarazo/mi-proyecto.git
git remote set-url origin https://github.com/tuUsuario/nuevo-repo.git
git remote remove origin

git branch -M main
git push -u origin main

git remote -v

git stash
git stash list
git stash apply
git stash clear

git checkout id_commit
git checkout main
git checkout -b develop
git branch
git merge
code