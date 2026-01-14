# pull
1. cd "path"
2. git pull

# push (if ada new file)
1. git status (it will show ur new file listed as untracked)
2. git add . (to track all new/modified file)
3. git commit -m "Add New file" (records the file in ur local git history)
4. git pull origin main --rebase (to avoid push rejection)
5. git push origin main

