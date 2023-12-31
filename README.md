# Project-7 Анализ продаж развлекательного приложения

**Описание проекта**

Этот проект посвящен анализу продаж развлекательного приложения Procrastinate Pro+. Цель проекта - на основе данных о пользователях, их посещениях, покупках и рекламных расходах выяснить причины убытков компании и помочь ей выйти в плюс.

**Данные**

**Данные для анализа хранятся в трех файлах:**

visits_info_short.csv - лог сервера с информацией о посещениях сайта

orders_info_short.csv - информация о заказах

costs_info_short.csv - информация о расходах на рекламу

**Описание колонок в файле visits_info_short.csv:**

User Id — уникальный идентификатор пользователя

Region — страна пользователя

Device — тип устройства пользователя

Channel — идентификатор источника перехода

Session Start — дата и время начала сессии

Session End — дата и время окончания сессии

**Описание колонок в файле orders_info_short.csv:**

User Id — уникальный идентификатор пользователя

Event Dt — дата и время покупки

Revenue — сумма заказа

**Описание колонок в файле costs_info_short.csv:**

dt — дата проведения рекламной кампании

Channel — идентификатор рекламного источника

costs — расходы на эту кампанию

**Заключение**

На основе предоставленных данных можно сделать следующие выводы:

LTV (пожизненная ценность клиента) увеличивается с течением времени для всех стран. Страны имеют различные значения LTV. Например, на 14-й день LTV для США составляет около 1, в то время как для Франции - около 0.7. Это может означать, что клиенты из США приносят больше дохода компании, чем клиенты из Франции.

ROI (возврат на инвестиций) также увеличивается с течением времени для всех стран. Страны имеют различные значения ROI. Например, на 14-й день ROI для США составляет всего 0.6, в то время как для Германии этот показатель около 1.5. Это может означать, что инвестиции в привлечение клиентов из Германии окупаются быстрее и лучше, чем инвестиции в привлечение клиентов из США. При этом можно сказать о том, что только лишь у США инвестиции в привлечение клиентов из этой не окупаются, в остальных же странах ситуация благоприятная.

Размер когорты в США значительно больше, чем в других регионах. В США размер когорты составляет 58562, в то время как во Франции и Великобритании он составляет около 10500, а в Германии - около 9000.

Средняя стоимость привлечения клиента (cac) в США также значительно выше, чем в других регионах. В США cac составляет 1.455876, в то время как в других регионах он колеблется от 0.454922 до 0.464898.

LTV и ROI увеличиваются с течением времени для всех каналов привлечения клиентов.

Каналы привлечения клиентов имеют различные значения как в LTV так и в ROI. Например, на 14-й день LTV для канала lambdaMediaAds составляет 1.766250, в то время как для канала YRabbit - 0.5. Это может означать, что клиенты, привлеченные через канал lambdaMediaAds, приносят больше дохода компании, чем клиенты, привлеченные через другие каналы.

**Как запустить проект**

Установите Jupyter Notebook или Jupyter Lab.

Откройте файл с проектом в Jupyter.

Запустите все ячейки по порядку.
