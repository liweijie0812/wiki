JetBrains linux中文输入法无法使用

## pycharm

```
# 查看pycharm.sh文件路径
find -name 'pycharm.sh'
```

编辑pycharm.sh,在 "Run the IDE" 之前添加

```
export GTK_IM_MODULE=fcitx 
export QT_IM_MODULE=fcitx 
export XMODIFIERS=@im=fcitx

# ---------------------------------------------------------------------
# Run the IDE.
# ---------------------------------------------------------------------
```

关掉pycharm,重新打开pycharm

## JetBrains全家桶都可以通过这样的方式处理中文输入法无法输入的问题