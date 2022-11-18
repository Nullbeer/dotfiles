# dotfiles
我的配置使用的是Chezmoi进行管理，chezmoi可以安全地跨多台不同的计算机管理您的点文件。
因此在使用的我的配置之前需要安装Chezmoi
[https://www.chezmoi.io/install/](安装教程)

#在当前计算机上开始使用 chezmoi,将我的配置复制到你的电脑上
`chezmoi init https://github.com/$GITHUB_USERNAME/dotfiles.git`
这将在其中创建一个新的 git 本地存储库 Chezmoi 将存储其源状态。默认情况下，chezmoi 只修改 工作副本。~/.local/share/chezmoi
使用 chezmoi 管理您的第一个文件：
`$ chezmoi add ~/.bashrc`
这将复制到。~/.bashrc~/.local/share/chezmoi/dot_bashrc
编辑源状态：
`$ chezmoi edit ~/.bashrc`
