# IPset4Static
Here are the files for ipset + iptables. Allows you to direct any website to VPN by domain name

It is possible to configure with one VPN or two (one main, the second backup + custom redirection to a specific one)

Compatible with Bird4Static (from Bird4Static version 3.9 and higher) and is its addon, but IPset4Static can work separately.

Designed for Keenetic routers with installed entware, as well as for any system with opkg packages, and for which the system is located in the*/opt/

**Requires AdguardHome or dnsmasq installed and configured before installation**

Так что перед установкой нужно один из них настроить, какой выбрать и как настроить описано [здесь](https://github.com/DennoN-RUS/IPset4Static/wiki/Перед-установкой)

## Installing the IPset4Static service
1) Log in via ssh to the entware environment: `ssh root@192.168.1.1`

2) Run:
    ```bash
   opkg install git git-http
   git clone https://github.com/DennoN-RUS/IPset4Static.git
   chmod +x ./IPset4Static/*.sh
   ./IPset4Static/install.sh 
    ```
Next, select the desired parameters.

Более подробная инструкция установки и описание [тут](https://github.com/DennoN-RUS/IPset4Static/wiki/Установка)

---
Веб-интерфейс: [web4static](https://github.com/spatiumstas/web4static)

Канал в телеграме: [тут](https://t.me/bird4static)

Чат в телеграме: [тут](https://t.me/bird4static_chat)

Поддержать проект можно через [yoomoney](https://yoomoney.ru/to/41001872039390) и [cloudtips](https://pay.cloudtips.ru/p/76ea7dde)
