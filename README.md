# Анализ продаж интернет-магазина компьютерных игр
  * [Описание исследования](#Описание-исследования)
  * [Описание данных](#Описание-данных)
  * [Общий вывод](#Общий-вывод)
## Описание исследования
Вы работаете в интернет-магазине «Стримчик», который продаёт по всему миру компьютерные игры.<br>
Из открытых источников доступны исторические данные о продажах игр,<br>
оценки пользователей и экспертов, жанры и платформы (например, Xbox или PlayStation).<br>
Вам нужно выявить определяющие успешность игры закономерности.<br>
Это позволит сделать ставку на потенциально популярный продукт и спланировать рекламные кампании.<br><br>
Перед вами данные до 2016 года.<br>
Представим, что сейчас декабрь 2016 г., и вы планируете кампанию на 2017-й.<br>
Нужно отработать принцип работы с данными.<br>
Неважно, прогнозируете ли вы продажи на 2017 год по данным 2016-го или же 2027-й — по данным 2026 года.<br>
## Описание данных
* `Name` — название игры
* `Platform` — платформа
* `Year_of_Release` — год выпуска
* `Genre` — жанр игры
* `A_sales` — продажи в Северной Америке (миллионы проданных копий)
* `EU_sales` — продажи в Европе (миллионы проданных копий)
* `JP_sales` — продажи в Японии (миллионы проданных копий)
* `Other_sales` — продажи в других странах (миллионы проданных копий)
* `Critic_Score` — оценка критиков (максимум 100)
* `User_Score` — оценка пользователей (максимум 10)
* `Rating` — рейтинг от организации ESRB (англ. Entertainment Software Rating Board).<br>
   Эта ассоциация определяет рейтинг компьютерных игр и присваивает им подходящую возрастную категорию.
## Общий вывод
Планирование рекламной компании на 2017 год.
* Самые популярные платформы — `PS4` и `XOne`.
* Не выявлено другой платформы, которая набирает популярность.
* Самые популярные жанры в регионах `North America` и `Europe` — `Shooter`, `Action`.
    Наиболее популярны игры с рейтингом `M` («для взрослых»).
    Жанр `Shooter` более стабилен в продажах.
* Самый популярный жанр в регионе `Japan` — `Role-Playing`.
    Для оценки влияния рейтинга стоит рассмотреть данные местной рейтинговой системы.
* Для наибольшего охвата аудитории имеет смысл обратить внимание на детские игры (рейтинги `E10+`, `E`).
    Игры с подростковым рейтингом наименее популярны.
* Оценки пользователей не влияют на продажи.
* Оценки критиков влияют на продажи.
***
_Работа над проектом велась в PyCharm 2021.3.2 (Professional Edition)_<br>
_формат ячеек Markdown различается в веб-версии и в PyCharm_