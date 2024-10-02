== Development stuff

=== Create new repository
echo "# LocalNews2" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:rtibell/LocalNews2.git
git push -u origin main

=== Create new Dev branching 
git pull 
git branch <dev_branch_name> 
git checkout <dev_branch_name>
git commit -m "first branch commit"
git push -j origin <dev_branch_name>

==== Merge in changes from main (periodically)
git merge main

