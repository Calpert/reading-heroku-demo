To create a new repository on the command line:
echo "# reading-heroku-demo" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:Calpert/reading-heroku-demo.git
git push -u origin main