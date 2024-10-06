# Копирование и скачивание контента с закрытых каналов

В Telegram есть возможность запретить копирование сообщений,
копирование текста сообщений, скачивание любых фото / видео из чата / канала.

Но эту возможность достаточно несложно обойти, для этого нужно использовать Web-версии
Telegram и браузерные расширения.

Браузерных версий аж две:
1. [Telegram WebK](https://telegram.org/dl/webk)
2. [Telegram WebA](https://telegram.org/dl/weba)

В любой из них можно легко скопировать текст сообщения, если выделить его
и просто потянуть в любой текстовый редактор, например VS Code. Возможно придётся
браузер и текстовый редактор уменьшить так, чтобы они оба поместились рядом на одном экране.

Сохранять картинки тоже несложно, нужно нажать правой кнопкой по картинке,
выбрать __Inspect__ и дальше в HTML-разметке найти ссылку на картинку. В __Telegram WebA__
это оказалось сделать чуть сложнее, потому что там клик по картинке открывает контекстное меню
самого Telegram, но тогда можно просто сделать __Inspect__ где угодно и найти нужный блок – при
наведении курсора на элемент в разметке, он сразу же подсветится на страничке. Нашли нужный
элемент с картинкой, дальше дело техники.

А вот скачивать видео уже просто так не получится.
Самый простой вариант – использовать расширения для Chrome, возможно для Firefox тоже
есть такие расширения, но я не пробовал. А вот для Chrome точно есть рабочие extensions.
__Важно.__ Расширения эти работают исключительно при использовании
[Telegram WebK](https://telegram.org/dl/webk).

## Telegram Restricted Content Downloader

[ссылка](https://chromewebstore.google.com/detail/tg-download-%D0%B7%D0%B0%D0%B3%D1%80%D1%83%D0%B7%D1%87%D0%B8%D0%BA-%D0%BE%D0%B3%D1%80/kinmpocfdjcofdjfnpiiiohfbabfhhdd) (__4.9 / 5__, 943 оценки)

__Другое название:__ TG Download - Загрузчик ограниченного контента Telegram

Лучшее расширение из всех, что я пробовал, потому что, именно это расширение
работает без ограничений – не требует денег, чтоб скачивать больше 3 видео / фото за раз.
__Один минус, если сообщение с видео редактировалось, то скачать видео не получится.__

## Другие расширения

Их все объединяет то, что можно скачать видео
только 3 раза и дальше расширение потребует оплаты. \
И кажется они все также __не умеют скачивать видео, если сообщение было отредактировано.__

### Telegram Private Video Downloader

[ссылка](https://chromewebstore.google.com/detail/%D1%81%D0%BA%D0%B0%D1%87%D0%B8%D0%B2%D0%B0%D0%B9%D1%82%D0%B5-%D0%B2%D0%B8%D0%B4%D0%B5%D0%BE-%D1%81-%D1%87%D0%B0%D1%81%D1%82%D0%BD%D1%8B/gdfhmpjihkjpkcgfoclondnjlignnaap) (__4.7 / 5__, 428 оценок)

__Другое название:__ Скачивайте видео с частных каналов Telegram

### TG Downloader - Telegram Video Download

[ссылка](https://chromewebstore.google.com/detail/tg-downloader-telegram-%D1%81%D0%BA/ioiepomamdncfjkigofklhciigbonnlk) (__4.0 / 5__, 293 оценки)

__Другое название:__ TG Downloader - Telegram скачать видео

### Telegram Restrcted Content Downloader - TG Downloader

[ссылка](https://chromewebstore.google.com/detail/telegram-restrcted-conten/oiaaacjagllkcoookaphpkghhiopejco) (__4.7 / 5__, 37 оценок)

### Telegram Video Downloader - TVD

[ссылка](https://chromewebstore.google.com/detail/telegram-video-downloader/lbfjfamhbgbaldijoohdfbdfkgmpdbni) (__3.9 / 5__, 45 оценок)

__Другое название:__ Telegram Video Downloader - Telegram скачать видео

### Telegram downloader - TG Video Photo Download

[ссылка](https://chromewebstore.google.com/detail/telegram-downloader-%D1%81%D0%BA%D0%B0%D1%87%D0%B0/kofmimpajnbhfbdlijgcjmlhhkmcallg) (__4.6 / 5__, 51 оценка)

__Другое название:__ Telegram downloader - скачать видео с телеграмма

### TG Downloader - Telegram Video Download

[ссылка](https://chromewebstore.google.com/detail/tg-downloader-telegram-%D1%81%D0%BA/kockkcmeepajnplekamhbkgjomppgdhp) (__2.5 / 5__, 6 оценок)

__Другое название:__ TG Downloader - Telegram скачать видео

А этот вроде нерабочий был.
