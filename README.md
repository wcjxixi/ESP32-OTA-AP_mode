# ESP32 OTA (Over-the-Air) via AP Mode

* AP 模式下的 ESP32 OTA (Over-the-Air)
* 适用于 Arduino 开发环境
* 移除了登录相关的文件和代码，访问 ip 地址或 esp32.local 直接显示上传固件页面

# 使用方法
* `data` 文件夹放到项目 (Sketch) 文件夹中
* Arduino IDE 安装 [arduino-esp32fs-plugin](https://github.com/lorol/arduino-esp32fs-plugin) 插件 (新版的 Arduino IDE 2 好像不支持)，Arduino IDE 中选择好开发板参数后，点 `ESP32 Sketch Data Upload`，然后选 `LittleFS`，会自动将 `data` 下的所有文件上传到开发板即可

> 实际只需要 `data` 文件夹下的 `index.html`、`jquery.min.js` 和 `style.css` 三个文件就可以
