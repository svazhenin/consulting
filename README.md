mkdir findir-mono && cd findir-mono
git init -b main
echo "# FinDirector MVP" > README.md
printf "node_modules\n.env\n.DS_Store\n" > .gitignore
git add .
git commit -m "chore: init repo"
git remote add origin git@github.com:<твой_org_или_user>/findir-mono.git
git push -u origin main
