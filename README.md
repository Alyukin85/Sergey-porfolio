# Портфолио: аналитик данных

## Обо мне
Привет! Меня зовут Сергей, я начинающий аналитик данных. В этом репозитории вы можете найти некоторые из моих проектов, выполненных во время обучения и практики.

## Навыки и технологии

<ul>
  <li>Инструменты анализа данных: SQL, Excel</li>
<li>Системы управления базами данных: PostgreSQL</li>
</ul>

## Проекты
### Проект 1: Калькулятор юнит-экономики онлайн-кинотеатра

#### Что нужно было сделать:

Задача №1 Собрать калькулятор юнит-экономики онлайн-кинотеатра

Задача №2 Посчитать юнит-экономику продукта и предложить сценарий по настройке параметров для выхода на 25-процентную маржинальность

Задача №3 Собрать хорошую наглядную визуализацию, где будет показано, кто, где и в каком объеме смотрит фильмы на платформе

#### Этапы решения задачи:

**Для понимания картины, были рассчитаны следующие метрики:**

1. Кол-во подписок в каждый месяц       
2. Кол-во просмотров в каждый месяц  
3. Кол-во уникальных просматривающих пользователей в каждый месяц
4. Дата первого просмотра для каждого юзера
5. Кол-во первых просмотров для пользователя в каждый месяц
6. Среднее кол-во просмотров на одного юзера в каждом месяце

**Далее был создан калькулятора юнит-экономики продукта, для этого были рассчитаны следующие метрики:**

1. Количество повторных оплат в каждом месяце
2. Retention для каждого месяца
3. Среднее геометрическое Retention    
4. Лайфтайм       
5. LTR 
6. CAC    
7. Маржинальность

**Завершающим этапом было оформления презентации в которой расписан сценарий по настройке параметров для выхода на 25-процентную маржинальность и собрана визуализация**

>Ссылки на проект [Онлайн кинотеатр](https://drive.google.com/drive/folders/1pTzBX7qENWKAdpnZbEgij-qkVan9NvGW?usp=sharing) Excel файл с решением задачи и презентация

**Вывод:**
Уменьшение расходов маркетинга на 60 % и снижение скидок на 60% может увеличить маржу до 25%. Увеличение стоимости подписки, в данном случае может снизить Retention и приток новых пользователей.


### Проект 2: Моделирование изменения балансов студентов в SQL

#### Что нужно было сделать:

Задача №1 Смоделировать изменение балансов студентов. Баланс — это количество уроков, которое есть у каждого студента. 

Задача №2 Проверить, всё ли в порядке с данными и составить список гипотез

#### Этапы решения задачи:


1. Было рассчитано сколько всего уроков было на балансе всех учеников за каждый календарный день

2. Как это количество менялось под влиянием транзакций (оплат, начислений, корректирующих списаний) и уроков (списаний с баланса по мере прохождения уроков)

3. Создана визуализация (линейную диаграмму) итогового результата


>Ссылка на проект в [metabase](https://metabase.sky.pro/question/62322)

#### Выводы
За 2106 год учениками было куплено 21798 урока, пройдено 17264 урока. Под конец года осталось не пройдено 4534. 

1. Отношение балансов непройденных уроков к купленным урокам улучшается. В конце года оно составляет ~16%.
Этот показатель демонстрирует здоровый баланс привлечения учителей, вовлеченности студентов и "освоения" произведенных оплат.

2. Большинство пиков транзакций происходило в начале каждого месяца месяца. Это может быть связано с получением з\п. 
В связи с этим, рекомендуем запускать маркетинговые акции ближе к этим датам. Так же был перерыв в пиках с 1 апреля по 1 июля, скорее всего связано с сезоном отпусков.

**вопрос дата - инженерам:**   почему в показателях появляются отрицательные значения отношения пройденых уроков к купленным (balance)?


## Контактная информация
Email: alyukin.sergey@yandex.ru
