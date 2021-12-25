#### 硬件配置

+ 主板：微星MAG B460M MORTAR
+ CPU：i7-10700
+ 显卡：暂无
+ 内存：美商海盗船(USCORSAIR)DDR4 3200 16GB x2
+ 硬盘：WD SN750 500G
+ 电源：海韵 CORE GM650
+ 显示器：小米 4k 显示器
+ 无线网卡/蓝牙：BCM943602CS【Bluetooth 4.1, 1300M 免驱】

### 软件版本

+ BIOS版本：E7C82IMS.120
+ OpenCore版本：0.6.7
+ MacOS版本：11.2.3

### Change log

+ 2021.04.06 参考 [myqqiu](https://github.com/myqqiu/Hackintosh-B460M-MORTAR-i5-10500-iGPU-UHD630) 更新到 opencore 0.6.7
+ 2021.04.06
  + 参考 [myqqiu](https://github.com/myqqiu/Hackintosh-B460M-MORTAR-i5-10500-iGPU-UHD630) 更新到 opencore 0.7.4
  + 更新到小米 4k 显示器, 实测 `enable-max-pixel-clock-override` 会导致 4K 显示器花屏, 需使用 `enable-hdmi20` 参数
  + 微星MAG B460M MORTAR 的 HDMI 接口不支持 4k@60hz, 只有 30hz 可用,需要使用 DP 接口

### 参考

1. <https://github.com/myqqiu/Hackintosh-B460M-MORTAR-i5-10500-iGPU-UHD630>
2. <https://github.com/szc188/MSI-B460M-MORTAR-10700K-5500XT-OC>
