IRbaby 使用 IRext 开源红外库，提供数以万计的红外设备遥控编码。IRbaby 是一个 ESP8266 万能红外方案，配合硬件支持达到类似于市面上售卖的万能红外遥控。并且只需对其进行简单设置就可以快速部署在HomeAssisant

#特点

Irext 强大红外码库

基于 ESP8266 的模块

提供 MQTT 控制

提供 UDP 接口

支持录码

离线解码

HomeAssistant 自动发现

#开始使用

下载 ESP8266 固件并烧写到设备。IRbaby-firmware

设备上电，移动端搜索连接到 ESP** 信号，并在浏览器中输入 192.168.4.1 对设备进行联网设置

下载 Android 客户端并运行,对设备进行 MQTT 和红外收发引脚设定。IRbaby-android

匹配电器，完成控制, HomeAssistant 用户可在控制界面导出配置文件（现支持 HomeAssistant 自动发现功能，设备添加之后，可直接在 HA 集成中看到）

IRbaby目前仍处于开发阶，目前的交互协议可能随时改变，不保证向后兼容，升级新版本时需要注意公告说明同时升级固件和客户端。

#六步连接HomeAssistant

