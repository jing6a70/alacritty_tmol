# 安装前
- 安装 `FiraCode` 字体
- 例如： `sudo dnf install fira-code-fonts.noarch`
- 检查字体： `fc-list | grep fira`
- 显示如下说明安装成功:
```bash
/usr/share/fonts/fira-code/FiraCode-Bold.ttf: Fira Code:style=Bold
/usr/share/fonts/fira-code/FiraCode-Retina.ttf: Fira Code,Fira Code Retina:style=Retina,Regular
/usr/share/fonts/fira-code/FiraCode-Regular.ttf: Fira Code:style=Regular
/usr/share/fonts/fira-code/FiraCode-Medium.ttf: Fira Code,Fira Code Medium:style=Medium,Regular
/usr/share/fonts/fira-code/FiraCode-SemiBold.ttf: Fira Code,Fira Code SemiBold:style=SemiBold,Regular
/usr/share/fonts/fira-code/FiraCode-Light.ttf: Fira Code,Fira Code Light:style=Light,Regular
```

# 安装此配置文件
1. 安装次配置
   ```bash
   mkdir -p ~/.config/alacritty
   git clone https://github.com/jing6a70/alacritty_tmol.git ~/.config/alacritty
   ```

2. 安装配置文件. 主题git仓库地址<可以查看各种主题> : https://github.com/alacritty/alacritty-theme.git
   ```bash
   # We use Alacritty's default Linux config directory as our storage location here.
   mkdir -p ~/.config/alacritty/themes
   git clone https://github.com/alacritty/alacritty-theme ~/.config/alacritty/themes
   ```
   
