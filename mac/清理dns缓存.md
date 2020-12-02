# 如何清除Mac OS中的本地DNS缓存

要在Mac OS（最多El Capitan）中刷新本地DNS缓存，请使用终端：

- 转到**应用程序**>**实用程序**>**终端**
- 输入以下命令，然后按Enter：

```
dscacheutil -flushcache
```

- 之后，键入第二个命令，然后按Enter：

```
sudo killall -HUP mDNSResponder
```

