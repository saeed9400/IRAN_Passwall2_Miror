<h1 style="text-align: center;">IRAN Passwall2 Mirror (در حال ساخت)</h1>

این مخزن، برای بسته‌های **Passwall2** (luci-app-passwall2 + وابستگی‌ها) است.

- VLESS | VMess | Trojan | Shadowsocks | Hysteria | Hysteria2  
- TUIC | WireGuard | sing-box | Xray-core و ...

### هدف میرور
راه حلی برای محدودیت‌های دسترسی به سرورهای خارجی در ایران + دانلود سریع‌تر و پایدارتر فایل‌های مورد نیاز نصب passwall2

### لینک پروژه اصلی:
🔗 https://github.com/Openwrt-Passwall/openwrt-passwall2
### نحوه استفاده از این میرور در OpenWrt

 

1. فایل پایین را ویرایش کنید (با vi یا nano): 
   
    ```bash
    ~/etc/opkg/customfeeds.conf



این خط را اضافه کنید.


    ```bash
    src/gz passwall2 https://saeed9400.github.io/IRAN_Passwall2_Miror/passwall2





4. سپس دستورات زیر را اجرا کنید:

    ```bash
    opkg update
    opkg install luci-app-passwall2

نکات مهم

حتماً وابستگی‌های لازم (مثل kmod-tun، dnsmasq-full، iptables و ...) را نصب کنید...

تشکر
از تیم اصلی xiaorouji و همه توسعه‌دهندگان Passwall2 سپاسگزاریم.
گزارش مشکل یا پیشنهاد:
https://github.com/saeed9400/IRAN_Passwall2_Miror/issues
💚 موفق باشید!
