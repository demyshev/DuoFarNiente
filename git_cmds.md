<!-- for a new repo otherwise git pull or git fetch -a -->
git clone <repo-ssh> 
<!-- see if git is initialized -->
git remove -V
<!--
create a new working branch to add custom change or do anything because we NEVER want to add anything
directly to main
-->

<!-- read about semantic CI feat for a feature, fix is when you are fixing somehting, chore is for everything else thats not feat, fix -->

git checkout -b <branchName> 

<!-- made a change -->
<!-- stage the change / add the change for tracking / start teracking the Change -->
<!-- . is to add everything -->
git add . 
<!-- lets give the changes we want to start tracking a meaningful name or message -->
git commit -m "<message>"

<!-- push for review -->
git push origin <branchName>

<!-- create a pull request for team review -->

<!-- git status to see your working change / status -->
git status

<!-- all new work have to start from main -->
git checkout main

<!-- to be on a safe side always git pull to always branch off of an up to date branch-->
git pull
