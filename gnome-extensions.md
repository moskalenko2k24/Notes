# Полезное для GNOME

## Полезные ссылки

[Nautiterm](https://github.com/mwahlroos/Nautiterm) \
[Add more than one keyboard shortcut for an action](https://superuser.com/questions/409843/add-more-than-one-keyboard-shortcut-for-an-action-in-gnome) \
[5 GNOME keyboard shortcuts to be more productive](https://fedoramagazine.org/5-gnome-keyboard-shortcuts-to-be-more-productive/)


## Расширения для GNOME

Надо сразу сказать, что расширения переоценены, я по началу использовал около десятка.
Сейчас я использую только Power Profile Switcher, G3kbSwitch, VIM Alt-Tab
(обычному человеку и последних 2 не нужны = это для вимеров).
Можно жить без трея, не особо он и нужен, но из-за того, что программы типа Viber,
нельзя полностью закрыть, лично я всё-таки использую расширения для трея, чтобы
видеть, закрыл ли я программу полностью или нет.

### 1. AppIndicator and KStatusNotifierItem Support

[ссылка](https://extensions.GNOME.org/extension/615/appindicator-support/)

Расширение, добавляющее трей, которого в современном GNOME по умолчанию нет.
К сожалению приложения типа Viber, WhatsApp(неофициальный клиент)
легко закрыть так, что они останутся висеть, благодаря трею это хотя бы видно.
А так кажется смысла особо прям нет, в Gnome философия другая.

### 2. Power Profile Switcher

[ссылка](https://extensions.gnome.org/extension/5575/power-profile-switcher/)

Очень полезное расширение. Когда ноутбук переходит на батарею,
расширение автоматически включает режим "экономии", когда ноутбук начинает работать
от сети, то сразу включается режим "производительности". Возможно когда-то в GNOME сделают
такое из коробки, по крайней мере этого хотелось бы не меньше чем трей, если не больше.
Для тех кто живёт в Украине(в том числе для меня) очень полезно.

### 3. G3kbSwitch

[ссылка](https://github.com/lyokha/g3kb-switch)

Важнейшее расширение для вимеров.
Оно нужно для работы Vim-плагина [Vim-xkbswitch](https://github.com/lyokha/vim-xkbswitch).
Расширение позволяет программно изменять язык ввода, а это нужно чтобы в Vim при нажатии на Esc,
автоматически переключался на английский. Язык, который был в insert mode "запоминается" и автоматически
восстанавливается при переходе в insert mode.

~~Единственное расширение, которое нужно ставить (собирать) самому из исходников.~~ \
Уже есть пакеты для Arch, Fedora, Nix / NixOS, в README всё есть, никакой make install не нужен!

### 4. VIM Alt-Tab

[ссылка](https://extensions.gnome.org/extension/2212/vim-alt-tab/)

Расширение исключительно для вимеров. Позволяет в Alt + Tab использовать вместо
стрелок Left / Right клавишы h / l. Неудобно только то, что h / l работают только на английском языке (т.е обрабатывается не ввод клавиш h / l, а именно букв), возможно исправят.

### 5. Just Perfection

[ссылка](https://extensions.GNOME.org/extension/3843/just-perfection/)

Расширение для "тонкой" настройки GNOME. Фактически это ещё один GNOME Tweaks.
В GNOME Tweaks не всё можно настроить, а в этом расширении можно много чего менять:
высоту верхней панели, размеры иконок при Alt + Tab, многие элементы можно скрывать и.т.д.

### 6. Blur my Shell

[ссылка](https://extensions.gnome.org/extension/3193/blur-my-shell/)

Позволяет сделать верхнюю панель прозрачной, но у этого расширения лично я наблюдал
какие-то глюки.

### 7. Clipboard History

[ссылка](https://extensions.gnome.org/extension/4839/clipboard-history/)

Название говорит за себя. Расширение хранит историю буфера обмена, которую можно
легко посмотреть нажав на иконку на панели. Полезно, если хранишь в буфере что-то важное,
и постоянно теряешь :)

### 8. OpenWeather

[ссылка](https://extensions.gnome.org/extension/750/openweather/)

Просмотр погоды, на панели показывает температуру, а при нажатии на иконку кучу других подробностей, в том числе прогноз на следующие часы / дни.

### 9. Vitals

[ссылка](https://extensions.gnome.org/extension/1460/vitals/)

Показывает системную информацию, такую как использование памяти, загруженность процессора,
температуру и.т.д.

### 10. Browser tabs

[ссылка](https://extensions.gnome.org/extension/4733/browser-tabs/)

_Search and switch to browser tabs using GNOME overview/ArcMenu_

### 11. Dash to Panel

[ссылка](https://extensions.gnome.org/extension/1160/dash-to-panel/)

_An icon taskbar for the Gnome Shell_ \
Иконки приложений на панели как в Windows / KDE Plasma.

### 12. Space Bar

[ссылка](https://extensions.gnome.org/extension/5090/space-bar/)

_Replaces the 'Activities' button with an i3-like workspaces bar._ \
Вместо кнопки "Activities" появляются кнопки с номерами рабочих столов,
удобно, чтоб быстро по ним переключаться мышкой. Hot Corner остаётся рабочим,
его можно использовать для перехода по окнам / рабочим столам.

### 13. ArcMenu

[ссылка](https://extensions.gnome.org/extension/3628/arcmenu/)

_Application menu for GNOME Shell_ \
Меню приложений в стиле KDE, зачем оно для GNOME я не понимаю.
По UI прикольно, по UX имхо не вписывается в GNOME.

### 14. Dash to Panel

[ссылка](https://extensions.gnome.org/extension/1160/dash-to-panel/)

_An icon taskbar for the Gnome Shell_ \
Аналогично, делает из Gnome подобие KDE, непонятно зачем.

### 15. Desktop Icons NG

[ссылка](https://extensions.gnome.org/extension/2087/desktop-icons-ng-ding/)

Рабочий стол с иконками для Gnome.
Не вписывается в философию Gnome, но кому-то ж это надо.

### 16. Light Dict

[ссылка](https://extensions.gnome.org/extension/2959/light-dict/)

Расширение для автоматического перевода выделенного текста,
похоже на расширения в браузерах.

### 17. Pop Shell

[ссылка](https://github.com/pop-os/shell)

Что-то для любителей [i3wm](https://i3wm.org). \
_The core feature of Pop Shell is the addition of advanced tiling window management — a feature that has been highly sought within our community. For many — ourselves included — i3wm has become the leading competitor to the GNOME desktop._

### 18. WinTile

[ссылка](https://extensions.gnome.org/extension/1723/wintile-windows-10-window-tiling-for-gnome/)

Тоже что-то для тайлинга.

### 19. Easy Docker Containers

[ссылка](https://extensions.gnome.org/extension/2224/easy-docker-containers/)

_A GNOME Shell extension (GNOME Panel applet) to be able
to generally control your available Docker containers._

