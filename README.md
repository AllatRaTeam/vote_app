# Система электронного голосования

Написать программу для проведения выборов. Избиратели должны предварительно зарегистрироваться в системе. Администратор заполняет список кандидатов. Каждый участник (по сети) или с того же самого компьютера входит в систему и голосует. Данные о проголосовавших накапливаются в базе данных. Дважды проголосовать нельзя. По окончании периода голосования администратор запускает процедуру подсчета голосов и система выдает результат.

_Основные алгоритмы:_

Подведение итогов выборов.


Рекомендуемая диаграмма классов
![](http://math.sgu.ru/sites/chairs/prinf/materials/java/images/task1.gif)

Интерфейсы:

* Интерфейс для входа в систему.
* Интерфейс для регистрации пользователей.
* Интерфейс для создания голосования.
* Интерфейс для голосования.
* Интерфейс для проверки результатов голосования.

Таблицы в базе данных:

Выборы (наименование, сроки и т.д.)
Кандидаты
Пользователи

*Модель веб-сервер* 