# Отладочная плата для Flipper Zero на базе ST-Link V3

![Flipper Zero Devboard with Stlink V3 ](https://cdn.flipperzero.one/devboard-stlinkv3.png)

Отладочная плата для продвинутых разработчиков, которым нужна внутрисистемная отладка своих программ. Построена на базе обычного [StLink V3 Mini](https://www.st.com/en/development-tools/stlink-v3mini.html), **разница только в формфакторе** и удобстве подключения. Дополнительно на плату выведены неиспользуемые интерфейсы STLink и неиспользуемые GPIO во Flipper Zero.

!!! warning "Отладная плата не нужна для прошивки Flipper Zero "

    Вы можете обновлять прошивку, разрабатывать и загружать свою прошивку во Flipper Zero по USB без отладочной платы! Отладочная плата нужна для внутрисистемной отладки запущенных программ, например через GDB, OpenOCD. Если вы точно не знаете как ее использовать, эта плата вам не нужна.    

### Технические характеристики

* ST-Link V3 Mini для прошивки и внутрисистемной отладки
* Встроенный UART to USB подключенный к UART во Flipper Zero (GPIO 13, 14)
* Выводы неиспользуемых GPIO во Flipper Zero для отладки и макетирования