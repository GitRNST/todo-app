# todo-app

1. Invite the people (GitHub -> collabration -> Add People -> Email)
2. Git clone in local rep
3. create a new branch like dev-ambu - git checkout -b dev-ambu
4. check current branch - git branch
5. switch to our current branch "dev-ambu" - git checkout dev-ambu
6. Pull the staging code - git pull origin staging
7. work local rep and commit to dev-ambu rep
    -> git add .
    -> git commit -m "your changes"
    -> git push origin dev-ambu
8. dev-ambu to staging rep
    -> git fetch origin
    -> git checkout staging
    -> git merge origin/dev-ambu
    -> git add .
    -> git commit -m "dev-ambu to staging changes"
    -> git push origin staging