mkdir Task1
cd Task1
echo "hello World!" > README.md
git add .
git commit -m "first commit"
git push
git branch dev
git checkout dev
touch testfile.txt
git add testfile.txt
git commit -m "Pushing a testfile"
git push --set-upstream origin dev
git branch Ahmed-new_feature
git status
echo ".*" > .gitignore
echo "!.gitignore" > .gitignore
git add .gitignore
git commit -m "add .gitignore file"
git push
git checkout Ahmed-new_feature
echo "Ahmed" >> README.md
git commit -m "README.md changes"
git revert HEAD
git log > log.txt
git branch -D Ahmed-new_feature