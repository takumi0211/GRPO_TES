git fetch --all --prune
git reset --hard origin/main
git clean -fd

git add -A
git commit -m "add print(GPU)"
git push origin main