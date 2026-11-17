
# _Мособлгаз_ для Home Assistant
>
> Форк https://github.com/alryaz/hass-mosoblgaz с исправлением багов и новой авторизацией.
>
> Предоставление информации о текущем состоянии ваших контрактов с Мособлгаз.
>
> [![hacs_badge](https://img.shields.io/badge/HACS-Default-green.svg?style=for-the-badge)](https://github.com/custom-components/hacs)
> [![Лицензия](https://img.shields.io/badge/%D0%9B%D0%B8%D1%86%D0%B5%D0%BD%D0%B7%D0%B8%D1%8F-MIT-yellow.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)


## Описание

Данная интеграция предоставляет возможность системе Home Assistant опрашивать API Мособлгаза и передавать показания по счётчикам.

На данный момент интеграцией реализован реализован следующий функционал:
* авторизация с поддержкой CAPTCHA;
* отображение основной информации о лицевом счёте;
* отображение последних начислений (по различным статьям);
* отображение основной информации по установленным устройствам;
* передача показаний (при наличии счётчика).

## Установка

### Home Assistant Community Store
