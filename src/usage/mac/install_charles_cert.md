# 安装Charles证书


## Nox安装Charles证书

Nox安卓模拟器中：

![nox_android_emulator_desktop](../../assets/img/nox_android_emulator_desktop.jpg)

用浏览器打开：

http://chls.pro/ssl

![nox_open_chls_pro](../../assets/img/nox_open_chls_pro.png)

效率真高：都没有下载证书文件，再打开证书文件的步骤，直接弹出安装证书界面：

![nox_install_cert_popop](../../assets/img/nox_install_cert_popop.png)

然后输入 证书名称 选择 `凭据用户` 为默认的 `VPN和应用`：

![nox_cert_name_type_vpn](../../assets/img/nox_cert_name_type_vpn.png)

即可，提示已安装证书：

![nox_installed_charles_cert](../../assets/img/nox_installed_charles_cert.jpg)

## 注意：要开启锁屏PIN或密码才可以

如果本身Nox没有设置屏幕密码，则会弹框提示：

> 您需要先设置锁定屏幕PIN或密码才能使用凭据存储

![nox_require_lock_screen_pin](../../assets/img/nox_require_lock_screen_pin.jpg)

点击 确定 后，进入 解锁方式选择：

![nox_unlock_screen_type_select](../../assets/img/nox_unlock_screen_type_select.png)

此处选择了图案解锁：

选择您的图案

![nox_select_your_pattern](../../assets/img/nox_select_your_pattern.png)

图案已记录

![nox_pattern_recorded](../../assets/img/nox_pattern_recorded.png)

您的新解锁图案

![nox_your_new_unlock_pattern](../../assets/img/nox_your_new_unlock_pattern.png)

## 安装证书后确认已安装

去设置中确认是否已经安装到系统了：

![nox_desktop_settings](../../assets/img/nox_desktop_settings.jpg)

`设置`->`安全`

![nox_settings_security](../../assets/img/nox_settings_security.png)

`安全` -> `受信任的凭据`

![nox_security_truested_proof](../../assets/img/nox_security_truested_proof.png)

系统中没有Charles：

![nox_proof_system](../../assets/img/nox_proof_system.png)

`用户`中有：`Charles`

![nox_proof_user_charles](../../assets/img/nox_proof_user_charles.png)

点击查看详情：

![nox_charles_cert_detail](../../assets/img/nox_charles_cert_detail.png)
