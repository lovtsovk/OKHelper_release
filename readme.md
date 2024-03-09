### OKHelper 1.12.5.2:
- Исправление ошибок 1.12.5.1
### OKHelper 1.12.5.2
##### Что нового:
- Теперь можно загружать сразу несколько GPX треков за один раз.
- Изменён внутренний алгоритм загрузки треков GPX. Теперь перед загрузкой треки GPX проходят предварительную обработку, что исключает проблемы с ',' и буквами 'C' в именах точек и треков. Этот режим включён по умолчанию, если какой-то трек загружается не корректно, то можно попробовать отключить предварительную обработку трека, для этого необходимо зажать Ctrl и кликнуть правой кнопкой мыши на кнопке GPX, появится сообщение "Безопасный режим отключён" и и на кнопке рядом с надписью GPX появится *. Обратно включается аналогично.
- Если по каким-то причинами программа не смогла найти путь к GPSBabel его можно задать из интерфейса программы не редактирую сам конфигурационный файл, для этого необходимо нажать на кнопку GPX средней кнопкой мыши. И указать расположение файла gpsbabel.exe
##### Исправления:
- теперь при поиске GPSBabel учитывается диск на который установлена система (у некоторых это может быть например D)
- Исправлена ошибка, возникающая при попытке загрузить точки( загрузить из GPX или включить сетку) из директории пути к которой содержат русские буквы.