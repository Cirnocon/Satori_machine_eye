# 机械觉之瞳
## 作者
Cirnocon

## 联系方式
电子邮件： cirnocon5@gmail.com 或 reedscirno@gmail.com

GitHub：https://github.com/Cirnocon

b站：Cirnocon

## 项目结构
- `ESP32EYE/`
    - `boards` 开发板配置文件，主要是启用psram

    - `data` SPIFFS文件储存文件夹
        - `index.html` html文件

        - `nipplejs.min.js` 摇杆库（虽然没用上）

    - `lib/` 自定义库文件夹
        - `AsyncWebCam` 

    - `src/` 源代码文件夹
        - `main.cpp` 
        
    - `partitions.csv` 分区表
    
    - `platformio.ini` ***platformio*** 配置文件


## 注意事项
所有配置文件都是基于 ***ESP32-S3-N16R8*** 写的

***platformio*** 的程序烧录并不会自动更新 ***SPIFFS*** 系统文件，需要手动更新

> 具体方法: ***Bulid Filesystem Image*** -> ***Program Size*** -> ***Upload Filesystem Image***
