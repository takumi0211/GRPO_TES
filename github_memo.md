git fetch --all --prune
git reset --hard origin/main
git clean -fd

git add -A
git commit -m "変更"
git push origin main