使用方法

1. 安装 python-CuteCat-iHttp 插件

   ```
   pip3 install git+https://github.com/0honus0/python-CuteCat-iHttp.git
   ```
2. 安装efb-telegram-master

   ```
   pip3 install efb-telegram-master
   ```
3. 安装efb-wechat-cutecat-slave

   ```
   pip3 install -U git+https://github.com/0honus0/efb-wechat-cutecat-slave.git
   ```
4. 配置 config.yaml (路径 honus.CuteCatiHttp/config.yaml)

   ```
   api_url: "http://127.0.0.1:8090"
   self_url: "http://127.0.0.1:18888"
   robot_wxid: ""
   access_token: ""
   ```

api_url 为运行可爱猫的ip + iHttp 插件的 port

self_url 为运行efb从端的 ip + port

robot_wxid 为作为机器人的微信id

access_token 鉴权使用，可在iHttp路径下配置文件中找到，如果开启则需要设置，否则不需要
