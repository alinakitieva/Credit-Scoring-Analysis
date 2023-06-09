# Исследование надёжности заёмщиков

## Описание проекта

Заказчик — кредитный отдел банка. Нужно исследовать влияние семейного положения и количества детей клиента на факт погашения кредита в срок. Результаты исследования будут использованы при разработке модели кредитного скоринга для оценки платежеспособности потенциальных заемщиков.

## Описание данных

- children — количество детей в семье
- days_employed — общий трудовой стаж в днях
- dob_years — возраст клиента в годах
- education — уровень образования клиента
- education_id — идентификатор уровня образования
- family_status — семейное положение
- family_status_id — идентификатор семейного положения
- gender — пол клиента
- income_type — тип занятости
- debt — имел ли задолженность по возврату кредитов
- total_income — ежемесячный доход
- purpose — цель получения кредита

## Вывод по итогам исследования
На основе проведенного анализа данных можно сделать следующие выводы: семейное положение и наличие детей в семье имеют значительное влияние на вероятность погашения кредита. Например, у клиентов, принадлежащих к категории "многодетные", вероятность стать должником составляет 9.2%, а у клиентов, которые не состоят в браке, эта вероятность составляет 9.8%. Это говорит о том, что семьи без детей и люди, потерявшие супруга/супругу, являются наиболее надежными заемщиками для банка.

Такие результаты указывают на важность учета семейного положения и количества детей при оценке платежеспособности клиентов. Банк может использовать эту информацию при разработке модели кредитного скоринга, чтобы более точно оценивать риски и предотвращать возможные задолженности по кредитам.
