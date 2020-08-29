# bangdream防沉迷破解

原理：bilibili游戏的防沉迷似乎是通过几个地址的返回值确定的，拦截对这几个地址的访问即可

似乎大多数b服游戏都可以用这个办法破解防沉迷

破解成功设备: `mi 5s`、`vivo x6sa`


请根据您的实际情况选择不同方式进行操作

- [无root模式(简单)](#无root)
- [root模式(略有难度)](#root)

## 无ROOT

#### 所需应用

[adguard](https://zhouzerong.coding.net/api/share/download/ee6e9106-2cd7-4743-8ac6-265749f7ff07)

#### 操作步骤
1. 安装adguard，并根据应用提示进行初始化

2. 进入adguard`设置`->`内容拦截`->`User rules`，点击右上角三个点，导入以下url内容

```
https://zhouzerong.coding.net/api/share/download/0aed65bd-83ba-4ada-a016-8fd2f92af1a4
```

3. 保持adguard正常开启状态进入游戏即可，游戏过程中需**保持adguard后台正常运行**

## ROOT
1. 确保您的设备可以正常读写hosts文件
> hosts文件路径:/etc/hosts

2. 在您的hosts末尾添加以下内容

```
# bilibiligame anti-addiction
127.0.0.1 p.biligame.com
127.0.0.1 line1-login.biligame.net
127.0.0.1 line3-login.biligame.net
127.0.0.1 line1-realtime-api.biligame.net
127.0.0.1 line3-realtime-api.biligame.net
127.0.0.1 line1-sdkcenter-login.bilibiligame.net
127.0.0.1 line3-sdkcenter-login.bilibiligame.net
127.0.0.1 line1-sdk-center-login-sh.biligame.net
127.0.0.1 line3-sdk-center-login-sh.biligame.net
# bilibiligame anti-addiction end
```

3. 进入游戏即可