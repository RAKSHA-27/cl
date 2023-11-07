<br>Create local file -> Fork repository
<br>Go to Git Bash -> cd .. -> cd student/Desktop/devo
<br> git init -> git config --global user.name "RAKSHA-K-R" -> git config --global user.email "20aiml0090@vvce.ac.in"\
<br> git clone "https://github.com/RAKSHA-K-R/sum.git" -> cd sum
<br><b>STEP 2</b>
<br> Create file in main branch -> nano samename.txt -> git add samename.txt -> git commit -m "Main file with samename as branch file"
<br> Create new branch -> git checkout -b "branch1" ->nano samename.txt ->Make changes in the txt file -> git add samename.txt -> git commit -m "Branch file with samename as main file"
<br> Return to master branch -> git checkout "master" -> Make changes in main samename.txt file -> git add samename.txt -> git commit -m "Ready to merge"
<br> git merge "branch1"  -------> Merge Conflict Encountered
<br> git diff
<br> git merge --abort
