# server-ngrok-6h
默认配置运行时间为6h

**使用方法**
1、fork本项目

2、进入 `ngrok.com` 使用GitHub账户授权注册登录
  之后会跳转到账户设置里，复制下图的token
  ![](https://cdn.jsdelivr.net/gh/gouidea/picbed-go/img/20210111035454.png)

3、回到GitHub，填入到 `ssh.yml`文件中
  ![](https://cdn.jsdelivr.net/gh/gouidea/picbed-go/img/20210111035807.png)

4、再去启动Action，期间会给出ssh登录账户信息（密码默认为123456）

5、登录成功，由于没有公网端口，可以配合内网穿透工具，连接外网
  ![](https://cdn.jsdelivr.net/gh/gouidea/picbed-go/img/20210111040403.png)

**其他说明**
在 `.github/workflows`文件夹下的 `ssh.yml` 里可以配置登录密码
配置项 `USER_PASS` 的参数就是可以自定义的密码
