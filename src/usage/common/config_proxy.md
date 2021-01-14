# 设置代理

用Nox配合来给手机app抓包，往往涉及到给Nox配置代理。

比如对于Mac汇总Charles中的代理配置是：

![mac_charles_proxy_info.png](../../assets/img/mac_charles_proxy_info.png)

* IP: `10.108.129.57`
* 端口: `7777`

然后去给Nox中WiFi设置此代理配置信息：

先去设置中看看WiFi的配置：

![nox_settings_wifi](../../assets/img/nox_settings_wifi.png)

![nox_settings_wifi_enable](../../assets/img/nox_settings_wifi_enable.png)

点击后也没有设置代理的地方：

![nox_wifi_wiredssd](../../assets/img/nox_wifi_wiredssd.png)

右上角 高级：

![nox_wifi_upright_advanced](../../assets/img/nox_wifi_upright_advanced.png)

高级WLAN：

![nox_advanced_wifi](../../assets/img/nox_advanced_wifi.jpg)

也没有。

后来找到了：

长按`WiredSSD`后，出现弹框，选择`修改网络`：

![nox_wiredssd_edit_network](../../assets/img/nox_wiredssd_edit_network.png)

点击`显示高级选项`：

![nox_show_advanced_options](../../assets/img/nox_show_advanced_options.png)

然后就可以设置代理了：

![nox_config_wifi_info](../../assets/img/nox_config_wifi_info.png)

比如，选择`手动`：

![nox_wifi_proxy_manual](../../assets/img/nox_wifi_proxy_manual.png)

设置代理的IP和端口：

![nox_wifi_proxy_ip_port](../../assets/img/nox_wifi_proxy_ip_port.png)

设置完毕后点击`保存`。

注：给WiFi设置了代理后，系统会提示：`网络可能会受到监控 受到不明第三方的 监控`

![nox_notice_network_monitored](../../assets/img/nox_notice_network_monitored.png)

忽略此提示即可。
