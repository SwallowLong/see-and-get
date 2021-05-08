# see-and-get
git checkout -b branch-name origin/branch-name 测试
  * git push 测试
  * 通过git branch -vv 查看是否绑定的为相应分支 如果是 则可以直接git push 不需要指定远程仓库
  * 绑定远程仓库命令测试
  * 首先使用git push origin branch-name 推送远程分支（即在GitHub上创建一个名为branch-name的新的远程分支）
  * 当创建分支后 使用git branch -u origin/branch-name 关联远程分支名
  * 此时 即可直接使用git push 来推送了

  * 方法二
  * git checkout need-branch-name
  * git checkout -b branch-name 
  * git push origin branch-name 
  * git push --set-upstream origin branch-name 绑定远程仓库 
  * 可直接使用 git push 推送