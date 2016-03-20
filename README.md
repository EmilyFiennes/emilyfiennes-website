# Website: emilyfiennes.com
Personal website for emilyfiennes.com

## How to start the local server ?

```
# Change directory: Development
cd Development/emilyfiennes.com

# Instruction to python: start a new HTTP local Server with port 3080
python -m SimpleHTTPServer 3080

# In new terminal, open web browser at http://localhost:3080
open http://localhost:3080
```

## How to save local changes on Github ?

```

# Check for local changes
git status

# Stage changes for the next commit
git add index.html

# Message to git to commit with title "Draft 1"
git commit -m "Draft 1"

# Push commit to master
git push origin master

# If errors of synchronization, pull from master (then re-push)
git pull origin master


```
