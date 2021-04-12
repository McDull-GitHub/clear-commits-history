<h2>刪除以前的commits</h2>

```

URL="https://github.com/McDull-GitHub/clear-commits-history.git" #換一下
git clone $URL && cd "$(basename "$_" .git)"
git checkout --orphan temporary_branch
git add .
git commit -m "Update"
git branch -D main
git branch -m main
git push origin main --force

```

<b>刪錯了不要找我！！！</b>
