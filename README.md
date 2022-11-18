# dotfiles
我的配置使用的是Chezmoi进行管理，chezmoi可以安全地跨多台不同的计算机管理您的点文件。因此在使用的我的配置之前需要安装Chezmoi

# 安装
可以查看[https://www.chezmoi.io/install/](安装教程)
这里推荐直接从源代码安装
```
git clone https://github.com/twpayne/chezmoi.git
cd chezmoi
make install-from-git-working-copy
```

# 将我的配置复制到你的电脑上
`chezmoi init https://github.com/$GITHUB_USERNAME/dotfiles.git`

