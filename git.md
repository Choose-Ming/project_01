## Git
modified 已修改
staged 已暂存
committed 已提交
Untracked 未跟踪

A暂存区
D 已删除
？？未跟踪
### 方法
1.$ git init 管理文件
2.$ git config --list global 查看所有配置信息

$ git status 查看文件处于什么状态
注意：红色文件说明在工作区
      绿色文件说明在暂存区

$ git add 提交到暂存区
$ git commit -m'index.text第一次提交'  从暂存区提交到仓库
$ git checkout -- index.html  撤销操作（git仓库的代码覆盖工作区的代码）
$  clear 清屏窗口
$ git add . 一次性全部提交
$ git reset HEAD 从暂存区移除
$ git commit -a -m  跳过暂存直接存在仓库
$ git rm -f index.html 同时移除工作区和仓库
$ git rm --cached xxx 移除仓库

git log 提交历史 查看历史 Q结束查看
git log -2 提交最近两次历史
