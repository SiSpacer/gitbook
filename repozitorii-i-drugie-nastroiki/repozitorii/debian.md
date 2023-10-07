---
cover: ../../.gitbook/assets/debian-logo-1024x576.png
coverY: 0
---

# Debian

## Установка репозиторий Debina

Debian 8 (Jessie)&#x20;

Debian 9 (Stretch)&#x20;

Debian 10 (Buster)&#x20;

Debian 11 (Bullseye)&#x20;

Debian 12 (Bookworm)

Debian использует APT как менеджер для установки или обновление пакетов, но также и для обновления всего дистрибутива. Обычно конфигурация APT меняется незначительно, за исключением кодового имени. Но иногда файл /etc/apt/sources.list требует некоторых изменений для подключения к другому релизу. В этом случае список репозиториев Debian о котором речь идет, придет вам на помощь. Для редактирования sources.list требуется воспользоваться следующей команду в терминале. `sudo nano /etc/apt/sources.list`

### Список репозиториев в sources.list

#### Debian 8 (Jessie)

`deb http://ftp.debian.org/debian jessie main contrib non-free`&#x20;

`deb-src http://ftp.debian.org/debian jessie main contrib non-free`&#x20;

`deb http://ftp.debian.org/debian jessie-updates main contrib non-free`&#x20;

`deb-src http://ftp.debian.org/debian jessie-updates main contrib non-free`&#x20;

`deb http://security.debian.org/ jessie/updates main contrib non-free`&#x20;

`deb-src http://security.debian.org/ jessie/updates main contrib non-free`&#x20;

`deb http://ftp.debian.org/debian jessie-backports main contrib non-free`

#### Debian 9 (Stretch)

`deb http://ftp.debian.org/debian stretch main contrib non-free`&#x20;

`deb-src http://ftp.debian.org/debian stretch main contrib non-free`&#x20;

`deb http://ftp.debian.org/debian stretch-updates main contrib non-free`&#x20;

`deb-src http://ftp.debian.org/debian stretch-updates main contrib non-free`&#x20;

`deb http://security.debian.org/ stretch/updates main contrib non-free`&#x20;

`deb-src http://security.debian.org/ stretch/updates main contrib non-free`&#x20;

`deb http://ftp.debian.org/debian stretch-backports main contrib non-free`

#### Debian 10 (Buster)

`deb http://ftp.debian.org/debian buster main contrib non-free`&#x20;

`deb-src http://ftp.debian.org/debian buster main contrib non-free`&#x20;

`deb http://ftp.debian.org/debian buster-updates main contrib non-free`&#x20;

`deb-src http://ftp.debian.org/debian buster-updates main contrib non-free`&#x20;

`deb http://security.debian.org/ buster/updates main contrib non-free`&#x20;

`deb-src http://security.debian.org/ buster/updates main contrib non-free`&#x20;

`deb http://ftp.debian.org/debian buster-backports main contrib non-free`

#### Debian 10 (Buster) RU

`deb http://mirror.corbina.net/debian/ buster main`&#x20;

`deb-src http://mirror.corbina.net/debian/ buster main`&#x20;

`deb http://security.debian.org/debian-security buster/updates main`&#x20;

`deb-src http://security.debian.org/debian-security buster/updates main`&#x20;

`deb http://mirror.corbina.net/debian/ buster-updates main`&#x20;

`deb-src http://mirror.corbina.net/debian/ buster-updates main`

#### Debian 11 (Bullseye)

`deb http://ftp.debian.org/debian bullseye main contrib non-free`&#x20;

`deb-src http://ftp.debian.org/debian bullseye main contrib non-free`&#x20;

`deb http://ftp.debian.org/debian bullseye-updates main contrib non-free`&#x20;

`deb-src http://ftp.debian.org/debian bullseye-updates main contrib non-free`&#x20;

`deb http://security.debian.org/debian-security bullseye-security main contrib non-free`&#x20;

`deb-src http://security.debian.org/debian-security bullseye-security main contrib non-free`&#x20;

`deb http://ftp.debian.org/debian bullseye-backports main contrib non-free`

#### Debian 12 (Bookworm)

`deb http://deb.debian.org/debian/ bookworm main non-free-firmware`&#x20;

`deb-src http://deb.debian.org/debian/ bookworm main non-free-firmware`&#x20;

`deb http://security.debian.org/debian-security bookworm-security main non-free-firmware`&#x20;

`deb-src http://security.debian.org/debian-security bookworm-security main non-free-firmware`&#x20;

`deb http://deb.debian.org/debian/ bookworm-updates main non-free-firmware`&#x20;

`deb-src http://deb.debian.org/debian/ bookworm-updates main non-free-firmware`&#x20;

`deb http://deb.debian.org/debian bookworm-backports main contrib non-free non-free-firmware`&#x20;

`deb-src http://deb.debian.org/debian bookworm-backports main contrib non-free non-free-firmware`

{% embed url="https://wiki.it-kb.ru/unix-linux/debian/bookworm/linux-how-to-add-debian-12-bookworm-default-repos" %}

Далее \
Сохраниеть ctrl+O\
Выход ctrl+Х
