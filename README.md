echo "# clone-tabnews" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:trcroots/clone-tab-news.git
git push -u origin main
