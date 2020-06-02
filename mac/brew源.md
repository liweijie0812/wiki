# brew 切换源

## Homebrew

### 国内源

```bash
# 中国科学技术大学
git -C "$(brew --repo)" remote set-url origin https://mirrors.ustc.edu.cn/brew.git
# 清华大学
git -C "$(brew --repo)" remote set-url origin https://mirrors.tuna.tsinghua.edu.cn/git/homebrew/brew.git
# 阿里云
git -C "$(brew --repo)" remote set-url origin https://mirrors.aliyun.com/homebrew/brew.git

```

### 官方源

```bash
git -C "$(brew --repo)" remote set-url origin https://mirrors.ustc.edu.cn/brew.git
```

## Homebrew Core

### 国内源

```bash
# 中国科学技术大学
git -C "$(brew --repo homebrew/core)" remote set-url origin origin https://mirrors.ustc.edu.cn/homebrew-core.git
# 清华大学
git -C "$(brew --repo homebrew/core)" remote set-url origin https://mirrors.tuna.tsinghua.edu.cn/git/homebrew/homebrew-core.git
# 阿里云
git -C "$(brew --repo homebrew/core)" remote set-url origin https://mirrors.aliyun.com/homebrew/homebrew-core.git
```

### 官方源

```bash
git -C "$(brew --repo homebrew/core)" remote set-url origin https://github.com/Homebrew/homebrew-core.git
```

## Homebrew Cask

### 国内源

```bash
# 中国科学技术大学
git -C "$(brew --repo homebrew/cask)" remote set-url origin https://mirrors.ustc.edu.cn/homebrew-cask.git
# 清华大学
git -C "$(brew --repo homebrew/cask)" remote set-url origin https://mirrors.tuna.tsinghua.edu.cn/git/homebrew/homebrew-cask.git
```

### 官方源

```bash
git -C "$(brew --repo homebrew/core)" remote set-url origin https://github.com/Homebrew/homebrew-cask.git
```



## Homebrew-bottles

**对于 bash 用户：**

```bash
# 中国科学技术大学
echo 'export HOMEBREW_BOTTLE_DOMAIN=https://mirrors.ustc.edu.cn/homebrew-bottles' >> ~/.bash_profile
# 清华大学
echo 'export HOMEBREW_BOTTLE_DOMAIN=https://mirrors.tuna.tsinghua.edu.cn/homebrew-bottles' >> ~/.bash_profile
# 阿里云
echo 'export HOMEBREW_BOTTLE_DOMAIN=https://mirrors.aliyun.com/homebrew/homebrew-bottles' >> ~/.bash_profile
source ~/.bash_profile
```

**对于 zsh 用户：**

```bash
# 中国科学技术大学
echo 'export HOMEBREW_BOTTLE_DOMAIN=https://mirrors.ustc.edu.cn/homebrew-bottles' >> ~/.zshrc
# 清华大学
echo 'export HOMEBREW_BOTTLE_DOMAIN=https://mirrors.tuna.tsinghua.edu.cn/homebrew-bottles' >> ~/.zshrc
# 阿里云
echo 'export HOMEBREW_BOTTLE_DOMAIN=https://mirrors.aliyun.com/homebrew/homebrew-bottles' >> ~/.zshrc
source ~/.zshrc
```

## 还原

删掉 HOMEBREW_BOTTLE_DOMAIN， bash 用户在~/.bash_profile， zsh 用户在~/.zshrr 



## 国内源使用帮助文档

### 中国科学技术大学 

https://lug.ustc.edu.cn/wiki/mirrors/help/brew.git

https://lug.ustc.edu.cn/wiki/mirrors/help/homebrew-bottles

### 清华大学 

https://mirrors.tuna.tsinghua.edu.cn/help/homebrew/

https://mirrors.tuna.tsinghua.edu.cn/help/homebrew-bottles/

### 阿里云 

https://developer.aliyun.com/mirror/homebrew?spm=a2c6h.13651102.0.0.24311b11yUaqvc



