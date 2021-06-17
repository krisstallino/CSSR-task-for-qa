# Отчёт о тестировании страницы "Ассистент менеджера"

## Краткое описание

08.06.2021 - 17.06.2021 было проведено GUI, functional и usability тестирование веб-страницы "Ассистент менеджера".

Проведенное тестирование не является исчерпывающим.

На тестирование затрачено: 24 часа

В результате тестирования выявлены следующие дефекты:
* [Верстка страницы не соответствует макету](https://github.com/krisstallino/CSSR-task-for-qa/issues/1#issue-918447905)
* [Блок с черной рамкой не исчезает при переключении между столбиками](https://github.com/krisstallino/CSSR-task-for-qa/issues/2#issue-918719533)
* [Неверное заполнение столбцов с процентами паттерном](https://github.com/krisstallino/CSSR-task-for-qa/issues/3#issue-918732788)
* [Ссылка «Софт для быстрого создания скриншотов» ведет на неверный адрес](https://github.com/krisstallino/CSSR-task-for-qa/issues/4#issue-918775062)
* [При submit кнопки "Отправить" не отправляется POST запрос](https://github.com/krisstallino/CSSR-task-for-qa/issues/5#issue-921632943)
* [Адаптивная верстка страницы отсутствует](https://github.com/krisstallino/CSSR-task-for-qa/issues/6#issue-923714537)
* [Кроссбраузерность. Internet Explorer 11](https://github.com/krisstallino/CSSR-task-for-qa/issues/7#issue-923739531)
* [Кроссбраузерность. Google Chrome 81](https://github.com/krisstallino/CSSR-task-for-qa/issues/8#issue-923743280)
* [Кроссбраузерность. Android 8 (Chrome)](https://github.com/krisstallino/CSSR-task-for-qa/issues/9#issue-923761458)
* [Кроссбраузерность. iOS 10 (Safari)](https://github.com/krisstallino/CSSR-task-for-qa/issues/10#issue-923763821)
* [Чекбокс "Чувство прекрасного" во вкладке "60%" отрабатывает неверно](https://github.com/krisstallino/CSSR-task-for-qa/issues/11#issue-923778394)
* [Грамматические ошибки в блоке с черной рамкой](https://github.com/krisstallino/CSSR-task-for-qa/issues/12#issue-923790402)
* [Вкладка "46%" постоянно показывает колесо загрузки](https://github.com/krisstallino/CSSR-task-for-qa/issues/13#issue-923867758)
* [Вкладка "10%" не загружается](https://github.com/krisstallino/CSSR-task-for-qa/issues/14#issue-923875608)
* [Поле EMAIL не выдает ошибку при вводе некорректного адреса](https://github.com/krisstallino/CSSR-task-for-qa/issues/15#issue-923886576)

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
* [чек-лист](https://docs.google.com/spreadsheets/d/1lVneSGsB50Slpu5xiSca-b3tEWf0ZOBDQ9I--tkCmxU/edit?usp=sharing)


В качестве объекта тестирования выступает веб-страница [Ассистент менеджера](https://csssr.github.io/qa-engineer/#).  
1. Соответствие [макету](https://www.figma.com/file/CtJDsg3EvAYWFfY7bEMeKZ/QA-%D1%82%D0%B5%D1%81%D1%82)  
Ожидаемый результат - соответствует
2. Соответствие техническому заданию  
Ожидаемый результат - соответствует
3. Кроссбраузерность   
Ожидаемый результат:
Internet Explorer 11 - верстка, шрифты соответствуют макету  
Google Chrome 81 - верстка, шрифты соответствуют макету  
Safari 10.1 - верстка, шрифты соответствуют макету  
iOS 10 (Safari) - верстка, шрифты соответствуют макету  
Android 8 (Chrome) - верстка, шрифты соответствуют макету

### Тестирование производилось в следующем окружении:
* macOS Big Sur ver.11.4
* Safari ver.11.4
* Java ver.11.0.10
* ItelliJ IDEA ver.2021.1.2
* Google Chrome ver.91.0.4472.77
* Chrome DevTools
* Addons for Google Chrome: PerfectPixel, WebDeveloper, Charset
* browserstack.com