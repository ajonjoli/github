```bash
# configure e-mail and name for identification

git config --global user.email "myluisortiz@gmail.com"  
git config --global user.name "Luis Ortiz Chan"

---

# clone for the first time  
# it will download repository in a new folder in current path

git clone https://github.com/ajonjoli/github.git

---

# show current status on git environment

git status

---
# add file to git tracking of changes, or add to next commit,  
# local -> staging

git add filename.txt

---

# add all files on folder to git tracking
# every time to THIS AND THE REST
git add .

---

# commit all updates
# staging -> head

git commit -m "comments comments"

---

# push to repository branch master
# head -> repository branch
# it asks for github user & pass

git push origin master
```
