# chrome-cross-domain-setting
谷歌浏览器跨域设置
## 1.mac设置
  通过terminal运行macOpenChrome.sh 即可完成设置
  ```
  bash macOpenChrome.sh
  ```
## 2.windows设置
  打开Chrome浏览器发送到桌面快捷方式 --右击属性--目标后面空格 加入下面的代码
  ```
  --args --disable-web-security --user-data-dir
  ```
