# upload github repositories
git init
#create read.md file
cat > README.md  (ctrl + D to exit edit)
git add README.md
git config --global user.email chengneng0@gmail.com
git config --global user.name nengcheng
git commit -m "first commit"
git remote add origin https://github.com/nengcheng/clustering.git
git push -u origin master #enter code of email

#add second file
git add Kmeans_neng.py
git commit -m "second commit"
git push -u origin master  #input code/username   #Done!

#add third file
git add jones_cleaned.csv
git commit -m "test data"
git push -u origin master #same origin repository

# add to a new repository
git status
git add README.md
git remote set-url origin  https://github.com/nengcheng/hopkins_test.git
git remote -v
git commit -m "first commit"
git push -u origin master



rm -rf .git

