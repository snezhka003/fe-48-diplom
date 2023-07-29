[![Build status](https://ci.appveyor.com/api/projects/status/wcr4wqcgql726h2h?svg=true)](https://ci.appveyor.com/project/snezhka003/fe-48-diplom)

# Дипломная работа к профессии Frontend-разработчик «Система бронирования ж/д билетов»

### Краткое описание задачи дипломной работы
Создать SPA на React для сервиса покупки билетов на ж/д, свёрстанное по [макетам в Figma](https://www.figma.com/file/7981GjEsjSpBUKolk4xFoT/%D0%97%D0%B0%D0%BA%D0%B0%D0%B7-%D0%B1%D0%B8%D0%BB%D0%B5%D1%82%D0%BE%D0%B2?node-id=0%3A1), в котором в качестве API используется [внешний сервер](https://students.netoservices.ru/fe-diplom/).

## Этапы разработки
1. [Установка и настройка проекта](./reference/steps/setup.md).
2. [Вёрстка проекта и роутинг](./reference/steps/markup.md).
3. [Компоненты](./reference/steps/сomponents.md).
4. [Собираем всё вместе](./reference/steps/finish.md).

Также настоятельно рекомендуется сдавать работу на этих промежуточных этапах вашему дипломному руководителю. Старайтесь делать это как можно чаще для того, чтобы избежать лишнего переписывания кода в процессе.

## Что является итогом работы
1.	Репозиторий на GitHub с файлами вашего проекта.
2. Страница на GitHub Pages c демо вашего проекта.

## Описание проекта


### Основные элементы

1. Вагон.
1. Направление.
1. Группа направлений.
1. Место (билет).

### Вагон

1. Вагон может быть одним из типов: сидячий, люкс (СВ), купе, плацкарт.
1. У каждого типа вагона своя карта рассадки мест.
1. У каждого вагона своя стоимость билетов.
1. Для каждого вагона есть возможность выбора дополнительных услуг: 
бельё, кондиционер и Wi-Fi.
1. Для некоторых вагонов стоимость белья включена в стоимость билета, то есть стоимость белья не должна прибавляться при формировании конечной стоимости билета.

## Направление 

1. Направление — путь движения вагона из одного города в другой.
1. Направление предполагает движение поезда только в одну сторону.
1. Направление имеет дату отправления и дату прибытия.

## Группа направлений

1. Используется для того, чтобы обеспечить возможность путешествия из одного города в другой и обратно.
1. Объединяет в себе два направления

## Место (билет)

1. Имеет свой номер на карте вагона.
1. Может быть занято другим пассажиром.
1. Закреплено за конкретным направлением.


### Далее [Информация по API](./reference/api.md)
