<p align="center">
 <h1>میروری از مخزن رسمی passwall2 برای کاربران ایرانی</h1>


 - **luci-app-passwall2**
 - VLESS | VMess | Trojan | Shadowsocks | Hysteria | Hysteria2  
 - TUIC | WireGuard | sing-box | Xray-core ...
</p>
<hr style="border: 1px solid #ccc; margin: 40px 0;">
<br>

### هدف میرور

راه حلی برای رفع محدودیت‌های کاربران ایرانی در دسترسی به فایل‌های مورد نیاز نصب passwall2 با سرعت و پایداری بیشتر.

### لینک پروژه اصلی:

🔗 https://github.com/Openwrt-Passwall/openwrt-passwall2

### نحوه استفاده از این میرور در OpenWrt

1: فایل زیر را ویرایش کنید (با `vi` یا `nano`):

<p>
    ```bash
    vi /etc/opkg/customfeeds.conf
</p>

2: این آدرس را به آن اضافه کنید
<p>
    ```bash
    src/gz passwall2 https://saeed9400.github.io/IRAN_Passwall2_Miror/passwall2
</p>





3: سپس دستورات زیر را اجرا کنید:

    ```bash
    opkg update
    opkg install luci-app-passwall2

### نکات مهم

حتماً وابستگی‌های لازم (مثل kmod-tun، dnsmasq-full، iptables و ...) را نصب کنید...


تشکر
از تیم اصلی xiaorouji و همه توسعه‌دهندگان Passwall2 سپاسگزاریم.


💚 موفق باشید!
