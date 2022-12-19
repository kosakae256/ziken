# ziken
事件

最新のdevブランチの情報を取得
```
git checkout dev
git pull origin dev
```

作業用のブランチに移動
```
# git branch <name>
git checkout sakatoku
git pull origin sakatoku
```

作業後
```
git add .
git commit -m "commit message"
git push origin push

git checkout dev
git merge sakatoku
git push origin dev
```
