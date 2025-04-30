git init
git add <nombre del archivo>
git add .
git add -A
git add --all

git commit -m "Descripcion del commit"

git log
git status
git diff
git log --oneline
git show "id del commit"

git remote add origin https://github.com/andres-lizarazo/mi-proyecto.git
git remote set-url origin https://github.com/tuUsuario/nuevo-repo.git
git remote remove origin

git branch -M main
git push -u origin main

git remote -v
