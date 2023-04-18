git reset --hard         # 回溯到未更改前(只有在git commit -m之前才有用)

#總有一天會忘記

git reset --hard HEAD~1  # 直接銷毀上一個commit
git checkout HEAD~2      # 回溯到2個commit
git checkout -           # 回溯1個commit
git checkout dog         # 切換分支
git brach                # 查看有多少分支
git branch dog           #創造分支