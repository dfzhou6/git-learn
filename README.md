# git-learn
### git reset
git reset HEAD^ // 回滚到上一个提交(工作区)
 
git reset --soft HEAD^ // 回滚到上一个提交(暂存区)

git reset --hard HEAD^ // 回滚到上一个提交(全部清除)

### git checkout
git checkout index-file // 撤销索引文件在工作区中的修改

### git rm
git rm index-file // 撤销索引文件在暂存区中的修改

git rm --cached index-file // 撤销索引文件在暂存区中的修改到工作区

