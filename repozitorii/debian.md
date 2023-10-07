---
cover: ../.gitbook/assets/debian-logo-1024x576.png
coverY: 0
---

# Debian

## Установка репозиторий Debina

Debian 8 (Jessie)&#x20;
Debian 9 (Stretch)&#x20;
Debian 10 (Buster)&#x20;
Debian 11 (Bullseye)&#x20;
Debian 12 (Bookworm)

Debian использует APT как менеджер для установки или обновление пакетов, но также и для обновления всего дистрибутива. Обычно конфигурация APT меняется незначительно, за исключением кодового имени. Но иногда файл /etc/apt/sources.list требует некоторых изменений для подключения к другому релизу. В этом случае список репозиториев Debian о котором речь идет, придет вам на помощь. Для редактирования sources.list требуется воспользоваться следующей командой.
<code>sudo nano /etc/apt/sources.list</code>

### Список репозиториев в sources.list
#### Debian 8 (Jessie)
<code>
deb http://ftp.debian.org/debian jessie main contrib non-free 
deb-src http://ftp.debian.org/debian jessie main contrib non-free
</code><code>
deb http://ftp.debian.org/debian jessie-updates main contrib non-free 
deb-src http://ftp.debian.org/debian jessie-updates main contrib non-free
</code><code>
deb http://security.debian.org/ jessie/updates main contrib non-free 
deb-src http://security.debian.org/ jessie/updates main contrib non-free 
</code><code>
deb http://ftp.debian.org/debian jessie-backports main contrib non-free
</code>

#### Debian 9 (Stretch)
<code>
deb http://ftp.debian.org/debian stretch main contrib non-free 
deb-src http://ftp.debian.org/debian stretch main contrib non-free
</code><code>
deb http://ftp.debian.org/debian stretch-updates main contrib non-free 
deb-src http://ftp.debian.org/debian stretch-updates main contrib non-free
</code><code>
deb http://security.debian.org/ stretch/updates main contrib non-free 
deb-src http://security.debian.org/ stretch/updates main contrib non-free 
</code><code>
deb http://ftp.debian.org/debian stretch-backports main contrib non-free
</code>

#### Debian 10 (Buster)
<code>
deb http://ftp.debian.org/debian buster main contrib non-free 
deb-src http://ftp.debian.org/debian buster main contrib non-free
</code><code>
deb http://ftp.debian.org/debian buster-updates main contrib non-free 
deb-src http://ftp.debian.org/debian buster-updates main contrib non-free
</code><code>
deb http://security.debian.org/ buster/updates main contrib non-free 
deb-src http://security.debian.org/ buster/updates main contrib non-free 
</code><code>
deb http://ftp.debian.org/debian buster-backports main contrib non-free
</code>

#### Debian 10 (Buster) RU
<code>
deb http://mirror.corbina.net/debian/ buster main 
deb-src http://mirror.corbina.net/debian/ buster main
</code><code>
deb http://security.debian.org/debian-security buster/updates main 
deb-src http://security.debian.org/debian-security buster/updates main
</code><code>
deb http://mirror.corbina.net/debian/ buster-updates main 
deb-src http://mirror.corbina.net/debian/ buster-updates main
</code>

#### Debian 11 (Bullseye)
<code>
deb http://ftp.debian.org/debian bullseye main contrib non-free 
deb-src http://ftp.debian.org/debian bullseye main contrib non-free
</code><code>
deb http://ftp.debian.org/debian bullseye-updates main contrib non-free 
deb-src http://ftp.debian.org/debian bullseye-updates main contrib non-free
</code><code>
deb http://security.debian.org/debian-security bullseye-security main contrib non-free 
deb-src http://security.debian.org/debian-security bullseye-security main contrib non-free 
</code><code>
deb http://ftp.debian.org/debian bullseye-backports main contrib non-free
</code>

#### Debian 12 (Bookworm)
<code>
deb http://deb.debian.org/debian/ bookworm main non-free-firmware 
deb-src http://deb.debian.org/debian/ bookworm main non-free-firmware
</code><code>
deb http://security.debian.org/debian-security bookworm-security main non-free-firmware 
deb-src http://security.debian.org/debian-security bookworm-security main non-free-firmware
</code><code>
deb http://deb.debian.org/debian/ bookworm-updates main non-free-firmware 
deb-src http://deb.debian.org/debian/ bookworm-updates main non-free-firmware
</code><code>
deb http://deb.debian.org/debian bookworm-backports main contrib non-free non-free-firmware 
deb-src http://deb.debian.org/debian bookworm-backports main contrib non-free non-free-firmware
</code>

`https://wiki.it-kb.ru/unix-linux/debian/bookworm/linux-how-to-add-debian-12-bookworm-default-repos`
