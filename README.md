# 一些设置简单但繁琐且容易忘记的路径



## 对于无谷歌套件的内地手机，下载Firefox火狐浏览器的地址：

https://github.com/mozilla-mobile/firefox-android/releases

- 对于拥有谷歌套件的手机，直接Google play即可
  

## Azure能设置`动态IP`的前提是，需要在设置为`无需基础结构冗rong余`

![Example Image](/Pictures/屏幕截图%202024-06-22%20230944.png)


- `SKU`需要选择`基本`，才会出现`动态IP`

![Example Image](/Pictures/屏幕截图%202024-06-22%20230716.png)

1. 无特殊用处，磁盘可以选`HDD`以节约成本，而不是`默认的SSD` 




2. `Ping`服务器需要打开端口，粗暴方式直接打开全部进出端口，`优先级`设置为尽量小


![Example Image](/Pictures/屏幕截图%202024-06-22%20231818.png)



## 国内一加刷Oxygen氧OS的地址为海外版一加Oneplus官网

https://www.oneplus.com/global

点击Support，`注意这里的global可以换为us、uk、in等，以对于需要的版本`

https://service.oneplus.com/global

点击Software Upgrade，选择机型

- 目前似乎官网没有 ONEPLUS 11 之后的官方包了


- 另：Google play上有社区版`Oxygen Updater`安装器可以使用


## Surge设置局域网 （忘了）

填写198.  然后加端口



## OpenAI Key临时使用

```bash
export OPENAI_API_KEY='your_openai_api_key'
```

## 登录远程服务器Remote server不用密码

ssh-copy-id -i ~/.ssh/id_ed25519.pub remote_user@server_address


