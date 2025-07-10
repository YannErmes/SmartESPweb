

cd /path/to/your/folder
git init
git add .
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/YannErmes/SmartESPweb.git
git push -u origin main
# Make changes to your files
git add .
git commit -m "Your commit message"
git push origin main

git remote remove origin

