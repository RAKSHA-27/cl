--> for main branch one file should be pushed to show the main branch
<br>Step 1:Search and fork the public repo
<br>Step 2:git clone repo link from code
<br>Step 3:cd repo name 
<br>Step 4:nano file.txt
<br>
<br>git init
<br>
<br>Step 5:git add file.txt
<br>Step 6:git commit -m "Intial Commit"
<br>Step 7:git push

<b> Creat branch 1 from main </b>
<br>git checkout -b "Branch_name"
<br>nano file1.txt
<br>git add file1.txt
<br>git commit -m "Branch1 File1"

<b> Creat branch 2 from main </b>
<br>git checkout -b "Branch_name"
<br>nano file2.txt
<br>git add file2.txt
<br>git commit -m "Branch2 File2"

<br> git branch

<br> git checkout "branch_name"       ----exit the present branch/change the branch
<br> git checkout "main"              ----if two files in branch has same name then there will be a issue 
