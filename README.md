# dotfiles
我的配置使用的是Chezmoi进行管理，chezmoi可以安全地跨多台不同的计算机管理您的点文件。因此在使用的我的配置之前需要安装Chezmoi

# 目前包括
  * .vimrc文件
  * .tmux文件
  * .vim中所有使用的插件——防止因为网速问题，下载不了

## 安装
可以查看[https://www.chezmoi.io/install/](安装教程)
这里推荐直接从源代码安装
```
git clone https://github.com/twpayne/chezmoi.git
cd chezmoi
make install-from-git-working-copy
```

## 将我的配置复制到你的电脑上
`chezmoi init https://github.com/Nullbeer/dotfiles`

## 通过运行以下命令检查 chezmoi 将对您的主目录进行哪些更改：
`chezmoi diff`

## 如果您对 chezmoi 所做的更改感到满意，请运行：
`chezmoi apply -v`

# 快速使用
直接将复制到用户目录，之后将`dot_`修改为`.`,即可直接使用。
```
cd ~
git clone https://github.com/twpayne/chezmoi.git
mv dot_vimrc .vimrc
mv .dor_vim .vim
```

