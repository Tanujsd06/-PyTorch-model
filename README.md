# -PyTorch-model
 PyTorch model
# create repo (local)
mkdir mlops_major && cd mlops_major
git init
echo "# ML Ops Major Assignment" > README.md
echo "__pycache__/" > .gitignore
git add README.md .gitignore
git commit -m "chore: initial README and gitignore"
git branch -M main
# push to GitHub (create remote repo on github.com then:)
git remote add origin git@github.com:<your_username>/<repo>.git
git push -u origin main
