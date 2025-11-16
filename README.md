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


requirements.text
scikit-learn==1.2.2
joblib==1.2.0
flask==2.2.5        # only needed later but safe to include
numpy==1.24.2
opencv-python-headless==4.8.1.78  # optional for image preproc if needed

