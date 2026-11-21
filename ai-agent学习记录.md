## 关于 Git 分支与提交记录的实操
我真实体验了一次 Git 的分支操作：
1. 创建并切换分支：我输入了 `git checkout -b test-branch-2`
2. 修改文件：加入了关于 Git 分支与提交记录的实操记录
3. 提交（commit）：我把这个改动存了档
4. 切回主分支（checkout main）：加的文字在 VS Code 里消失了，说明主分支完全没被影响，分支隔离了
5. 合并（merge）：我输入了 `git merge test-branch-2`，刚才消失的文字又回到了主分支里
通过实操，我这段时间每次修改笔记，都会用 `git commit` 存个档，用 `git push` 传到 GitHub 网页上，打开网页能看到我所有的提交记录
