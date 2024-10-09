# Маршруты для роутера Keenetic

 Зайти в web интерфейс роутера, выбрать `Меню/ Маршрутизация / Загрузить из файла` http://192.168.1.1/staticRoutes В строке интерфейс выбрать ваш VPN конфиг (разницы нет **OpenVPN, PPTP, WireGuard, AmneziaWG, Socks5**) и нажать загрузить. Если с первого раза не загрузились все маршруты, еще раз нажать загрузить и роутер добавит недостающие маршруты.

![Screenshot](https://rockblack.su/images/Screenshot_153.jpg)
> [!NOTE]
> Таким способом выход в Youtube, Instagram и другие сервисы будет через VPN, а на другие сервисы и сайты через вашего провайдера.


____

Если после загрузки маршрутов у вас **перестал работать кинопоиск**, то нужно добавить **Статический маршрут** и поставить птичку на `эксклюзивный маршрут`, что даст приоритет этому маршруту. 

В интерфейсе выбрать вашего провайдера, в данном примере - `Подключение Ethernet`

:white_check_mark:Добавить данные ip адреса с `маской 24` как на скриншоте
```
5.255.255.0
```
```
77.88.21.0
```
```
87.250.247.0
```
```
87.250.250.0
```
```
87.250.251.0
```
```
87.250.254.0
```
```
93.158.134.0
```
```
213.180.199.0
```


![Screenshot](https://rockblack.su/images/Screenshot_160.jpg)

____


:white_check_mark:Если после добавления маршрутов Instagram, Twitter и других сервисов, они не работают, то нужно добавить **DNS DoT** и затем очистить кэш и куки приложения.

`94.140.14.14`  dns.adguard-dns.com

`94.140.15.15` dns.adguard-dns.com

`8.8.8.8`  dns.google

`8.8.4.4`  dns.google

`1.1.1.1` cloudflare-dns.com

`1.0.0.1`  cloudflare-dns.com

![Screenshot](https://rockblack.su/images/vless/DNS1.jpg)

![Screenshot](https://rockblack.su/images/vless/DNS2.jpg)


____
> [!TIP]
> [VPN на роутер](https://rockblack.su/price) - WireGuard, AmneziaWG, OpenVPN, Vless, Outline, Socks5

> [Телеграмм бот](https://t.me/Cripto_Plusbot)

> [Телеграмм группа](https://t.me/rockblack_vpn)
