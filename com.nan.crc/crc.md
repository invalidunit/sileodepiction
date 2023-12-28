# Check repo change 配置文件添加 key
## 一、从 App Store 安装 Bark

1.请先从 App Store 中安装 Bark App，这是为你推送通知的方式，主要目前还没找到（也可能我不会）纯终端可以往越狱设备推送通知的命令

[点击此处跳转 App Store](https://apps.apple.com/app/id1403753865 "Bark")

![image_1_1_1_light](./images/image_1_1_1_light.png)
## 二、获取 Bark 推送 key

1.打开 Bark app 后点击中心的圆形注册按钮

2.按下图黄色框框圈起来的位置复制链接

![image_2_1_1_light](./images/image_2_1_1_light.png)

3.将复制出来的链接仅保留上图红色框框部分（两个斜杠中间夹着的部分就是 key，不包含斜杠）
## 三、在配置文件中为 crc 应用 bark 的 key

1.从 Filza 中打开文件

	<bark data>/Library/Preferences/com.nan.crc.plist

\<bark data\> 即 bark 存放数据的路径

2.点击 bark 展开子菜单，找到 key 也就是下图红框位置

![image_3_2_1_light](./images/image_3_2_1_light.png)

3.点击 key 右侧的 i 也就是上图黄框位置，并粘贴第二步中获得的 key

4.配置完 key 后可以重装软件包，这会触发一条测试用的通知，告诉你开始工作了
