git@github.com:by2016ling/learn.git

echo "# learn" >> README.md

git remote add origin git@github.com:by2016ling/learn.git
git push -u origin master

//i2.hdslb.com/bfs/openplatform/201801/imjpStkBel716.jpeg@600w_800h.jpeg

Delta compression using up to 8 threads.
Compressing objects: 100% (15/15), done.
Writing objects: 100% (22/22), 1.75 KiB | 128.00 KiB/s, done.
Total 22 (delta 5), reused 0 (delta 0)
remote: Resolving deltas: 100% (5/5), done.
To github.com:by2016ling/learn.git
 * [new branch]      master -> master
Branch 'master' set up to track remote branch 'master' from 'origin'.

合并分支时，如果可能，Git会用Fast forward模式，但这种模式下，删除分支后，会丢掉分支信息。
git log --graph --pretty=oneline --abbrev-commit dev2

