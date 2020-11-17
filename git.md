## Git
modified 已修改
staged 已暂存
committed 已提交
Untracked 未跟踪
### 方法
$ git init 管理文件
$ git config --list global 所有设置

$ git status 查看文件处于什么状态
注意：红色文件说明在工作区
      绿色文件说明在暂存区

$ git add 提交到暂存区
$ git commit -m'index.text第一次提交'  从暂存区提交到仓库
$ git checkout -- index.html  撤销操作（git仓库的代码覆盖工作区的代码）
$  clear 清屏窗口
$ git add . 一次性全部提交
$ git reset HEAD 从暂存区移除
