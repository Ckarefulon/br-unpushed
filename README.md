# 临时测试仓库（可删除）

用于 Build-Runner 的回归验证，已完成使命。

删除需要 delete_repo 权限：

\ash
gh auth refresh -h github.com -s delete_repo
gh repo delete Ckarefulon/br-unpushed --yes
\\n