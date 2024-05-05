
# To create README.md file -
echo "# github-imran" >> README.md 

git init

# Before commit-
git add README.md

# To commit 
git commit -m "first commit"

# To set the branch-
git branch -M main

# To link to repo-
git remote add origin https://github.com/imranlim/github-imran.git

# Upload file-
git push -u origin main
# For create branch-
 git chechkout -b 

# To confirm what branch
 git status

# Before commit -all file edit-
git add .

# Before commit -specific file-
git add {file name}

# To commit-
git commit -s -m"{massage}"

# To push-
git push -u origin {branch name}

# To tell what to download and where -
git fetch origin {location name/branch name example-main}

# To download -
git pull origin {location name/branch name example-main}

