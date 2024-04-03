# Github & Git
`git --version`
`where git`
`git status`
# 初始化仓库
`git init`
# 追踪文件:git add命令并没有把文件提交到 Git 仓库，而是把文件添加到了「临时缓冲区」
`git add`
# 提交信息到仓库:commit表示提交，-m表示提交信息，提交信息写在双引号""内
`git commit -m "text commit"`
# 打印Git仓库提交日志
`git log`
# 查看仓库分支情况
`git branch`
# 切换到新分支
`git checkout `
# 创建分支并且切换到分支
`git checkout - `
# 将分支合并到当前分支
`git merge `
# 删除分支
`git branch -d `
强制删除
`git branch -D `
# 为当前分支添加标签
`git tag `
查看标签
`git tag`
# 切换到该标签的代码状态
`git checkout tag_name`
# 表示我们指定 RSA 算法生成密钥，然后敲三次回车键，期间不需要输入密码，之后就就会生成两个文件，分别为id_rsa和id_rsa.pub，即密钥id_rsa和公钥id_rsa.pub. 对于这两个文件，其都为隐藏文件
` ssh-keygen -t rsa`
# 生成SSH key 连接GitHub
`ssh-keygen -t rsa -C “your_email.com”`
` ssh -T git@github.com`

